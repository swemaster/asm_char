SRCS=$(wildcard *.c *.s)
FLAGS=-lm -m32 -gdwarf-2 -static
TARGET=out

$(TARGET): $(SRCS)
	gcc -g -o $@ $^ $(FLAGS) 

clean:
	-rm -f $(TARGET)

