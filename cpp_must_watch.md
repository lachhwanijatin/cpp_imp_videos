# The Ultimate C++ Watch list (quant dev roles)

Use this master checklist to track your progress. It covers everything from core language mechanics and memory models to OS-level networking, `epoll`, bare-metal kernel bypass, and system profiling.

## Phase 1: Memory & Object Model
*Focus: Hardware interaction, lifetimes, memory structure, and build processes.*
- [ ] [The Abstract Machine — Bob Steagall (2020)](https://www.youtube.com/watch?v=ZAji7PkXaKY)
- [ ] [Class Layout — Stephen Dewhurst (2020)](https://www.youtube.com/watch?v=SShSV_iV1Ko)
- [ ] [Pointers and Memory — Ben Saks (2020)](https://www.youtube.com/watch?v=rqVWj0aVSxg)
- [ ] [Compiling and Linking — Ben Saks (2021)](https://www.youtube.com/watch?v=cpkDQaYttR4)
- [ ] [Undefined Behavior — Ansel Sermersheim & Barbara Geller (2021)](https://www.youtube.com/watch?v=NpL9YnxnOqM)

## Phase 2: Lifecycles & Value Semantics
*Focus: Avoiding heap allocations, minimizing redundant copies, and understanding expression rules.*
- [ ] [Understanding Value Categories — Ben Saks (2019)](https://www.youtube.com/watch?v=XS2JddPq7GQ)
- [ ] [Move Semantics — Nicolai Josuttis (2021)](https://www.youtube.com/watch?v=Bt3zcJZIalk)
- [ ] [Forwarding References — Mateusz Pusz (2023)](https://www.youtube.com/watch?v=0GXnfi9RAlU)
- [ ] [The Special Member Functions — Klaus Iglberger (2021)](https://www.youtube.com/watch?v=9BM5LAvNtus)
- [ ] [Everyday Efficiency: In-Place Construction — Ben Deane (2019)](https://www.youtube.com/watch?v=oTMSgI1XjF8)

## Phase 3: Polymorphism & Abstractions
*Focus: Eliminating vtable branch mispredictions and exact footprints of standard abstractions.*
- [ ] [Virtual Dispatch and its Alternatives — Inbal Levi (2019)](https://www.youtube.com/watch?v=jBnIMEb2GhA)
- [ ] [Type Erasure — Arthur O'Dwyer (2019)](https://www.youtube.com/watch?v=tbUCHifyT24)
- [ ] [Lambdas from Scratch — Arthur O'Dwyer (2019)](https://www.youtube.com/watch?v=3jCOwajNch0)
- [ ] [Smart Pointers — Arthur O'Dwyer (2019)](https://www.youtube.com/watch?v=xGDLkt-jBJ4)

## Phase 4: Metaprogramming & Types
*Focus: Compile-time execution, template mechanics, and name resolution.*
- [ ] [Templates (Part 1 of 2) — Andreas Fertig (2020)](https://www.youtube.com/watch?v=VNJ4wiuxJM4)
- [ ] [Templates (Part 2 of 2) — Andreas Fertig (2020)](https://www.youtube.com/watch?v=0dtjDTEE0hQ)
- [ ] [Function Call Resolution in C++ — Ben Saks (2024)](https://www.youtube.com/watch?v=ab_RzvGAS1Q)
- [ ] [Concepts in C++ — Nicolai Josuttis (2024)](https://www.youtube.com/watch?v=jzwqTi7n-rg)
- [ ] [Master the static, inline, const, and constexpr Keywords — Andreas Fertig (2025)](https://www.youtube.com/watch?v=hLakx0KYiR0)

## Phase 5: Data Structures, Allocators & Threads
*Focus: CPU cache friendly structures, dynamic allocation elimination, and basic synchronization.*
- [ ] [Almost Always Vector — Kevin Carpenter (2024)](https://www.youtube.com/watch?v=VRGRTvfOxb4)
- [ ] [Custom Allocators Explained — Kevin Carpenter (2025)](https://www.youtube.com/watch?v=RpD-0oqGEzE)
- [ ] [Concurrency — Arthur O'Dwyer (2020)](https://www.youtube.com/watch?v=F6Ipn7gCOsY)

## Phase 6: Hardware Sympathy & CPU Caches
*Focus: Cache lines, false sharing, struct layout (SoA vs AoS), and memory fetching.*
- [ ] [Data-Oriented Design and C++ — Mike Acton (2014)](https://www.youtube.com/watch?v=rX0ItVEVjHc)

## Phase 7: The Memory Model & Lock-Free Atomics
*Focus: Lock-free programming, memory ordering, and kernel-less inter-thread communication.*
- [ ] [C++ Atomics, From Basic to Advanced — Fedor Pikus (2017)](https://www.youtube.com/watch?v=ZQFzMfHIxng)
- [ ] [Single Producer Single Consumer Lock-free FIFO — Charles Frasch (2023)](https://www.youtube.com/watch?v=K3P_Lmq6pw0)

## Phase 8: Static Polymorphism & Zero-Cost Abstractions
*Focus: Curiously Recurring Template Pattern (CRTP), mixins, and compile-time interfaces.*
- [ ] [Expressing Implementation Sameness and Similarity — Daisy Hollman (2023)](https://www.youtube.com/watch?v=Fhw43xofyfo)

## Phase 9: OS Architecture & Trading Systems
*Focus: Trading system architecture and multi-core concurrency limits.*
- [ ] [When Nanoseconds Matter: Ultrafast Trading Systems in C++ — David Gross (2024)](https://www.youtube.com/watch?v=sX2nF1fW7kI)
- [ ] Scalable and Low Latency Lock-free Data Structures in C++ — Alexander Krizhanovsky (2022)

## Phase 10: OS-Level Networking & epoll
*Focus: Socket programming, Linux asynchronous I/O, file descriptor concurrency, and readiness models.*
- [ ] [What I Learned From Sockets: Applying the Unix Readiness Model — Filipp Gelman (2022)](https://www.youtube.com/watch?v=YmjZ_052pyY)
- [ ] The Linux socket API explained — Chris Kanich (2020)

## Phase 11: Hardware Reality, TLB, & Kernel Bypass
*Focus: Solarflare/OpenOnload, eliminating page faults, TLB misses, and overriding OS limitations.*
- [ ] When a Microsecond Is an Eternity: High Performance Trading Systems in C++ — Carl Cook (2017)
- [ ] Low-Latency Programming and High-Frequency Trading — Paul Bilokon (2025)

## Phase 12: Modern Zero-Copy Idioms
*Focus: Managing character sequences and parsing data off the wire without allocations.*
- [ ] Back To Basics: C++ Strings and Character Sequences — Nicolai Josuttis (2025)

## Phase 13: Profiling, Diagnostics & Telemetry
*Focus: Hardware performance counters, identifying TLB/cache misses, and mastering Linux diagnostic tools.*
- [ ] [A C++ developer's guide to performance analysis tools — Milian Wolff (2019)](https://www.youtube.com/watch?v=6bXj_qF0O1A)
- [ ] [Tuning C++: Benchmarks, and Profiling, and Microarchitectures, Oh My! — Chandler Carruth (2015)](https://www.youtube.com/watch?v=nXaxk27zwlk)