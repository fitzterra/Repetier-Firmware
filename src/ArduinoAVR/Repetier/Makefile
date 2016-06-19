# Arduino Make file. Refer to https://github.com/sudar/Arduino-Makefile

ARDUINO_DIR = /usr/local/share/arduino-1.6.7

ARCHITECTURE  = avr
BOARD_TAG    = mega
BOARD_SUB    = atmega2560
ISP_PORT = /dev/ttyUSB0
MONITOR_PORT = /dev/ttyUSB0
MONITOR_CMD = miniterm.py

#ARDMK_DIR=/usr/share/arduino
ARDMK_DIR=/home/tomc/ownCloud/Electronics/Arduino/Arduino-Makefile

USER_LIB_PATH = libraries

CXXFLAGS = -Wno-deprecated-declarations -g3

MONITOR_BAUDRATE = 230400

ARDUINO_LIBS = \
	       Wire \
	       SPI

-include $(ARDMK_DIR)/Arduino.mk

CFLAGS_STD = -Wall -Wundef -Werror
CXXFLAGS_STD = -Wall -Werror
# !!! Important. You have to use make ispload to upload when using ISP programmer
