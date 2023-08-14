# Gorilla Colab WebUI

This repository hosts a user-friendly Web User Interface (WebUI) built using Gradio, providing an interactive way to communicate with the Gorilla API directly from Google Colab.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1ktnVWPJOgqTC9hLW8lJPVZszuIddMy7y?usp=sharing)


## Introduction

[Gorilla LLM](https://huggingface.co/gorilla-llm) is an advanced language model that enables seamless interaction with APIs using natural language commands. This Colab notebook simplifies the process of conversing with Gorilla through a Gradio-based WebUI.

Huge thanks to [@ShishirPatil](https://github.com/ShishirPatil) for creating [Gorilla Repo](https://github.com/ShishirPatil/gorilla)

The WebUI leverages the power of [Gradio](https://github.com/gradio-app/gradio), a Python library for creating intuitive and interactive UIs for machine learning models. The interface is seamlessly deployed on Google Colab, offering a smooth and accessible platform for issuing commands to Gorilla and visualizing its API responses.

![Gorilla Colab WebUI](https://github.com/TanmayDoesAI/Gorilla-WebUI/assets/85993243/f167f774-8eef-4e02-aa55-0436c9e4547d)

## Usage

To utilize the WebUI, follow these steps:

1. Open the [Colab notebook](https://colab.research.google.com/drive/1ktnVWPJOgqTC9hLW8lJPVZszuIddMy7y?usp=sharing).

2. Execute all cells to load the requisite libraries and models, which may take a minute.

3. Interact with the WebUI by providing prompts and observing Gorilla's API responses.

Experiment with various prompts, such as:

- "Translate this sentence to French"
- "Summarize this paragraph in 5 sentences"
- "Generate an image of a cat"

The outputs are presented in organized blocks, showcasing the domain, API call, provider, explanation, and code.

## Customization

The Colab notebook can be personalized according to your preferences:

- Modify the Gradio UI by incorporating new components or adjusting the styling to align with your design choices.
- Opt for local deployment instead of using Colab, offering flexibility in where and how the WebUI is run.

Feel free to adapt the notebook to suit your specific requirements and enhance the user experience.
