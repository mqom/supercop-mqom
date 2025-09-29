This repository contains the `tarball` archive of MQOM-v2 for the [SUPERCOP](https://bench.cr.yp.to/supercop.html).
This archive embeds the `crypto_sign` implementations of all variants of MQOM: the three NIST security levels (`cat1`, `cat3` and `cat5`) for the base fields `GF(2)`,
`GF(16)` and `GF(256)`, for the "fast" and "short" as well as ̀the `r3` and `r5` flavours of the signature algorithm. The implementations
make use of AES-NI, AVX2, AVX-512, and GFNI optimizations when available.
