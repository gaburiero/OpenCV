#PKG_CONFIG_PATH=/usr/local/lib/pkgconfig:${PKG_CONFIG_PATH}
#export PKG_CONFIG_PATH

all:
	g++ -o kmeans kmeans.cpp  `pkg-config --cflags --libs opencv`

clean:
	-rm -f *.o
	-rm -f kmeans
