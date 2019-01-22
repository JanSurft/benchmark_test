# benchmark_test
Testing the google benchmark suite.

## installation

- `git clone git@github.com:JanSurft/benchmark_test.git`
- `cd benchmark_test`
- `mkdir build`
- `cd build`
- execute cmake twice.. will get an error otherwise if on executing `make`
- `cmake -DBENCHMARK_DOWNLOAD_DEPENDENCIES=ON -DCMAKE_BUILD_TYPE=Release ..`
- `cmake -DBENCHMARK_DOWNLOAD_DEPENDENCIES=ON -DCMAKE_BUILD_TYPE=Release ..`
- `make`

## execute tests
- `./bin/test`
