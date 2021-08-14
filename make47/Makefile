foo := a.o b.o l.a c.o
one := $(patsubst %.o,%.c,$(foo))

two := $(foo:%.o=%.c)

three := $(foo:.o=.c)

all:
	echo $(one)
	echo $(two)
	echo $(three)
