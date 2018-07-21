# [r-immunedeconv](https://anaconda.org/grst)
![travis ci](https://api.travis-ci.org/grst-anaconda/r-immunedeconv.svg?branch=master)

Conda build for [immunedeconv](https://github.com/grst/immune_deconvolution_methods), an
R library that collects methods for estimating immune cell content from bulk RNA-seq
data.

## How to build
Summary of the [conda tutorial](https://conda.io/docs/user-guide/tutorials/build-pkgs.html).

The following command builds the package and lists an output path of
the compiled package.
```
conda build .
```

The following command gives a plain output of the output filename that will be generated:
```
conda build . --output
```

Convert the packages for all platforms:
```
conda convert --platform all <output_package.tar.bz2> -o ./build
```

Upload the package to anaconda cloud
```
# anaconda login
anaconda upload <path to compiled package>
```

