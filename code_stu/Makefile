CC=gcc
BIN=project
OBJ=system.o teacher.o main.o student.o principal.o
FLAG=-DDEBUG
STD=-std=gnu99

all:$(OBJ)
	$(CC) -o $(BIN) $(OBJ) && ./$(BIN)

%.o:%.c
	$(CC) $(STD) $(FLAG) -c $< -o $@

clean:
	rm -f $(BIN) $(OBJ)

