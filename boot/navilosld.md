navilos.ld - 링커 스크립트

$ arm-none-eabi-ld -n -T ./navilos.ld -nostdlib -o navilos.axf boot/Entry.o

$ arm-none-eabi-objdump -D navilos.axf

- 링크로 실행 파일 만드는 명령어
