OBJS= ansi.o		isctype.o	none.o		setlocale.o	toupper.o
OBJS+= collate.o	lconv.o		rune.o		table.o
OBJS+= collcmp.o	localeconv.o	runetype.o	tolower.o


CFLAGS= -I. -I../../inc -I../../inc/ia32 -I../../include/bsd -I../../include/efishell -I../include  -O2 -fpic -Wall -ffreestanding -fshort-wchar -fno-strict-aliasing -fno-merge-constants -fno-builtin

all: $(OBJS)
	ar rcs ../libc.a $(OBJS)

clean:
	rm -f *.o liblocalelib.a


