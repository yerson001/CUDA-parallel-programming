# Compile this file (CUDA + opencv)

~~~
nvcc -o apt main.cu `pkg-config --cflags --libs opencv4`
~~~
# Execute
~~~
./apt path_img  ---> example    ./apt /home/yerson/cuda/lena.png
~~~
