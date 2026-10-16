# Understanding Distributed Systems & Tail Latency

Published on: October 15, 2026

When building backend services, looking at arithmetic averages can be misleading. If 99 requests take 10ms and 1 request takes 5,000ms, your average latency looks fine at 59ms, but your actual user experience for the tail percentile is broken.

## Why Averages Lie

Averages hide spikes caused by garbage collection pauses, lock contention, or network congestion...

![Sample Image](../assets/blog-media/sample.png)

## Conclusion

Always monitor p99 and p99.9 metrics.