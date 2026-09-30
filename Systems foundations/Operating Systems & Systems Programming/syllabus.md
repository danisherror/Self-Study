# C1. Operating Systems & Systems Programming

**Backbone:** MIT 6.1810 (formerly 6.S081, xv6 labs); book *Operating Systems: Three Easy Pieces* (free online).

**Topics**

1. Processes, threads, scheduling, context switches
2. Virtual memory, page tables, TLBs, copy-on-write
3. System calls, traps, interrupts, the kernel/user boundary
4. File systems, crash consistency, journaling
5. Concurrency: locks, lock-free structures, memory ordering
6. Linux internals: namespaces, cgroups, capabilities, seccomp
7. Virtualization: hypervisors, KVM, microVMs, how containers differ
8. Performance: perf, flame graphs, eBPF tracing (Brendan Gregg, *Systems Performance*)

**Projects**

- Complete all xv6 labs (syscalls, page tables, COW fork, locks, networking driver).
- **Mini-container runtime in C/Go:** build a tool that uses namespaces, cgroups v2, pivot\_root, seccomp, and dropped capabilities to run a process. Write a threat model listing what it does and does not isolate. This formalizes your recent container investigation.
