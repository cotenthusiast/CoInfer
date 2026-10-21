# CoInfer

**An experimental machine learning inference engine built from first principles.**

CoInfer explores the systems and algorithms responsible for executing machine learning models efficiently.

The project focuses on understanding inference beyond high-level framework APIs, including model execution, memory management, batching, decoding, and performance optimisation.

Initially, development will focus on autoregressive transformer inference, with room to explore other architectures and inference workloads.

## Areas of exploration

- **Model execution:** Forward passes, execution pipelines, and numerical computation.
- **Autoregressive inference:** Token generation, sampling, and decoding strategies.
- **Memory management:** KV caching, tensor storage, and memory efficiency.
- **Batching and scheduling:** Efficient execution of multiple inference requests.
- **Performance:** Profiling, benchmarking, and computational optimisation.

## Development

CoInfer is in its early stages of development.

The initial goal is to implement a minimal working inference pipeline and progressively investigate the techniques used by modern inference systems.

The project is experimental and does not aim to replace production inference frameworks.

## Related projects

- [CoTorch](https://github.com/cotenthusiast/CoTorch): An experimental machine learning framework built from first principles.
- [CoHarness](https://github.com/cotenthusiast/CoHarness): An experimental AI coding-agent harness exploring model integration, tool calling, context management, and autonomous execution.

## License

MIT License.
