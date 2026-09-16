# Усложненный make-file.  Введены переменные для параметров компиляции и исполняемых файлов

.PHONY: all clean

RELEASE_FLAGS = -O2 -Wall
DEBUG_FLAGS   = -g -O0 -Wall
RELEASE_EXEC  = example3
SOURCE        = Kazino-Royal.cpp

all: $(RELEASE_EXEC)

$(RELEASE_EXEC): $(SOURCE)
	g++ $(RELEASE_FLAGS) $(SOURCE) -o $(RELEASE_EXEC)

clean:
	rm -f $(SOURCE) *.o

