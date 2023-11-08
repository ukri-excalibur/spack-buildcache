# Spack buildcache for ExCALIBUR benchmarks CI

This repository provides a [Spack OCI buildcache](https://spack.readthedocs.io/en/latest/binary_caches.html#oci-docker-v2-registries-as-build-cache) to be used in CI of [`ukri-excalibur/excalibur-tests`](https://github.com/ukri-excalibur/excalibur-tests).
This is based on [spack/github-actions-buildcache](https://github.com/spack/github-actions-buildcache).

You can see the [list of packages](https://github.com/ukri-excalibur/spack-buildcache/pkgs/container/github-actions-buildcache) produced by this buildcache.

If you want to have more packages in this buildcache, add them to the [`spack.yaml`](./spack.yaml) file.
