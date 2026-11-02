# Habitual Hacking: pilot report

Research report for the Habitual Hacking pilot (Neurotech @ Berkeley, Fall 2026): does reward exploitation in an LLM become habitual with continued reinforcement?

Open `index.html` in a browser. It is a single self-contained page with the experiment setup, six figures, final-checkpoint results, limitations and next steps.

- **Run:** `pilot-kl01-s0-20261030-0815`, seed 0
- **Model:** Qwen2.5-3B-Instruct with LoRA, trained with REINFORCE
- **Headline:** no arm became habitual; all three stayed devaluation-sensitive (DI 0.84–0.89). The fixed and sparse arms are confounded with roughly 2x the reinforcement and KL drift of the varying arm.

Figures are drawn from the run's logged evaluations, training logs and per-sample CSVs.
