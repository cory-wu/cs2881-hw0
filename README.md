# cs2881-hw0
HW0 for Harvard's CS2881 AI Safety course

## Hypothesis

My hypothesis is that the J-space is mandatory for reasoning above a certain level of difficulty; where that is is probably somewhere between MATH 500 and AIME I. W/o the J-space, explicit CoT is a necessary but not sufficient condition for advanced reasoning.

Some experiments I have in mind:
Benchmark and evaluate GSM8 performance on Qwen3-4b with the J-space, Qwen3-4b with the J-space ablated but explicit CoT, and then Qwen3-4b with the J-space ablated and no explicit CoT. I expect decreasing performance, respectively.

We can do the same with MATH500. I'd expect the performance gap between Qwen3-4b with the J-space ablated but with explicit CoT and Qwen3-4b with the J-space ablated and no explicit CoT to shrink, since the required amount of reasoning for these problems will be more than GSM8. (Here, explicit CoT can only get you so far).

Something similar will happen as we step it up to AIME I and AIME II.
