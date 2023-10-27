
TARGET=drmlist
CSOURCES = $(shell echo *.c)
OBJECTS = $(CSOURCES:.c=_c.o)

LDFLAGS =  -lmydrm -L ../mydrm/
BINDIR = $(PREFIX)/bin

all: $(TARGET)

$(TARGET): $(OBJECTS)
	$(CC)  $(FLAGS) -o $(TARGET) $(OBJECTS) $(LDFLAGS)

include ../base.mk
