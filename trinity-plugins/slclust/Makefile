# Brian J. Haas

SUBS = src

all install depend clean:
	X=`pwd`; \
	for i in $(SUBS); \
	do echo '<<<' $$i '>>>'; cd $$X/$$i; $(MAKE) $@; done

# DO NOT DELETE
