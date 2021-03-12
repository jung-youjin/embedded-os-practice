$ arm-none-eabi-as -march=armv7-a -mcpu=cortex-a8 -o Entry.o ./Entry.S

$ arm-none-eabi-objcopy -O binary Entry.o Entry.bin

$ hexdump Entry.bin

- Entry.S를 어셈블러로 컴파일한 후 바이너리로 덤프하는 명령어
