# the compiler for C: gcc
CC = gcc

# compiler flags
# -Wall		enables all compiler's warning messages.
# -Wextra	enables some extra warning flags that are not enabled by -Wall
# -g		generates debug information to be used by GDB debugger.
CFLAGS = -g -Wall -Wextra

# build target
TARGET = multiply_matrix
TASK = 04

# lib path
LIB = ../../lib

default: $(TASK)-$(TARGET)

$(TASK)-$(TARGET):
	$(CC) $(CFLAGS) -o $(TARGET) $(LIB)/matrix.c $(LIB)/utils.c $(LIB)/my_math.c $(TASK)-$(TARGET).c

clean: 
	$(RM) $(TARGET) *.o
