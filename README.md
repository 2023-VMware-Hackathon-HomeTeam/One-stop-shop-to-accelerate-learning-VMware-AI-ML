# One-Stop Shop to Accelerate Your Learning of VMware and AI/ML

| Welcome[^1] |
|---|
| <video src="https://user-images.githubusercontent.com/8474263/261398731-e645200c-cc57-40b8-b1c9-ccc76bb0d8fe.mp4" type="video/mp4">A futuristic looking AI generated human, shown in portrait, says, "Welcome to your one-stop shop for learning artificial intelligence and machine learning with VMware."</video>|

## Introduction
This document is our product for the **2023 VMware Explore Hackathon**. We wanted to create a resource that can help a Virtual Infrastructure Admin understand the current landscape of AI/ML and how they can learn more about it, while also including how to learn these technologies from the comfort of their home. We also want to explore how much you can use your homelab to help you learn VMware technology in this field, and if we can make it easier for you, we will!

**The Home Team** - One-stop shop to accelerate your learning of VMware and AI/ML:  
- Learn new technologies in the AI/ML space with your homelab.
- Automate a test environment and research CPU/GPU/etc. capabilities.

## What's the relationship between VMware and AI/ML?

In time, you will likely see both AI and ML workloads in your data centers. In addition, we will likely see the emergence of a data center administration skill set that is specific to managing AI/ML workloads. vSphere is the enterprise data center virtualization platform of choice in most organizations and will also provide the additional management overlay needed to utilize and optimize AI/ML workloads.

### What do businesses ask AI/ML systems to do?

Two common requests emerge: 
- Help them to improve their products faster.
- Learn what their customers will want in future products or features.

### Why?

Organizations are looking for ways to improve their current business. The outcome desired is to realize revenue faster on current offerings.
Examples of how companies use AI/ML in this area:
- Identify operational improvements.
- Identify product improvements.

Organizations want to find net new revenue by identifying new ways/methods/products to sell. The outcome desired is to find net new revenue on net new offerings to build (invest). 
Examples of how companies want to use AI/ML in this area:

- Predict what their customers will want to increase their satisfaction with future products.
- Look for patterns in customer behavior that could open up new market opportunities.
	
### Why you, the vSphere administrator, and why your data center?

These efforts have to be done on company proprietary data. At most organizations, the most sensitive information is placed only in company controlled data centers, and the AI/ML systems required to extract the outlined outcomes must be run in those same data centers managed by company administrators.

For VI Admins, AI and ML open up many possibilities, such as:

- Optimizing complex processes
- Automating routine tasks
- Improving data analytics

### What does that mean to you?

You're getting new workloads, and you need to understand their workload profiles, as AI and ML workloads have heavy data center demands. You must learn to manage these workloads just like you learned about managing databases on vSphere. 
The toolsets you use to manage your workloads could introduce features that consume AI and ML that you will need to understand, for example, to drive the automation of workload management.  

## Definitions: What is AI? What is ML? What is Deep Learning, Generative AI, and what are LLMs?

_Artificial Intelligence (AI)_ refers to intelligent systems that can perform human-like tasks. Tasks such as problem-solving, decision-making, and understanding language. AI uses algorithms and processes data to do this. These systems can be narrow or general in scope. Narrow AI focuses on specific tasks, like image recognition or natural language processing. General AI aims to replicate human-like intelligence across a range of activities.

_Machine Learning (ML)_ is a subset of AI. ML empowers computers to learn and improve through experience instead of explicit programming. These systems use large datasets to train models and identify patterns and relationships. This enables the system to make decisions or predictions without human help.

There are different types of ML, each catering to specific tasks and goals:

- Supervised learning
- Unsupervised learning
- Reinforcement learning

_Supervised learning_ involves training the system with labeled data. _Unsupervised learning_ deals with unlabeled data to find patterns and groupings. _Reinforcement learning_ focuses on training the system through trial and error. Rewarding successful actions and penalizing unsuccessful ones.

There are many areas of study within Artificial Intelligence. Taking some definitions from "How AI Works" by Ronald Kneusel:  

<p align="center" width="100%">
    <img src="https://github.com/2023-VMware-Hackathon-HomeTeam/One-stop-shop-to-accelerate-learning-VMware-AI-ML/assets/16085267/d0de1662-05b6-40d8-97f5-807d39476550" width="50%" alt="A line drawing showing the relationship between artificial intelligence, machine learning, and deep learning. 'Deep learning' is written inside of an oval, which itself is inside a second oval where 'machine learning' is written, which again is inside a third oval where 'artificial intelligence' is written." />
</p>

> Machine learning builds models from data. For us, a model is an abstract notion of something that accepts inputs and generates outputs where the inputs and outputs are related in some meaningful way. The primary goal of machine learning is to condition a model using known data so that the model produces meaningful output when given unknown data. 
>
>  _Deep learning_ uses large models of the kind previously too big to make useful. ... there’s no strict definition of deep learning other than involving neural networks with many layers.

> _Generative AI_ is an umbrella term for models that create novel output, either independently (randomly) or based on a prompt supplied by the user. Generative models do not produce labels but text, images, or even video. Under the hood, generative models are neural networks built from the same essential components.  
>
> (The book covers) three kinds of generative AI models: generative adversarial networks (GANs), diffusion models, and large language models (LLMs).

> _Large language models (LLMs)_ accept as input a text prompt supplied by a user. They then generate output text, word by word (really token by token),
> using the prompt and all previously generated words as a guide. In effect, LLMs only design goal is to be very good at predicting the next word in a
> sequence of words initiated by the input prompt. That’s all they were trained to do. However, that is not all that they learned to do. AI
> researchers are so excited by LLMs because while learning to be expert text generators, LLMs also learned a host of emergent
> abilities, including question answering, mathematical reasoning, high-quality computer programming, and logical reasoning.

> Future historians might point to the Fall 2022 release of OpenAI’s ChatGPT large language model as the dawn of true AI.  

Modern processing capabilities have made LLMs practical in 2023, and humanity's imagination has made it the most discussed technology of this year.

## Where and how can you learn it?

- Learn how [_VMware_ empowers AI/ML](https://www.vmware.com/products/vsphere/ai-ml.html), including a link to **free** _NVIDIA_-powered hands-on labs.  
- [Frank Denneman](https://twitter.com/frankdenneman) has a series of articles covering [machine learning with vSphere](https://frankdenneman.nl/category/machine-learning/). His article _[Basic Terminologies Large Language Models](https://frankdenneman.nl/2023/08/18/basic-terminologies-large-language-models/)_ is a great reference and should be bookmarked!  
- There are several free and paid AI courses on [Coursera](https://www.coursera.org/). At the moment, the most highly rated course is _[AI for Everyone](https://www.coursera.org/learn/ai-for-everyone)_.  
- _Helsinki University_ offers a free _[Elements of AI](https://www.elementsofai.com/)_ online course.  
- News, courses, videos, toolkits and more are available from _[Learn with Google AI](https://ai.google/build/machine-learning/)_.  
- _edX_ offers free and paid courses in [Artificial Intelligence](https://www.edx.org/learn/artificial-intelligence) and [Machine Learning](https://www.edx.org/learn/machine-learning).  
- _Microsoft_ offers free courses in [Azure AI Services & Azure Machine Learning](https://learn.microsoft.com/en-us/training/browse/?expanded=azure&products=ai-services%2Cazure-machine-learning).  
- Purchase a book from a person involved in this field. [How AI Works](https://nostarch.com/how-ai-works) is meant to be a general introduction to AI, ML and LLMs without complicated math but still giving you valuable context.
- Purchase an NVIDIA course called [Introduction to AI in the Data Center](https://academy.nvidia.com/en/course/intro-aidc/?cm=12076)
- [NIST Risk management for AI](https://www.nist.gov/itl/ai-risk-management-framework)  

## I keep hearing about HuggingFace; what is it?

HuggingFace is "the platform where the machine learning community collaborates on models, datasets, and applications". Importantly, this is where people upload their [models](https://huggingface.co/models), their [training datasets](https://huggingface.co/datasets), and where projects are categorized in [spaces](https://huggingface.co/spaces). One of the most interesting links is [the LLM leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) where the speed of development is apparent.

VMware has its own page on the HuggingFace webpage with models and training sets that will offer you "Domain adapting language models to VMware-specific use cases": 

https://huggingface.co/VMware

You can see in this [video from Prompt Engineering](https://youtu.be/N-qaMCwqRHI) how the website is browsed and how some features are used to test a new, more efficient model.  

## I keep hearing about MidJourney, Runway, etc.

[MidJourney](https://www.midjourney.com/) is known for generating images using AI. From [Wikipedia](https://en.wikipedia.org/wiki/Midjourney): "Midjourney is a generative artificial intelligence program and service created and hosted by San Francisco-based independent research lab Midjourney, Inc. Midjourney generates images from natural language descriptions, called "prompts", similar to OpenAI's DALL-E and Stable Diffusion."  

[Runway Gen2](https://research.runwayml.com/gen2) is "A multimodal AI system that can generate novel videos with text, images or video clips". Combined with MidJourney, using its Image 2 Video capabilities, you can generate movies completely in these tools such as [this one](https://twitter.com/acstle/status/1684033395205230592?s=20).

## What does your lab need to run AI/ML and Large Language Models (LLMs)?

### GPU

Although some AI/ML workloads are capable of running without a GPU, having a GPU can significantly improve performance. AI/ML workloads can take advantage of common commodity GPUs from the likes of _AMD_ and _NVIDIA_. At present _NVIDIA_ GPUs are the most commonly used and supported. The more GPU VRAM your video card has, the more performant and capable AI/ML can be. Ideally, your GPU should have at least 8 GB of VRAM.

#### NVIDIA

Probably the best resource for everything NVIDIA plus vSphere is the _[VMware vSphere Deployment Guide](https://docs.nvidia.com/ai-enterprise/deployment-guide-vmware/0.1.0/index.html)_ from the _NVIDIA Docs Hub_.

### CPU, RAM, Storage

While AI/ML can run on a variety of hardware platforms, including single board computers (SBCs) like _Raspberry Pis_, you get more flexibility from an x86-64 bit processor. Whether _Intel_ or _AMD_, your CPU should have at least 4 cores. An x86-64 bit processor also provides access to PCI-Express lanes that allow your system to have one or more GPUs.

When it comes to system RAM, try to have double the amount of GPU VRAM. For example, if your GPU has 8 GB VRAM, you should have at least 16 GB system RAM.

Depending on how many LLMs, other models, or data sets you want to download or train, AI/ML can consume anywhere from hundreds of megabytes to petabytes or more. For a lab environment, having at least several hundred gigabytes should allow you to store and use a number of pre-trained LLMs. For AI/ML, the more storage you can provide, the better. Like most workloads, AI/ML benefits from faster storage like NVMe-based solid state drives.

## Homelab Quickstart Guide

### Coral TPU  

If you are interested in working with _[TensorFlow](https://www.tensorflow.org/)_, [William Lam](https://github.com/lamw) has managed to connect a [Coral USB TPU Accelerator to ESXi](https://williamlam.com/2023/05/google-coral-usb-edge-tpu-accelerator-on-esxi.html). This isn't cutting edge technology, but it's a [very affordable TPU](https://coral.ai/products/accelerator) that you can get from Amazon and many other retailers; we brought one to the Hackathon if you want to see it!

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
    ```powershell
    iex (irm auto11.tc.ht)
    ```

### But I don't have the hardware...  

Recently we have seen demo use cases like _[Distributed Llama 2 on CPUs](https://towardsdatascience.com/distributed-llama-2-on-cpus-via-llama-cpp-pyspark-65736e9f466d)_ that allow AI/ML to run on CPU with very small hardware requirements. The projects are not the same as an enterprise use case, but they can still help solidify concepts.

<p align="center" width="100%">
    <img src="https://github.com/2023-VMware-Hackathon-HomeTeam/One-stop-shop-to-accelerate-learning-VMware-AI-ML/assets/16085267/c1bde63b-f548-47e5-8958-5c90c07776fc" width="50%" alt="An image of text from the opening section of the Distributed LLama 2 on CPUs article linked above." />
</p>

Also, here's a tutorial on [running the open source LLaMa 2 on Windows, Linux or Mac locally](https://replicate.com/blog/run-llama-locally).

### I've heard about LLaMa; what is it?

[LLaMa](https://ai.meta.com/llama/) is an open source LLM available for free for research and commercial use. It seems to be one of the most popular options for learning and deploying in enterprises.  

This [beginner's guide](https://agi-sphere.com/llama-guide/) is very good at explaining the concepts at a high level. In particular, this table is useful:

<p align="center" width="100%">
    <img src="https://github.com/2023-VMware-Hackathon-HomeTeam/One-stop-shop-to-accelerate-learning-VMware-AI-ML/assets/16085267/b11428a8-a67b-419d-ac5c-c994f1158227" width="50%" alt="An image text from the 'What Computer Hardware Do I Need?' section of the beginner's guide linked above. Includes two tables of VRAM recommendations for various Llama model types." />
</p>

## Diving Deeper - Where to go from here?

Here are some resources if you'd like to get a deeper understanding of AI/ML:

- _TensorFlow_ provides a [resource library with curated curriculums](https://www.tensorflow.org/resources/learn-ml) for machine learning.
- Join an AI/ML challenge on _[Kaggle](https://www.kaggle.com/)_. New challengers can get started with the [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/overview) challenge
- Check with your local colleges and universities to see if they offer AI/ML disciplines within their computer science program  

## Show me what's out there

We wanted to include interesting links that may spur your interest, with a little commentary and dates, so you can see how fast the space is changing. Several of these are from _Twitter/X_ which is indeed a good social network for this topic.

| Date | Link | Comment |
| --- | --- | --- |
| June 2023 | https://twitter.com/mreferre/status/1670752054334181376?s=20 | Massimo dives deeper into all the technology needed to do LLMs from scratch |
| July 2023 | https://twitter.com/alvinfoo/status/1683434918070845440?s=20 | A mashup of Barbie and Oppenheimer movies created solely with AI tools |
| July 2023 | https://twitter.com/Kyrannio/status/1682542654675111936 | A music video where images, video and music were created using AI tech |
| July 2023 | https://twitter.com/svpino/status/1684967487950004231?t=xTQO75bwSLz1p5T4ZQa8yg&s=19 | Some LLMs are being aimed at helping developer productivity |
| July 2023 | https://the-decoder.com/text-to-video-is-improving-rapidly-here-are-some-examples-created-with-runway-gen-2/ | Runway Gen2 tutorial |
| July 2023 | https://www.forbes.com/sites/steveandriole/2023/07/26/llama-chatgpt-bard-co-pilot--all-the-rest--how-large-language-models-will-become-huge-cloud-services-with-massive-ecosystems/amp/ | Forbes evaluates LLMs |
| Aug 2023 | https://www.forbes.com/sites/billfrist/2023/08/01/how-generative-ai--a-technology-catalyst--is-revolutionizing-healthcare/amp/ | Forbes evaluates the impact of AI related technologies on Healthcare |
| Aug 2023 | https://decrypt.co/150861/nvidia-ai-image-generator-floppy-disk-4-minutes?amp=1 | Nvidia AI Image Personalization Method Fits on a Floppy Disk and Takes 4 Minutes to Train |
| Aug 2023 | https://the-decoder.com/chatgpt-gets-several-new-features-including-multi-document-chat/ | New features in ChatGPT, including uploading multiple documents to ask questions on |

[^1]: Image generated via _[Stable Diffusion](https://github.com/Stability-AI/stablediffusion)_. Audio generated via _[ElevenLabs](https://elevenlabs.io/)_. Video generated via _[SadTalker](https://github.com/OpenTalker/SadTalker)_
