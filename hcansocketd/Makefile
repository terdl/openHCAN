TARGET = hcansocketd
SRC = main.c

CXX = gcc
CFLAGS  = -O2 -I. -Wall -g
#CFLAGS += -DDEBUG

all:
	$(CXX) $(CFLAGS) -o $(TARGET) $(SRC)
	
clean:
	rm -f $(TARGET)
	rm -fR ./scanBuild

install:
	strip $(TARGET)
	sudo install $(TARGET) /usr/sbin
