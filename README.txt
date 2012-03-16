to compile cpp api:

gcc -c cpp_api.cpp
ar -r cpp_api.a cpp_api.o

to build mex file using cpp api:

(in matlab)
mex mex_api.cpp cpp_api.a
