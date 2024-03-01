dep = calculator/operations.h
objects = calculator/addition.o calculator/division.o calculator/main.o calculator/multiplication.o calculator/subtraction.o

%.o: %.c $(dep)
	gcc -c -o $@ $< 

calculator/calculator: $(objects)
	gcc -o $@ $^ 

clean:
	rm -f calculator/*.o calculator/calculator
