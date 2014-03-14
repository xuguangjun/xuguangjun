csapp.c中有关于线程的函数，在用gcc编译的时候要加上-lpthread参数，除此之外，还要加上-lrt参数

eg:gcc hello.c csapp.c -o hello -lpthread -lrt

pthread是指Posix线程，它是C程序中处理线程的一个标准接口，定义了大概60个函数
