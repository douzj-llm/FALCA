# FALCA

**FALCA: Falsification-Aware Reinforcement Learning with Hierarchical Credit Assignment for Long-Horizon Deep Search Agents**

Zijun Dou\*, Kun Luo\*, Chaofan Li, Shuqi Lu, Zheng Liu†

\* Equal contribution · † Corresponding author

[Project Page](https://douzj-llm.github.io/FALCA/) · [Paper](https://douzj-llm.github.io/FALCA/static/pdf/falca_paper.pdf)

FALCA formulates long-horizon deep search as a propose–falsify process: a Searcher proposes candidate answers, independent Falsifiers seek counterevidence and return structured falsification reports, and the Searcher revises its research state. Training combines SFT warmup on falsification trajectories with agentic RL using hierarchical credit assignment over trajectories, research segments, and turns.

Code and model will be released here.

## Citation

```bibtex
@article{dou2026falca,
  title   = {FALCA: Falsification-Aware Reinforcement Learning with
             Hierarchical Credit Assignment for Long-Horizon Deep Search Agents},
  author  = {Dou, Zijun and Luo, Kun and Li, Chaofan and
             Lu, Shuqi and Liu, Zheng},
  journal = {arXiv preprint},
  year    = {2026}
}
```
