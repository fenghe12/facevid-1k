# DH-FaceVid-1K
Generating talking face videos from various conditions has
recently become a highly popular research area within gener-
ative tasks. However, building a high-quality face video gen-
eration model requires a well-performing pre-trained back-
bone, a key obstacle that universal models fail to adequately
address. Most existing works rely on universal video or im-
age generation models and optimize control mechanisms, but
they neglect the evident upper bound in video quality due to
the limited capabilities of the backbones, which is a result
of the lack of high-quality human face video datasets. In this
work, we investigate the unsatisfactory results from related
studies, gather and trim existing public talking face video
datasets, and additionally collect and annotate a large-scale
dataset, resulting in a comprehensive, high-quality multiracial
face collection named <b> FaceVid-1K</b> . Using this dataset, we
craft several effective pre-trained backbone models for face
video generation. Specifically, we conduct experiments with
several well-established video generation models, including
text-to-video, image-to-video, and unconditional video gen-
eration, under various settings. We obtain the correspond-
ing performance benchmarks and compared them with those
trained on public datasets to demonstrate the superiority of
our dataset. These experiments also allow us to investigate
empirical strategies for crafting domain-specific video gen-
eration tasks with cost-effective settings. We will make our
curated dataset, along with the pre-trained talking face video
generation models, publicly available as a resource contribu-
tion to hopefully advance the research field.

Part of FaceVid-1K Dataset will be available at https://huggingface.co/datasets/jjuik2014/FaceVid-1K-partial

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
