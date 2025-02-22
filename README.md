## colab
```batch
%%writefile test.cpp
```
```batch
%%writefile input.txt
```
```batch
!g++ -std=c++17 -Wall -o test test.cpp
!./test < input.txt
!cat output.txt
```
