# FROM_SCRATCH_LLM

Welcome to **FROM_SCRATCH_LLM**, an experimental project where I’m building a **Large Language Model (LLM)** from the ground up using **PyTorch**. This journey involves coding a small **GPT-like model**—complete with its data pipeline, architecture, and pretraining—followed by finetuning and tweaking using **LitGPT**. I’m also experimenting with model parameters to see how they affect performance. This project is inspired by my book, *Build a Large Language Model From Scratch*, and incorporates some code from LitGPT.

## Project Overview

This is a hands-on exploration of LLM internals, built through trial and error. The goal? Understand how these models work by creating one from scratch, then enhancing it with pretrained weights and finetuning. Below are the key steps I’m tackling.

## Steps I’m Exploring

### 1. Data Pipeline
- **Description**: Building a custom text tokenizer and a PyTorch `DataLoader` to feed data into the LLM efficiently.
- **Folder**: `data`
- **Goal**: Ensure the model can process text smoothly.

### 2. Building the Model
- **Description**: Assembling a GPT-like architecture, connecting layers and components to bring it to life.
- **Folder**: `architecture`
- **Goal**: Create a compact, functional language model.

### 3. Pretraining Hack
- **Description**: Pretraining the model on a tiny public text sample to test its ability to generate basic sentences.
- **Folder**: `pretraining`
- **Goal**: Confirm it can learn and produce coherent output.

### 4. Loading Weights
- **Description**: Importing pretrained weights into the model using LitGPT, pulling from models like **Llama, Phi, Gemma, Mistral**, and others.
- **Folder**: `weightloading`
- **Goal**: Boost the model’s capabilities with pretrained knowledge.

### 5. Finetuning Play
- **Description**: Finetuning the model with a small custom dataset, refining it in LitGPT to enhance its skills.
- **Folder**: `finetuning`
- **Goal**: Tailor the model for specific tasks or behaviors.

## Notes
- This is an experimental playground! Feel free to explore, suggest improvements, or toss in creative ideas. I’m learning as I go, and collaboration is encouraged.

## Getting Started
1. Clone this repo: `git clone <repo-url>`
2. Install dependencies: `pip install -r requirements.txt`
3. Dive into a folder and start hacking!

## Contributing
Got ideas? Found a bug? Want to experiment with me? Open an issue or submit a pull request—I’d love to hear from you!


*Built with curiosity, a lot of coffee, and help from open source*
