LIB_FLAGS = -L/opt/boost/boost_1_65_1/stage/lib -lboost_system -lboost_thread -lpthread

all:  server client

server:
	g++ chat_server.cpp $(LIB_FLAGS) -o chat_server

client:
	g++ chat_client.cpp $(LIB_FLAGS) -o chat_client

clean:
	rm -rf *.o chat_server chat_client
