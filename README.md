# DenseMTL
## Dense Multitask Learning to Reconfigure Comics (CVPRW 2023) Oral
Deblina Bhattacharjee, Sabine Süsstrunk, and Mathieu Salzmann

## Abstract:
In this paper, we develop a MultiTask Learning (MTL) model to achieve dense predictions for comics panels to, in turn, facilitate the transfer of comics from one publication channel to another by assisting authors in the task of reconfiguring their narratives. Our MTL method can successfully identify the semantic units as well as the embedded notion of 3D in comics panels. This is a significantly challenging problem because comics comprise disparate artistic styles, illustrations, layouts, and object scales that depend on the author's creative process. Typically, dense image-based prediction techniques require a large corpus of data. Finding an automated solution for dense prediction in the comics domain, therefore, becomes more difficult with the lack of ground-truth dense annotations for the comics images. To address these challenges, we develop the following solutions- we leverage a commonly-used strategy known as unsupervised image-to-image translation, which allows us to utilize a large corpus of real-world annotations; - we utilize the results of the translations to develop our multitasking approach that is based on a vision transformer backbone and a domain transferable attention module; -we study the feasibility of integrating our MTL dense-prediction method with an existing retargeting method, thereby reconfiguring comics.

## Published in: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)

``` @INPROCEEDINGS{10208491,
  author={Bhattacharjee, Deblina and Süsstrunk, Sabine and Salzmann, Mathieu},
  booktitle={2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW)}, 
  title={Dense Multitask Learning to Reconfigure Comics}, 
  year={2023},
  volume={},
  number={},
  pages={5646-5655},
  keywords={Three-dimensional displays;Annotations;Semantics;Layout;Predictive models;Transformers;Prediction algorithms},
  doi={10.1109/CVPRW59228.2023.00598}}
```
