# Compile this file (CUDA + opencv)

~~~
nvcc -o apt main.cu `pkg-config --cflags --libs opencv4`
~~~
# Execute
~~~
./apt 
~~~
