---
title:  What is Ollama? 
author: malachyl  
date:   2026-06-10
updated:    2026-06-10 
tags:  	[Concept, basic]
---

# What is Ollama?
<!-- If you update the document title, ensure you update the title in the metadata above to match -->

Ollama is a platform for running large language models (LLMs) on local computers. Ollama stands for Omni-Layer Learning Language Acquisition Model.

## Applications and benefits
You can use Ollama to create content, generate code, and translate and localise documents. 

The ability to run LLMs locally provide you with several benefits:
* control over privacy (compared to using proprietary cloud models)
* experimentation without incurring usage or token costs
* access to a wide range of models tailored to different tasks and domains
* customisation and fine-tuning of models for specific needs
* integration with different tools and programming languages.

## Features
Using Ollama, you can download, run, import, and manage LLMs. 

Ollama provides both a user-friendly graphical interface and a command line option for advanced users. Use the command line option for initial setup and advanced features like customising models, and the graphical interface for general use such as code and content generation.

Additionally, Ollama provides a local HTTP API, client libraries for languages like JavaScript and Python, and a REST API.

## Limitations
Ollama has certain limitations that arise from running models locally.

Primarily, the hardware on the local system, including, CPU, GPU, RAM, and VRAM, affect the size of models that you can run and the performance of the models when in use. Ollama is not designed to scale to production-grade applications or distributed workloads. There is no access to proprietary or frontier models, and the downloaded models can quickly go out of date.