# Concurrency

Learn concurrency by watching interleavings happen, breaking synchronization, and writing real concurrent programs - not by memorizing definitions.

## Resources

| Resource | Description |
|---|---|
| [The Deadlock Empire](https://deadlockempire.github.io/) | A concurrency puzzle game where you exploit thread interleavings to break programs. Excellent for developing intuition for race conditions, locks, deadlocks, and synchronization bugs. |
| [A Tour of Go - Concurrency](https://go.dev/tour/concurrency/1) | Interactive browser exercises for goroutines, channels, buffered channels, `select`, mutexes, and concurrent design. |
| [PortSwigger - Race Conditions](https://portswigger.net/web-security/race-conditions) | Free interactive labs built around realistic race conditions in web applications, including limit-overrun and multi-endpoint races. |

## Core concepts to understand

- concurrency vs. parallelism
- processes vs. threads
- shared state and race conditions
- atomic operations
- mutexes, read/write locks, semaphores, and condition variables
- deadlock, livelock, and starvation
- memory visibility and ordering
- producer/consumer patterns
- thread pools and task-based concurrency
- channels and message passing
- lock-free concepts and compare-and-swap
- cancellation, timeouts, and structured concurrency

## Mental model

When debugging concurrent code, ask:

1. **What state is shared?**
2. **Which operations must appear atomic?**
3. **What interleavings are possible?**
4. **What ordering guarantees actually exist?**
5. **Can one participant wait forever?**

[← Back to main README](../README.md)
