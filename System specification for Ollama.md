---
title:  System specification for Ollama
author: malachyl  
date:   2026-06-10
updated:    2026-06-10 
tags:	[Reference, basic]
---

# System specification for Ollama
<!-- If you update the document title, ensure you update the title in the metadata above to match -->

To run your models effectively with Ollama, you must ensure your hardware has sufficient power and capacity for what you want to do. This topic outlines model sizes and the minimum system requirements to run them.

## Understanding model sizes

The hardware specification you need depends on the size of the model you plan to run and what you want to do with it. There are four size ranges as follows.

* **Mini models (270M-4B)** Suitable for mobile phones and mini-PCs with little memory. These models dos simple tasks or act as assistants where high quality is not critical.
* **Small models (4B-14B)** A balanced range for home and light professional use. Run well on "normal" PCs.
* **Medium models (14B-70B)** These require high specification hardware, especially if you want quick responses. They provide a significant leap in quality, context, and reasoning.
* **Large models (>70B)** This is the domain of advanced workstations, servers with multiple GPUs, or very high-end Macs.

The specifications outlined below are for mini to small entry-level models. For medium and large models, refer to the model documentation for recommended specifications.

## Windows
For a Windows installation of Ollama, you  need a minimum of:

* Windows 10
* 4th generation Intel i7 CPU or equivalent
* 8Gb of RAM
* SSD drive with 12Gb free space

This minimum specification runs small local models and you will probably notice a lag in text generation for models over 7B. For models smaller than 7B you do not need a GPU.

To work with Ollama in a production environment, you need a GPU. Use the following specifications:

* Windows 11
* 11th generation Intel CPU or higher / AMD CPU based on Zen 4
* GPU with 24 GB of VRAM
* 32Gb RAM
* SSD drive with 50Gb free space

## macOS
<-- ToDo - find the Mac specifications and populate this section>

## Linux
<-- ToDo - find the Linux specifications and populate this section>