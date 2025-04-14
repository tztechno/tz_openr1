# tz_openr1

---

```

[config for grpo]

# GRPO trainer config
bf16: true
use_vllm: false
do_eval: false
gradient_accumulation_steps: 2
gradient_checkpointing: true
gradient_checkpointing_kwargs:
  use_reentrant: false
hub_model_id: Qwen2-0.5B-math-grpo
hub_strategy: every_save
learning_rate: 2.0e-05
log_completions: true
log_level: info
logging_first_step: true
logging_steps: 1
logging_strategy: steps
lr_scheduler_type: cosine
max_prompt_length: 256
max_completion_length: 512
max_steps: -1
num_generations: 4
num_train_epochs: 1

[drgrpo only]
scale_rewards: false

[cppo only]
metric: smallest
pruning: 0.5 
allocation: true

```

---

https://www.kaggle.com/code/stpeteishii/openr1-qwen2-0-5b-math-drgrpo2-0414 (drgrpo)

https://www.kaggle.com/code/stpeteishii/openr1-qwen2-0-5b-math-drgrpo-0414 (drgrpo)

https://www.kaggle.com/code/stpeteishii/openr1-qwen2-0-5b-math-cppo-0414 (cppo)

https://www.kaggle.com/code/stpeteishii/openr1-qwen2-0-5b-math-grpo-0414 (grpo)

https://www.kaggle.com/code/stpeteishii/openr1-qwen2-0-5b-math-sft-0413

---

https://github.com/huggingface/open-r1

https://github.com/lzhxmu/CPPO

---


**CPPO: Accelerating the Training of Group Relative Policy Optimization-Based Reasoning Models** (cppo)

https://arxiv.org/abs/2503.22342

**Understanding R1-Zero-Like Training: A Critical Perspective** (drgrpo)

https://arxiv.org/abs/2503.20783


---
