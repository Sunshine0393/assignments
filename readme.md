## Report 1
First of all there was a problem due the error, which says that project is not configured correctly, 
I Googled it, after there was sayd that i must set gcc c++ compiler,
after i figured that in my pc there is no cmake installed, then there is no make installed, installed both of them, then
I added to CMakeList.txt, set( CMAKE_CXX_COMPILER "C:/MinGW/bin/g++.exe" )
set( CMAKE_C_COMPILER "C:/MinGW/bin/gcc.exe" ), after it said that there was still configuration still not configured. After googling some hours i found that there must additional arguments in cmake command, and everyting worked great