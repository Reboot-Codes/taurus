# Taurus

Get it? TPU-RS? Yeah, bad joke.

Taurus is a Tensor Processing Unit abstraction library that provides interoperability with the following platforms:

- EdgeTPU (a.k.a. Google Coral)
- CUDA (NVIDIA GPUs)
- **TENTATIVE:** ANE (Apple Neural Engine)
- Vulkan (GPU-agnostic HW accel)
- [OxiMath](https://github.com/Reboot-Codes/oxifluxion/tree/main/oximath) (Precision floating point calculation library, aka the `no_std` compatible option that runs on the CPU.)

Developed alongside [Clover](https://github.com/Reboot-Codes/clover) for usage in its Inference Engine component, however it's designed to be usage-case agnostic.

NOT READY FOR PRODUCTION USAGE!

## To-Do

- [ ] Setup documentation with auto-builds
- [ ] Setup CI/CD testing
- [ ] Verify feasibility of Objective-C FFI for ANE backend.
