# ROCm and Cuda compatibility headers and tools

This is basically a set of headers to allow HIP to compile Cuda code without any or minor modifications.

Here I also include the HIP headers under [nvidia_detail](nvidia_detail) that AMD uses to compile HIP code on `nvcc`, the license should allow that.

Included is also the [hipify-perl](hipify-perl) script which is not available on some systems like Arch Linux for some reason.

- HIP CUDA headers: ROCm 5.4.3
- hipify-perl: [ROCm-Developer-Tools/HIPIFY:73c5d36e2](https://github.com/ROCm-Developer-Tools/HIPIFY/blob/73c5d36e22154f7d0d48bfd746a186fada98ed26/bin/hipify-perl)
