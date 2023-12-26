# Let's Think Parallel

Welcome to the "Let's Think Parallel" repository! This project delves into parallelization techniques, specifically focusing on two major sections: CPU Parallelization and GPU Parallelization.

## CPU Parallelization

The CPU parallelization section encompasses seven sorting programs, including serial and parallel implementations (using OpenMP) and one utilizing a sorting algorithm from the STL library.
- `bbs.cpp`
- `bbp.cpp`
- `qss.cpp`
- `qsp.cpp`
- `mss.cpp`
- `msp.cpp`
- `reference.cpp`

## Compilation:
To compile all files, use:

```bash
make
```

### Execution Format:

To execute the programs, use the following format:

```bash
[executable name] [amount of random nums to generate] [number of threads to use] [seed value for rand]
```
For example:

```bash
./bbs 100000 8 10
```
## GPU Parallelization

The GPU Parallelization folder includes three programs implemented in CUDA programming:

- `thrust.cu`
- `singlethread.cu`
- `multithread.cu`

## Compilation:
To compile all files, use:

```bash
make
```
## Execution Format:
To execute the programs, use the following format:

```bash
[executable name] [amount of random nums to generate] [seed value for rand] [1 to print sorted array, 0 otherwise]

````
For example:

```bash
./thrust 1000 1 1
```
Explore the parallelization techniques and compare the CPU and GPU implementations. Feel free to experiment with different input parameters and thread configurations.

## Contributing
Feel free to contribute to the project and suggest improvements to enhance the understanding of parallelization concepts. Pull requests are welcome!
