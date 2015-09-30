CC = gcc
CFLAGS = -g -Wall
OUTPUT = libfuncs.a
OBJFILES = func1.o func2.o
AR = ar
.PHONY: clean

$(OUTPUT): $(OBJFILES)
	$(AR) rv $(OUTPUT) $(OBJFILES)

%.o: %.c
	$(CC) -c $< -o $@

clean:
	rm -f $(OBJFILES) $(OUTPUT)

