# ContactExplorer reproduction notes

Independent reading and experimental notes for the [ContactExplorer paper](https://arxiv.org/abs/2603.10971) and [official implementation](https://github.com/ruoyiqiao/ContactExplorer). The algorithm and main code are the original authors' work. This repository publishes my evaluation summaries; it does not repackage the upstream implementation.

## Scope

I studied the contact coverage counter, energy-based reaching reward, and PPO training path, then reproduced the LEAP-hand CubeInBox task in Isaac Gym. I ran training and independent fixed-policy evaluation, comparing ContactExplorer with a PPO baseline without the two exploration rewards. I also investigated contact coverage and friction perturbations.

For one training seed, the ContactExplorer checkpoint at 1,250 updates achieved 373/384 (97.14%) and 359/384 (93.49%) successes on two nominal evaluation seeds. At 2,000 updates it achieved 333/384 (86.72%) and 312/384 (81.25%); the baseline at 2,000 updates achieved 0/384 on both. See [evaluation details](results/fixed-policy-evaluation.md) and [follow-up evaluation](results/follow-up-evaluation.md).

Evaluation seeds test fixed checkpoints and are not independent training seeds. This is a single-task, single-training-seed study, not a reproduction of the paper's full multi-task, multi-seed, or real-robot results.

## Provenance

The local experiment used upstream commit `0cc4988f44e6d2f1921009593dd2c3559578ffdc`. Run the original project for the implementation. The result files here are summaries of my local experiments; checkpoints and large logs are retained locally.
