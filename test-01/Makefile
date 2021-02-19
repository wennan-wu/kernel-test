cc = arm-linux-gnueabi-gcc
prom = test
obj = test.o
CFLAGES = -static

$(prom) : $(obj)
	$(cc) -o $(prom) $(obj) $(CFLAGES)

%.o: %.c
	$(cc) -c $< -o $@

clean:
	rm -rf $(obj) $(prom)
