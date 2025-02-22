# [Scalable 3D Captioning with Pretrained Models](https://arxiv.org/abs//2306.07279)

[Tiange Luo*](https://tiangeluo.github.io/), [Chris Rockwell*](https://crockwell.github.io), [Honglak Lee†](https://web.eecs.umich.edu/~honglak/), [Justin Johnson†](https://web.eecs.umich.edu/~justincj) (*Equal contribution    †Equal Advising)

We provide our codes for captioning and finetuning text-to-3D models in [captioning_pipeline](https://github.com/crockwell/Cap3D/tree/main/captioning_pipeline) and [text-to-3D](https://github.com/crockwell/Cap3D/tree/main/text-to-3D). Detailed instruction and where to download our model checkpoints can be found in each directory.

Data download available at [Hugging Face](https://huggingface.co/datasets/tiange/Cap3D), including descriptive captions for 3D objects in [Objaverse](https://objaverse.allenai.org/) and [ABO](https://amazon-berkeley-objects.s3.amazonaws.com/index.html), along with Objaverse's point clouds, rendered images, and Shap-E latent codes.

## Overview
Cap3D provides detailed descriptions of 3D objects by leveraging pretrained models in captioning, alignment, and LLM to consolidate multi-view information.

<img src="teaser.png" alt="drawing">


## Citation
If you find our code or data useful, please consider citing:
```
@article{luo2023scalable,
      title={Scalable 3D Captioning with Pretrained Models},
      author={Luo, Tiange and Rockwell, Chris and Lee, Honglak and Johnson, Justin},
      journal={arXiv preprint arXiv:2306.07279},
      year={2023}
}
```

If you use our captions for Objaverse objects, please cite:
```
@inproceedings{deitke2023objaverse,
  title={Objaverse: A universe of annotated 3d objects},
  author={Deitke, Matt and Schwenk, Dustin and Salvador, Jordi and Weihs, Luca and Michel, Oscar and VanderBilt, Eli and Schmidt, Ludwig and Ehsani, Kiana and Kembhavi, Aniruddha and Farhadi, Ali},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={13142--13153},
  year={2023}
}
```

If you use our captions for ABO objects, please cite:
```
@inproceedings{collins2022abo,
  title={Abo: Dataset and benchmarks for real-world 3d object understanding},
  author={Collins, Jasmine and Goel, Shubham and Deng, Kenan and Luthra, Achleshwar and Xu, Leon and Gundogdu, Erhan and Zhang, Xi and Vicente, Tomas F Yago and Dideriksen, Thomas and Arora, Himanshu and others},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  pages={21126--21136},
  year={2022}
}
```

## Acknowledgments
This work is supported by two grants from LG AI Research and Grant #1453651 from NSF.
Thanks to <a href="https://www.linkedin.com/in/kaiyi-li-1b4a1114b/">Kaiyi Li</a> for his technical supports.
Thanks to <a href="https://mbanani.github.io/">Mohamed El Banani</a>, <a href="http://kdexd.xyz/">Karan Desai</a> and <a href="https://nileshkulkarni.github.io/">Ang Cao</a> for their many helpful suggestions. Thanks <a href="https://mattdeitke.com/">Matt Deitke</a> for helping with Objaverse-related questions. 

We also thank the below open-source projects:
- [PyTorch](https://www.github.com/pytorch/pytorch) 
- [Blender](https://github.com/blender/blender)
- [PyTorch3D](https://github.com/facebookresearch/pytorch3d)
- [BLIP2](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)
- [CLIP](https://github.com/openai/CLIP)
