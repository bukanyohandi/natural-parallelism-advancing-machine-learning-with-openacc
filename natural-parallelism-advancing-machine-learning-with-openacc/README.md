With the extension concepts of parallel computing, natural parallelism can be further blended into the realm of machine learning. This project specifically focuses on accelerating softmax regression, neural networks, and convolutional neural networks using OpenACC. OpenACC offers a simplified approach to programming for parallel computing, particularly for GPU acceleration.

The project’s aim is to demonstrate the significant impact of parallel computing in machine learning, especially when dealing with extensive data and complex models. By optimizing machine learning algorithms for GPUs, computation speeds can be greatly enhanced, thereby improving the overall efficiency and performance of these algorithms. The project involves understanding the core algorithms of softmax regression and neural networks, followed by the application of OpenACC for parallel computing on GPUs. This exploration will not only provide hands-on experience with parallel computing in machine learning but also highlight the importance of effective hardware utilization to boost algorithmic performance.

Within the submitted zip file, a folder project can be found, this will be the main project folder.
1. Navigate to the folder
2. Run `run.sh` or simply paste the below sequence of commands:
```
scancel -u 120040025
bash ./ test . sh
squeue -o "%.18 i %.9 P %.25 j %.9 u %.2 t %.10 M %.6 D %R"
```
3. Upon completion, one can find out the results information in the same directory.