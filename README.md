# STM32 TinyUSB example + Xinput

Simple example how to use TinyUSB with STM32 without use STM32CubeIDE trash.

- This project was made using a NUCLEO-U083RC.
- Pushing on board button going to execute an A press button of Xbox controller

## Building
```
git clone https://github.com/Loc15/xinput_stm32.git
cd xinput_stm32/
git submodule update --init
mkdir build
cd build
make
```