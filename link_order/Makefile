
SRCS         := main.c a.c b.c
SRCS_REVERSE := main.c b.c a.c

all:
	gcc $(SRCS) -o ab
	gcc $(SRCS_REVERSE) -o ba
	gcc $(SRCS) -o ab.2
	md5sum ab ba ab.2

clean:
	rm -f ab ba
