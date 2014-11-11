CC = g++
CFLAGS = -g -Wall -pedantic
REG_FILES = r1_0Beta1/*h r1_0Beta2/*.h

regressiontest: reg_tests_driver.cpp ../../source/utf8.h ../../source/utf8/core.h ../../source/utf8/checked.h ../../source/utf8/unchecked.h $(REG_FILES)
	$(CC) $(CFLAGS) reg_tests_driver.cpp -o regressiontest
