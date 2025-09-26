## colab
```
%%writefile test.c
```
```
%%writefile input.txt
```
```
!gcc -std=c11 -Wall test.c -o test -lm
!./test < input.txt
```
```
%%writefile test.cpp
```
```
%%writefile input.txt
```
```
!g++ -std=c++11 -Wall test.cpp -o test
!./test < input.txt
```
