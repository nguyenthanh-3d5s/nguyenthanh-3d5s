## colab
```
%%writefile test.cpp
```
```
%%writefile input.txt
```
```
!g++ -std=c++17 -Wall -o test test.cpp
!./test < input.txt
```
```
!gcc -std=c17 -Wall -o test test.c -lm
!./test < input.txt
```
