# nexigen-csharp 🔷

An idiomatic, high-performance **.NET 9+** implementation within the **nexigen** ecosystem. Engineered specifically for simulator control logic and applications requiring extreme throughput without runtime overhead.

## 🚀 Key Architectural Features
* **Zero-Allocation Design:** Heavily utilizes `Span<T>`, `Memory<T>`, and `ValueTask` to minimize or completely bypass heap allocations, eliminating Garbage Collector (GC) spikes.
* **Lock-Free Concurrency:** Implements asynchronous data pipelines using `System.Threading.Channels` for fast, non-blocking queue operations.
* **Modern .NET Ecosystem:** Full support for Native AOT (Ahead-Of-Time) compilation, modern Task Parallel Library (TPL), and standard Dependency Injection.

## 🛠️ Core Components
* High-speed asynchronous Logger optimized for zero string allocations.
* Thread-safe Metrics provider for near real-time telemetry.
* Application hosting abstractions and domain event buses.

## 📄 License
Distributed under the **MIT License**. Created by Vasily Kovrigin.
