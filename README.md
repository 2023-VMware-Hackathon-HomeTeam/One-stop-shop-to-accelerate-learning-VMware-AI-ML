# One-Stop Shop to Accelerate Learning of VMware and AI/ML

| Welcome[^1] |
|---|
| <video src="https://user-images.githubusercontent.com/8474263/261398731-e645200c-cc57-40b8-b1c9-ccc76bb0d8fe.mp4" type="video/mp4"> </video> |

## Introduction
This document is our product for the 2023 VMware Explore Hackathon. We wanted to create a resource that can help a Virtual Infrastructure Admin understand the current landscape of AI/ML and how they can learn more about it, while also including how to learn these technologies from the comfort of your home. We also want to explore how much you can use your homelab to help you learn VMware technology in this field, and if we can make it easier for you, we will!

The Home Team - One stop shop to accelerate your learning of VMware and AI/ML:  
- Learn new technologies in the AI/ML space with your homelab.
- Automate a test environment and research CPU/GPU/etc capabilities.

## What's the relationship between VMware and AI/ML?

In time, you will likely see both AI and ML workloads in your datacenters. In addition, we will likely see the emergence of a datacenter administration skillset that is specific to managing AI/ML workloads. vSphere is the enterprise datacenter virtualization platform of choice in most organizations and will also provide the additional management overlay needed to utilize and optimize AI/ML workloads.

### What do businesses ask AI/ML systems to do?

Two common requests emerge: 

1. **Speed** - Improve their products faster
2. **New Revenue** - Learn what their customers will want

### Why?

1. **Speed** - Improve organizations products faster

   Organizations are looking for ways to improve their current business

   > Outcome desired is to realize revenue faster on current offerings

   Examples of how companies use AI/ML in this area:

   - Identify operational improvements
   - Identify product improvements
	
2. **New Revenue** - Learn what their customers will want

   Organizations want to find net new revenue by identifying new ways/methods/products to sell

   > Outcome desired is to find net new revenue on net new offerings to build(invest)

   Examples of how companies want to use AI/ML in this area:

   - Predict what their customers will want
   - Look for patterns in customer behavior
	
### Why you, the vSphere administrator, and why your datacenter?

These efforts have to be done on company proprietary data. At most organizations, the most sensitive information is placed only in company controlled datacenters, and the AI/ML systems required to extract the outlined outcomes must be run in those same datacenters managed by company administrators.

### What does that mean to you?

You're getting new workloads, and you need to understand their workload profiles, as AI and ML workloads have heavy datacenter demands. You must learn to manage these workloads just like you learned about managing databases on vSphere. 
The toolsets you use to manage your workloads could introduce features that consume AI and ML that you will need to understand, for example, to drive the automation of workload management.

### So what do I need to know?

AI and ML are two different workloads.
ML systems are only one part of an overall AI platform.

## What is AI/ML?

_Artificial Intelligence (AI)_ refers to intelligent systems that can perform human-like tasks. Tasks such as problem-solving, decision-making, and understanding language. AI uses algorithms and processes data to do this. These systems can be narrow or general in scope. Narrow AI focuses on specific tasks, like image recognition or natural language processing. General AI aims to replicate human-like intelligence across a range of activities.

_Machine Learning (ML)_ is a subset of AI. ML empowers computers to learn and improve through experience instead of explicit programming. These systems use large datasets to train models and identify patterns and relationships. This enables the system to make decisions or predictions without human help.

There are different types of ML, each catering to specific tasks and goals:

- Supervised learning
- Unsupervised learning
- Reinforcement learning

_Supervised learning_ involves training the system with labeled data. _Unsupervised learning_ deals with unlabeled data to find patterns and groupings. _Reinforcement learning_ focuses on training the system through trial and error. Rewarding successful actions and penalizing unsuccessful ones.

For VI Admins, AI and ML open up many possibilities, such as:

- Optimizing complex processes
- Automating routine tasks
- Improving data analytics

## Where and how can you learn it?

- Learn how [_VMware_ empowers AI/ML](https://www.vmware.com/products/vsphere/ai-ml.html), including a link to **free** _NVIDIA_-powered hands-on labs.
- There are several free and paid AI courses on [Coursera](https://www.coursera.org/). At the moment, the most highly rated course is _[AI for Everyone](https://www.coursera.org/learn/ai-for-everyone)_.
- _Helsinki University_ offers a free _[Elements of AI](https://www.elementsofai.com/)_ online course.
- News, courses, videos, toolkits and more are available from _[Learn with Google AI](https://ai.google/build/machine-learning/)_.
- _edX_ offers free and paid courses in [Artificial Intelligence](https://www.edx.org/learn/artificial-intelligence) and [Machine Learning](https://www.edx.org/learn/machine-learning).
- _Microsoft_ offers free courses in [Azure AI Services & Azure Machine Learning](https://learn.microsoft.com/en-us/training/browse/?expanded=azure&products=ai-services%2Cazure-machine-learning).
- Purchase a book from a person involved in this field. [How AI Works](https://nostarch.com/how-ai-works) is meant to be a general introduction to AI, ML and LLMs without complicated math, but still giving you valuable context.  

## What does your lab need to run AI/ML and Large Language Models (LLMs)?

### GPU

Although some AI/ML workloads are capable of running without a GPU, having a GPU can significantly improve performance. AI/ML workloads can take advantage of common commodity GPUs from the likes of _AMD_ and _NVIDIA_. At present _NVIDIA_ GPUs are the most commonly used and supported. The more GPU VRAM your video card has, the more performant and capable AI/ML can be. Ideally, your GPU should have at least 8 GB of VRAM.

#### NVIDIA

Probably the best resource for everything NVIDIA plus vSphere is the _[VMware vSphere Deployment Guide](https://docs.nvidia.com/ai-enterprise/deployment-guide-vmware/0.1.0/index.html)_ from the _NVIDIA Docs Hub_.

### CPU, RAM, Storage

While AI/ML can run on a variety of hardware platforms, including single board computers (SBCs) like _Raspberry Pis_, you get more flexibility from an x86-64bit processor. Whether _Intel_ or _AMD_, your CPU should have at least 4 cores. An x86-64bit processor also provides access to PCI-Express lanes that allow your system to have one or more GPUs.

When it comes to system RAM, try to have double the amount of GPU VRAM. For example, if your GPU has 8 GB VRAM, you should have at least 16 GB system RAM.

Depending on how many LLMs, other models, or data sets you want to download or train, AI/ML can consume anywhere from hundreds of megabytes to petabytes or more. For a lab environment, having at least several hundred gigabytes should allow you to store and use a number of pre-trained LLMs. For AI/ML, the more storage you can provide, the better. Like most workloads, AI/ML benefits from faster storage like NVMe-based solid state drives.

## Homelab Quickstart Guide

If you are interested in working with _[TensorFlow](https://www.tensorflow.org/)_, [William Lam](https://github.com/lamw) has managed to connect a [Coral USB TPU Accelerator to ESXi](https://williamlam.com/2023/05/google-coral-usb-edge-tpu-accelerator-on-esxi.html).

### Generative AI

If you want to quickly get some generative AI tools installed in your homelab, [Wesley "TechNobo" Pyburn](https://github.com/TCNOco) has created some helpful PowerShell scripts. These scripts install common open-source AI/ML tools, automatically downloading and installing required components and dependencies.

Let's look at two of those scripts, which install tools similar to _ChatGPT_ and _MidJourney_.

- **Vicuna**
  - An open-source chatbot based on [LLaMa](https://en.wikipedia.org/wiki/LLaMA), which claims to achieve 90% quality of _ChatGPT GPT-4_
  - Can take advantage of _NVIDIA_ GPU and _AMD_ GPU (MacOS & Linux only), or can run CPU-only
  - Requires 20 GB or more of storage if all models are downloaded
  - To install on _Windows 10/11_, run the following command from an elevated (administrator) PowerShell prompt:
    ```powershell
    iex (irm vicuna.tc.ht)
    ```
- **AUTOMATIC1111**
  - A web UI for _[Stable Diffusion](https://en.wikipedia.org/wiki/Stable_Diffusion)_, which allows you to generate images from text prompts
  - Requires a GPU. A GPU with 8GB VRAM or more is strongly recommended. It supports GPUs with 4GB of VRAM, and there are reports that some GPUs with 2GB of VRAM can work
  - Requires 10 GB or more of storage
  - To install on _Windows 10/11_, run the following command from an elevated (administrator) PowerShell prompt:
    ```
    iex (irm auto11.tc.ht)
    ```

## Diving Deeper - Where to go from here?

Here are some resources if you'd like to get a deeper understanding of AI/ML:

- [Frank Denneman](https://twitter.com/frankdenneman) has a series of articles covering [machine learning with vSphere](https://frankdenneman.nl/category/machine-learning/). His article _[Basic Terminologies Large Language Models](https://frankdenneman.nl/2023/08/18/basic-terminologies-large-language-models/)_ is a good starting point
- _TensorFlow_ provides a [resource library with curated curriculms](https://www.tensorflow.org/resources/learn-ml) for machine learning.
- Join an AI/ML challenge on _[Kaggle](https://www.kaggle.com/)_. New challengers can get started with the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/overview) challenge
- Check with your local colleges and universities to see if they offer AI/ML disciplines within their computer science program

[^1]: Image generated via _[Stable Diffusion](https://github.com/Stability-AI/stablediffusion)_. Audio generated via _[ElevenLabs](https://elevenlabs.io/)_. Video generated via _[SadTalker](https://github.com/OpenTalker/SadTalker)_
