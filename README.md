# Penghe Li / 李鹏赫

PhD candidate in Artificial Intelligence at Harbin Institute of Technology (HIT), advised by Prof. Jianbin Qiu (邱剑彬).

I work on efficient inference for large language and vision-language models, with a focus on edge VLMs, mixed-precision quantization, and visual KV-cache.

## Research interests

- Edge vision-language models (VLMs)
- Mixed-precision quantization
- Visual KV-cache
- Model-system co-design for inference

## Open-source contributions (PRs pending review)

Correctness fixes submitted to upstream projects. As of 2026-11-26, none of these pull requests have been merged. Please treat them as pending review, not as upstream-adopted work.

**Primary**

- [FlashInfer #9309](https://github.com/flashinfer-ai/flashinfer/pull/9309) — Align FA2 JIT dispatch with instantiated query tiles to avoid dynamic linking failures; adds compile, link, and load regression tests. Status: open, rebased onto current main; a targeted CI request has been posted, still awaiting maintainer authorization and review.
- [Triton #12510](https://github.com/triton-lang/triton/pull/12510) — Make MXFP4 nearest-even rounding elementwise, so one element's rounding is not affected by unrelated values; adds midpoint and neighbor regressions. Status: open, awaiting review.

**Other open PRs**

- [Triton #12598](https://github.com/triton-lang/triton/pull/12598) — Preserve closure bindings when the interpreter rewrites kernels.
- [SGLang #44162](https://github.com/sgl-project/sglang/pull/44162) — Compensate cumulative request-arrival-time drift in the serving benchmark.

## Technical stack

Python · C/C++ · CUDA · PyTorch · Triton · Linux · Git

## Contact

GitHub: [@Lipenghee](https://github.com/Lipenghee)
