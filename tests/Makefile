ifeq ($(OS),Windows_NT)
	EXE = .exe
endif

TARGET = tglfw_opengl3

all:
	nim c -r -d:strip -d:ImSpinner tglfw_opengl3.nim

clean:
	@-rm -f $(TARGET)$(EXE)
	@-rm -fr .nimcache

run: all
	./$(TARGET)$(EXE)
