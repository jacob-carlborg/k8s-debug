## Resource

* [Ruby tracing part one - BPF](https://balazs.kutilovi.cz/posts/ruby-tracing-part-one-bpf)
* [docker-bpf](https://github.com/hemslo/docker-bpf)
* [Run eBPF Programs in Docker using docker-bpf](https://hemslo.io/run-ebpf-programs-in-docker-using-docker-bpf)
* [DTrace Linux](https://github.com/oracle/dtrace-utils/tree/2.0-branch)
* [ruby-install](https://github.com/postmodern/ruby-install)
* [Ephemeral container](https://kubernetes.io/docs/tasks/debug/debug-application/debug-running-pod/#ephemeral-container)
* [netshoot Docker image](https://github.com/nicolaka/netshoot)
* [Nixery - ad hoc Docker registry](https://nixery.dev)
* [Spying on a Ruby process's memory allocations with eBPF](https://jvns.ca/blog/2018/01/31/spying-on-a-ruby-process-s-memory-allocations/)

## Build Ruby

Enable DTrace by passing `--enable-dtrace` to the configure script.
When using `ruby-install`: `ruby-install ruby 3.1.2 -- --enable-dtrace`.
