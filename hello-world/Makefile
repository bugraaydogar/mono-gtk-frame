ifeq ($(CSHARP_COMPILER),)
	CSHARP_COMPILER = mcs
endif

.PHONY: all
all: bin/clr/hello-world.exe

bin/clr/hello-world.exe: hello-world.cs
	mkdir -p bin/clr
	$(CSHARP_COMPILER) hello-world.cs -pkg:gtk-sharp-2.0 -o $@

clean:
	rm -rf bin