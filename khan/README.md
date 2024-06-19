# MCS ANL Blog

## Preface

Computer Vision (CV), a subset of Artificial Intelligence (AI), enables computers to interpret visual data from images and videos by acquiring, processing, and analyzing digital images to extract meaningful information. Techniques such as image classification, instance segmentation, semantic segmentation, and object detection are widely used in CV. Deep learning algorithms such as convolutional neural networks (CNNs) are essential for tasks like tracking objects and recognizing actions. CV empowers AI models, like large language models (LLMs), to efficiently understand and identify objects and activities within visual data, thereby enhancing their ability to comprehend and generate insights from multimedia content.

The primary objective of this project is to leverage the notion of object recognition, a particular CV task, in conjunction with an LLM to aid users in discovering, downloading, and asking about relevant images or videos. Dense captioning, especially when enriched with sufficient temporal data gleaned from videos, significantly enhances descriptive capabilities.

## Further Research

While there are many areas to improve upon for LLMs, like regarding [efficiency](https://arxiv.org/abs/2406.02528) or architectures (transformers, RNNs, Mamba)

A generalized action representation somewhat like [Husky](https://arxiv.org/abs/2406.06469) could boost the LLM usefulness for this application.

Regarding LLM, popular architectures such as transformers, RNNs, and Mamba have drawbacks, including non-determinism and unreliable memory. To address these issues, a Generalized Action Representation (GAR) could be a possible research avenue.
Regarding the LLM, architectures such as the popular transformer approach as well as RNN and Mamba have a number of drawbacks. Floating point operations in parallel programming patterns is a one factor for why LLMs are not deterministic. Other weaknesses include conflicting information and unreliable parametric memory. While a RAG could reduce hallucinations, it does not solve them. To overcome these problems, a Generalized Action Representation (GAR) can be possible research with the idea current architectures are inherently not the right approach for specialized tasks (no more or less) in an LLM, regardless of the amount of data available. [Husky](https://arxiv.org/abs/2406.06469)

I often research using [Google Scholar](https://scholar.google.com) and [Papers With Code](https://paperswithcode.com).

## Weekly Goals

- Week 1: Summarize and propose project improvements, scope, and milestones.
- Week 2: Define the technologies that will be used to achieve the proposed milestones.

## June 3rd

- Attended orientation, gaining insights into culture, policies, and procedures.
- Located cubicles and office space for the MCS division.

## June 4th

- Completed 24 TMS trainings.
- Obtained badge.

## June 5th

- Researched and successfully prototyped with LLaVa and pre-trained open CLIP.
- Obtained proximity card.

## June 6th

- Wrote blog.
- Researched types of architectures and models avalable for temporal analysis.

## June 7th


**Proposed Approach:**

- Develop an algorithm for video/image captioning at the edge.
- Utilize it to send alerts (via API) based on classification (e.g., tornado warnings, flock of birds migration).
- Enable text and video/image search queries from sorted alerts.
- Implement Client LLM/RAG for analysis on images.
- Provide highlights of historical data from alerts with a recommendation system.


As a result, I propose the following:

    • Algorithm to compute on video (and/or image) captioning at the edge
    • Use this to send alerts (via API) from the edge via classification
        ◦ Warnings (tornado, flood, accidents)
        ◦ Information (flock of birds migrating, deer eating)
    • Text (and video/images converted to text) search query from sorted alerts
    • Client LLM/RAG for analysis on image(s)
        ◦ Luminous objects (sun, reflection on solar panel)
        ◦ Colors, number of cars and deformations on car
        ◦ Predict next flock of birds using historical data
        ◦ Why did they migrate (seasonal changes)
    • Highlights of historical data from alerts
        ◦ Cater to specific user intent with alerts recommendation system


## June 10th

- Meeting to discuss goals in video captioning and image analysis.

## June 11th

- Extended research on replacing `scenic` with `pllava`.

## June 12th

- Guided tour of the Aurora supercomputer and Rapid Prototyping Laboratory.
- Visited the library to better understand older references available for research.

## June 17th