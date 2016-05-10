# info for programming:
# avrdude -p atmega2560 -D -c stk500v2 -P /dev/ttyUSB0 -U flash:w:build-mega-atmega2560/AstroEQ-Firmware.hex:i
BOARD_TAG    = mega
BOARD_SUB    = atmega2560
MONITOR_PORT = /dev/ttyUSB0
CFLAGS += -g
CXXFLAGS += -g
#DEBUG = 1 # crashes simulation
#ARDUINO_DIR  = /where/you/installed/arduino-1.6.5
include /usr/share/arduino/Arduino.mk
