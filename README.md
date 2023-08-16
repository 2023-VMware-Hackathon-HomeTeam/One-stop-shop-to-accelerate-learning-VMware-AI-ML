# One-Stop Shop to Accelerate Learning of VMware and AI/ML

https://github.com/2023-VMware-Hackathon-HomeTeam/One-stop-shop-to-accelerate-learning-VMware-AI-ML/assets/8474263/139a000e-77e9-4ae5-9abc-994fe1d9c586

[^1]

## Introduction
This document is our product for the 2023 VMware Explore Hackathon. We wanted to create a resource that can help a Virtual Infrastructure Admin understand the current landscape of AI/ML and how they can learn more about it, while also including how to learn these technologies from the comfort of your home. We also want to explore how much you can use your homelab to help you learn VMware technology in this field, and if we can make it easier for you, we will!

The Home Team - One stop shop to accelerate your learning of VMware and AI/ML:  
- Learn new technologies in the AI/ML space with your homelab.
- Automate a test environment and research CPU/GPU/etc capabilities.

## What is AI/ML

_Artificial Intelligence (AI)_ refers to intelligent systems that can perform human-like tasks. Tasks such as problem-solving, decision-making, and understanding language. AI uses algorithms and processes data to do this. These systems can be narrow or general in scope. Narrow AI focuses on specific tasks, like image recognition or natural language processing. General AI aims to replicate human-like intelligence across a range of activities.

_Machine Learning (ML)_ is a subset of AI. ML empowers computers to learn and improve through experience instead of explicit programming. These systems use large datasets to train models, and identify patterns and relationships. This enables the system to make decisions or predictions without human help.

There are different types of ML, each catering to specific tasks and goals:

- supervised learning,
- unsupervised learning, and
- reinforcement learning.

_Supervised learning_ involves training the system with labeled data. _Unsupervised learning_ deals with unlabeled data to find patterns and groupings. _Reinforcement learning_ focuses on training the system through trial and error. Rewarding successful actions and penalizing unsuccessful ones.

For VI Admins, AI and ML open up many possibilities, such as:

- Optimizing complex processes,
- Automating routine tasks, and
- Improving data analytics.

## Where and how can you learn it?

### Free

- Learn how [_VMware_ empowers AI/ML](https://www.vmware.com/products/vsphere/ai-ml.html), including a link to **free** _NVIDIA_-powered hands-on labs.
- There are a number of free (and paid) AI courses on [Coursera](https://www.coursera.org/). At the moment the most highly rated course is _[AI for Everyone](https://www.coursera.org/learn/ai-for-everyone)_.
- _Helsinki University_ offers a free _[Elements of AI](https://www.elementsofai.com/)_ online course.
- News, courses, videos, toolkits and more are available from _[Learn with Google AI](https://ai.google/build/machine-learning/)_.
- _edX_ offers free (and paid) courses in [Artificial Intelligence](https://www.edx.org/learn/artificial-intelligence) and [Machine Learning](https://www.edx.org/learn/machine-learning).
- _Microsoft_ offers free courses in [Azure AI Services & Azure Machine Learning](https://learn.microsoft.com/en-us/training/browse/?expanded=azure&products=ai-services%2Cazure-machine-learning).

### Paid

## What would you need to run AI/ML or even Large Language Models in your homelab, test lab at work, etc?

### GPU

Although some AI/ML workloads are capable of running without a GPU, having a GPU can significantly improve performance. AI/ML workloads can take advantage of common commodity GPUs from the likes of _AMD_ and _NVIDIA_. At present _NVIDIA_ GPUs are the most commonly used and supported.

#### NVIDIA

Probably the best resource for everything NVIDIA plus vSphere is the _[VMware vSphere Deployment Guide](https://docs.nvidia.com/ai-enterprise/deployment-guide-vmware/0.1.0/index.html)_ from the _NVIDIA Docs Hub_.

### CPU, RAM, Storage


## Quickstart guide for a homelab (any caveats?) but still have fun

If you are interested in working with _[TensorFlow](https://www.tensorflow.org/)_, [William Lam](https://github.com/lamw) has managed to connect a [Coral USB TPU Accelerator to ESXi](https://williamlam.com/2023/05/google-coral-usb-edge-tpu-accelerator-on-esxi.html).

### Generative AI

If you want to quickly get some generative AI tools installed in your homelab, [Wesley "TechNobo" Pyburn](https://github.com/TCNOco) has created some helpful PowerShell scripts. These scripts install common open-source AI/ML tools, automatically downloading and installing required components and dependencies.

Let's look at two of those scripts, which install tools similiar to _ChatGPT_ and _MidJourney_.

- **Vicuna**
  - An open-source chatbot based on [LLaMa](https://en.wikipedia.org/wiki/LLaMA), which claims to achieve 90% quality of _ChatGPT GPT-4_.
  - Can take advantage of _NVIDIA_ GPU and _AMD_ GPU (MacOS & Linux only), or can run CPU-only.
  - Requires 20 GB or more of storage if all models are downloaded.
  - To install on _Windows 10/11_, run the following command from an elevated (administrator) PowerShell prompt:
    ```powershell
    iex (irm vicuna.tc.ht)
    ```
- **AUTOMATIC1111**
  - A web UI for _[Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion)_, which allows you to generate images from text prompts.
  - Requires a GPU. A GPU with 8GB VRAM or more is strongly recommended. Supports GPUs with 4GB of VRAM, and there are reports that some GPUs with 2GB of VRAM can work.
  - Requires 10 GB or more of storage.
  - To install on _Windows 10/11_, run the following command from an elevated (administrator) PowerShell prompt:
    ```
    iex (irm auto11.tc.ht)
    ```
  
[^1]: Image generated via _[Stable Diffusion](https://github.com/Stability-AI/stablediffusion)_. Audio generated via _[FreeTTS](https://freetts.com/)_. Video generated via _[SadTalker](https://github.com/OpenTalker/SadTalker)_.
