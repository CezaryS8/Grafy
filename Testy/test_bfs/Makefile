all:
	cc -c graph.c
	cc -c main.c
	cc -c bfs_algorithm.c
	cc -c graph.c read.c 
	cc -c errors.c
	cc -o bfs main.o graph.o bfs_algorithm.o read.o  errors.o
	./bfs

clean:
	rm *.o
