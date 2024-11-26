---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---
<h1><p style="text-align: center;">Kevin Flanagan, <a href="https://dimadamen.github.io">Dima Damen</a>, <a href="https://mwray.github.io/">Michael Wray</a></p></h1>
<p style="text-align: center;">University of Bristol</p>
![](assets/images/intro_fig_bmvc2.png)
<i>Left: We generate training examples from videos with rough timestamps of narrations by artificially merging clips to provide a contrastive signal. Right: At test time, CliMer
can perform temporal grounding in long, dense videos.</i>
## Abstract

Video Moment Retrieval is a common task to evaluate the performance of visual-language models—it involves localising start and end times of moments in videos from query sentences. The current task formulation assumes that the queried moment is present in the video, resulting in false positive moment predictions when irrelevant query sentences are provided. In this paper we propose the task of Negative-Aware Video Moment Retrieval (NA-VMR), which considers both moment retrieval accuracy and negative query rejection accuracy. We make the distinction between In-Domain and Out-of-Domain negative queries and provide new evaluation benchmarks for two popular video
moment retrieval datasets: QVHighlights and Charades-STA. We analyse the ability of current SOTA video moment retrieval approaches to adapt to Negative-Aware Video Moment Retrieval and propose UniVTG-NA, an adaptation of UniVTG designed to tackle NA-VMR. UniVTG-NA achieves high negative rejection accuracy (avg. 98.4%) scores while retaining moment retrieval scores to within 3.87% Recall@1 0.5 IoU.

## Video
<iframe width="800" height="460" src="https://www.youtube.com/embed/082nRrTHCnQ?si=mjB0r2o6rUhdbsMt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
## Paper

[ArXiv](https://arxiv.org/abs/2310.17395)

## Poster



## Code, Data Splits and Features

The code, dataset splits and links for features can be found [here](https://github.com/keflanagan/CliMer)

## Bibtex

```
@InProceedings{flanagan2023climer,
    author    ={Flanagan, Kevin and Damen, Dima and Wray, Michael},
    title     ={Learning Temporal Sentence Grounding From Narrated EgoVideos},
    booktitle ={British Machine Vision Conference (BMVC)},
    year      ={2023}
}
```

## Acknowledgements

K Flanagan is supported by UKRI (Grant ref EP/S022937/1) CDT in
Interactive AI & Qinetiq Ltd via studentship CON11954. D Damen is supported by EPSRC
Fellowship UMPIRE (EP/T004991/1) & EPSRC Program Grant Visual AI (EP/T028572/1)
