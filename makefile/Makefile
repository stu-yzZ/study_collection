#version1
hello :main.cpp function1.cpp function2.cpp #create file named hello which depend on these three cpp file
	g++ main.cpp function1.cpp function2.cpp


#version2
# CXX = g++
# TARGET = hello
# OBJ = main.o function1.o function2.o

# $(TARGET): $(OBJ) #TARGET depends on OBJ
# 	$(CXX) -o $(TARGET) $(OBJ)

# main.o: main.cpp
# 	$(CXX) -c main.cpp

# function1.o: function1.cpp
# 	$(CXX) -c function1.cpp

# function2.o: function2.cpp
# 	$(CXX) -c function2.cpp


#version3
# CXX = g++
# TARGET = hello
# OBJ = main.o function1.o function2.o

# CXXFLAGS = -c -Wall
# $(TARGET): $(OBJ) #TARGET depends on OBJ
# 	$(CXX) -o $@ $^

# %.o: %.cpp
# 	$(CXX) $(CXXFLAGS) $< -o $@

# .PHONY: clean
# clean:
# 	rm -f *.o $(TARGET)




