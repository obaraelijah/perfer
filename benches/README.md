## Benchmark

### Python

To run the benchmark for Python, execute the following command in your terminal:

```sh
python3 fib.py
```

This command will generate a `fib-py.csv` file containing benchmark results with two columns: 'Iteration' and 'Time'. For example:

```
Iteration,Time
1,369.21750220614524
```

This benchmark runs up to 20 iterations.

### Go

For Go, you can run the benchmark using the following command:

```sh
go run fib.go
```

This will output the benchmark results directly to the console and will generate a `fib-go.csv` file containing benchmark results with two columns: "Run" and "Time", up to 20 iterations.

### Rust

To execute the benchmark for Rust, cd into the [`fib-rs`](./fib-rs) directory and run the following command:

```sh
cargo run --release
```

This will generate a `fib-rs.csv` file containing benchmark results with two columns: "Run" and "Time", up to 20 iterations.

### Julia

For Julia, run the benchmark script with:

```sh
julia fib.jl### Python

To run the benchmark for Python, execute the following command in your terminal:

```sh
python3 fib.py
```

This command will generate a `fib-py.csv` file containing benchmark results with two columns: 'Iteration' and 'Time'. For example:

```
Iteration,Time
1,369.21750220614524
```

This benchmark runs up to 20 iterations.
```

This will generate a `fib-jl.csv` file containing benchmark results with two columns: "Run" and "Time", up to 20 iterations.

### C

For C, compile and run the executable:

```sh
gcc -O3 -march=native -Wall -Wextra -o fib fib.c

./fib
```

This will generate a `fib-c.csv` file containing benchmark results with two columns: "Run" and "Time", up to 20 iterations.