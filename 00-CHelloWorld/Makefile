# Variables para facilitar cambios futuros
CC = gcc
CFLAGS = -std=c23
TARGET = hello.exe

# Regla por defecto: compila y luego ejecuta
all: compile run

# Regla para compilar
compile:
	$(CC) $(CFLAGS) hello.c -o $(TARGET)

# Regla para ejecutar
run:
	.\$(TARGET)

# Regla para limpiar los archivos generados
clean:
	del $(TARGET) output.txt