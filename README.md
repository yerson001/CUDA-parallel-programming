# Compile this file (CUDA + opencv)

~~~
nvcc -o apt init.cu `pkg-config --cflags --libs opencv4`
~~~
# Execute
~~~
./apt 
~~~
