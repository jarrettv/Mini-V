Please see https://canbus.esoterical.online/

python3 ~/katapult/scripts/flashtool.py -f ~/klipper/out/klipper.bin -d /dev/serial/by-id/usb-katapult_stm32g0b1xx_4A00290012504B4B38383620-if00

mainboard: 183fbc1d936f

provoke3d adxl ampon
make flash FLASH_DEVICE=0483:df11

8d010481812b

python3 ~/katapult/scripts/flashtool.py -i can0 -u 8d010481812b -f ~/klipper/out/klipper.bin

usb-katapult_stm32g0b1xx_4A00290012504B4B38383620-if00

python3 ~/katapult/scripts/flashtool.py -f ~/klipper/out/klipper.bin -d /dev/serial/by-id/usb-katapult_stm32g0b1xx_4A00290012504B4B38383620-if00

21183091201e

python3 ~/katapult/scripts/flashtool.py -i can0 -u 21183091201e -f ~/klipper/out/klipper.bin
