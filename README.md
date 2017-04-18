# cuda_fft

### Parameters


* cufftComplex

A single-precision, floating-point complex data type that consists of interleaved real and imaginary components.

* cufftType
```
    typedef enum cufftType_t { 
    CUFFT_R2C = 0x2a, // Real to complex (interleaved) 
    CUFFT_C2R = 0x2c, // Complex (interleaved) to real 
    CUFFT_C2C = 0x29, // Complex to complex (interleaved) 
    CUFFT_D2Z = 0x6a, // Double to double-complex (interleaved) 
    CUFFT_Z2D = 0x6c, // Double-complex (interleaved) to double 
    CUFFT_Z2Z = 0x69 // Double-complex to double-complex (interleaved) 
    } cufftType;
```


### 1D 
```
cufftPlan1d
```


### Benchmarking
* http://www.cv.nrao.edu/~pdemores/gpu/
* https://github.com/moznion/fftw-vs-cufft

fftw3 (cpu)
* http://people.sc.fsu.edu/~jburkardt/c_src/fftw3/fftw3.html
```
sudo apt-get install libfftw3-dev
```

### Doc
* http://moss.csc.ncsu.edu/~mueller/cluster/nvidia/0.8/NVIDIA_CUFFT_Library_0.8.pdf
