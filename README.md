# cs2881-hw0
HW0 for Harvard's CS2881 AI Safety course

## Hypothesis

My hypothesis is that an unablated J-space is mandatory for reasoning above a certain level of difficulty; whatever level of difficulty this is depends on the model (we will test on Qwen3-4b). Anthropic claims that using explicit chain of thought (CoT) reduces dependence on the J-space, shown by experiments where models using explicit CoT retain performance above models without explicit CoT, even under increasing levels of ablation.

But beyond a certain level of reasoning (harder math problems), can explicit CoT compensate for ablations to the J-space? I don't think so. So for sufficiently advanced reasoning problems, I'd expect that ablations to the J-space will cause similar performance declines on models using explicit CoT and models not using explicit CoT. My guess is that this is somewhere around MATH500 and AIME level problems.

A positive result here (where ablations to J-space cause uniform performance declines independent of explicit CoT) suggest that without the J-space, explicit CoT is a necessary but not sufficient conidition for advanced reasoning.
