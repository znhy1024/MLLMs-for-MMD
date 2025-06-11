# MLLMs-for-MMD
This is the repository of [Multimodal Misinformation Detection by Learning from Synthetic Data with Multimodal LLMs](https://arxiv.org/abs/2409.19656). 

## Method
For feature extraction, we use the same Mixed-modal Encoder as [RA-CM3](https://proceedings.mlr.press/v202/yasunaga23a.html). For semantic similarity-based selection, we use the cosine similarity as the measure using NumPy. For distributional similarity-based selection, we use the calibrated wasserstein gradient as the measure using the repository of [geomloss module](https://github.com/jeanfeydy/geomloss).

## Fine-Tune
We directly use the offical repository of [LLaVA-NeXT](https://github.com/haotian-liu/LLaVA) and [mPLUG-Owl2](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2). Plese refer to these repos for instructions.

## Datasets
See *data* directory.

## Citation

```
@misc{zeng2024multimodalmisinformationdetectionlearning,
      title={Multimodal Misinformation Detection by Learning from Synthetic Data with Multimodal LLMs}, 
      author={Fengzhu Zeng and Wenqian Li and Wei Gao and Yan Pang},
      year={2024},
      eprint={2409.19656},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2409.19656}, 
}
```
