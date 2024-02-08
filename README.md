<p align="center">
<img src="https://github.com/Kriz182/looker-explore-assistant/blob/main/static/uc9.png" width="350" height="350" alt="Cool Logo" style="border-radius: 10px;">
</p>


# Data Exploration Assistant using Looker's Semantic Layer

## Overview
This repository contains Notebooks to generate a context for a natural language query interface. It uses LLM to translate users' query into a structure Looker query and display the results in Looker's Explore.

<img src="https://github.com/Kriz182/looker-explore-assistant/blob/main/static/image1.gif"  alt="Demo" >

## Prerequisites
- Access to Google Cloud Platform (GCP) with Vertex AI Enabled.
- Access to a Looker Instance.
- Basic understanding of Looker's Explore Interface.
- [Private Embedding enabled in the instance, same-origin disable and 3P cookies disabled] (https://cloud.google.com/looker/docs/private-embedding)

## Features
- **Natural Language Query**: Query data in Looker using Natural Language
- **Visualisation**: Define Visualisation to plot the data

## How to Use
1. **Clone the Repository or Download the Notebooks**: Clone this repository to your local machine or or just the Notebooks into your preferred environement.
3. [**Looker Context Examples**:](https://github.com/Kriz182/looker-explore-assistant/blob/main/looker_context_examples.ipynb) : This Notebook generate the context and examples to be used as prompt to the LLM.
   Ensure to copy the results and save them to be used later
5. [**Explore Assistant Sandbox**](https://github.com/Kriz182/looker-explore-assistant/blob/main/explore_assistant_sandbox.ipynb): This Notebook run the sandbox environement using Gradio.
   In the Notebook you need to paste the context and examples in the place holders. 

## Additional Information
- The Notebook comments provide guidance.
- Modify the script as needed to suit your specific requirements or to analyze a different semnatic model.
- Both Notebooks use [**Gradio**](https://www.gradio.app/) to setup the interface to interact with the script.


## License

This project is licensed under the terms of the GNU General Public License version 3 (GPLv3).
