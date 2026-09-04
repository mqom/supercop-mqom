# SUPERCOP archive of MQOM

This repository contains the `tarball` archive of MQOM-v3 for the [SUPERCOP](https://bench.cr.yp.to/supercop.html) benchmarking platform.
This archive embeds the `crypto_sign` implementations of all variants of MQOM: the three NIST security levels (`cat1`, `cat3` and `cat5`) for the base fields `GF(2)`
and `GF(16)`, for the "fast" and "short" as well as the `ct` and `ot` flavours of the signature algorithm. The implementations
make use of VAES / AES-NI, AVX2, AVX-512, GFNI, ARM NEON and ARM AES optimizations when available.
