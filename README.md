# DH-FaceVid-1K
Generating talking face videos from various conditions has recently become a highly popular research area within generative tasks. However, building a high-quality face video generation model requires a well-performing pre-trained backbone, a key obstacle that universal models fail to adequately address. Most existing works rely on universal video or image generation models and optimize control mechanisms, but they neglect the evident upper bound in video quality due to the limited capabilities of the backbones, which is a result of the lack of high-quality human face video datasets. In this work, we investigate the unsatisfactory from related studies and collect and annotate a large-scale dataset, resulting in a comprehensive, high-quality digital human facial dataset named DH-FaceVid-1K. Using this dataset, we develop several effective pre-trained backbone models for face video generation, supporting tasks like text-to-video and image-to-video generation. We establish performance benchmarks and compare them with models trained on public related datasets to demonstrate the superiority of our dataset. These experiments enable us to explore empirical strategies for designing domain-specific video generation tasks in a cost-effective manner. We plan to make our curated dataset and pre-trained human face video generation models publicly available as a resource contribution, with the aim of advancing face-centric downstream tasks.


If you find FaceVid-1K useful for your work please cite:
```
@inproceedings{Di2024FaceVid1KAL,
      title={FaceVid-1K: A Large-Scale High-Quality Multiracial Human Face Video Dataset},
      author={Donglin Di and He Feng and Wenzhang Sun and Yongjia Ma and Hao Li and Wei Chen and Xiaofei Gou and Tonghua Su and Xun Yang},
      year={2024},
      url={https://api.semanticscholar.org/CorpusID:273233717}
}
```

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
