include ../../../../WaziDev.mk

ARDUINO_LIBS     += DHT

include /usr/share/arduino/Arduino.mk

monitor:
	stty -F $(MONITOR_PORT) raw $(MONITOR_BAUDRATE)
	cat $(MONITOR_PORT)
