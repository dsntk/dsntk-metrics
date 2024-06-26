**DSNTK** | Decision Toolkit

# Performance

The performance of Decision Toolkit is measured using Rust benchmarks, executed for DMN™ compatibility tests.
This approach gives the feeling how performant this toolkit is.
All benchmarks are executed on a single core of the processor AMD Ryzen 5 4600G.

| version                |    date    | perf<br/>90% | perf<br/>99% |
|------------------------|:----------:|:------------:|:------------:|
| [v0.0.4](./2024-02-04) | 2024-02-04 |    ≤ 5µs     |    ≤ 47µs    |
| [v0.0.3](./2023-12-31) | 2023-12-31 |    ≤ 5µs     |    ≤ 49µs    |
| [v0.0.1](./2023-11-11) | 2023-11-11 |    ≤ 6µs     |    ≤ 51µs    |

> Note: When the Decision Toolkit is used as a service,
> then delays related to networking have to be taken into consideration
> when estimating the overall performance.
