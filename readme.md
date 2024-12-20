## Resource
* [Ruby tracing part one - BPF](https://balazs.kutilovi.cz/posts/ruby-tracing-part-one-bpf)
* [docker-bpf](https://github.com/hemslo/docker-bpf)
* [Run eBPF Programs in Docker using docker-bpf](https://hemslo.io/run-ebpf-programs-in-docker-using-docker-bpf)
* [DTrace Linux](https://github.com/oracle/dtrace-utils/tree/2.0-branch)
* [ruby-install](https://github.com/postmodern/ruby-install)

## Build Ruby

Enable DTrace by passing `--enable-dtrace` to the configure script.
When using `ruby-install`: `ruby-install ruby 3.1.2 -- --enable-dtrace`.
