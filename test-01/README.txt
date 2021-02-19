1)预处理
	arm-linux-gnueabi-gcc -E test.c -o test.i
2)编译
	arm-linux-gnueabi-gcc -S test.i -o test.s
3)汇编
	arm-linux-gnueabi-gcc -c test.S -o test.o
4)链接
	arm-linux-gnueabi-gcc test.o -o test --static
