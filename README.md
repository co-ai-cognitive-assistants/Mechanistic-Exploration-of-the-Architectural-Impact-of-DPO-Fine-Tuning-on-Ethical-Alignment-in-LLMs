Mechanistic-Exploration-of-the-Architectural-Impact-of-DPO-Fine-Tuning-on-Ethical-Alignment-in-LLMs

This repository contains code for the paper Mechanistic-Exploration-of-the-Architectural-Impact-of-DPO-Fine-Tuning-on-Ethical-Alignment-in-LLMs

## Setup

1. Install the required dependencies:

```bash
pip install -r requirements.txt
```

2. Download the model weights:
   - The model weights are hosted separately due to size limitations
   - Download from: [coai/gemma_2b_evil_research](https://huggingface.co/coai/gemma_2b_evil_research)


## Note
Some imports in the code reference the local Gemma-2b model. These need to be updated to use the HuggingFace hosted version at `coai/gemma_2b_evil_research`.

## Requirements
All dependencies are listed in `requirements.txt`. Install them using pip as shown above.