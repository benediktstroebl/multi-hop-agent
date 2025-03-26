# Multi-Hop Reasoning Agent

This repository contains a multi-hop agent implementation using DSPy.

## Setup

1. Clone this repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Ensure you have an OpenAI API key in your `.env` file
4. Run the `multihop_agent.ipynb` notebook to train and evaluate the agent.
   
## Notes

1. Make sure your `.env` file contains your OpenAI API key:
```
OPENAI_API_KEY=your_api_key_here
```

2. The finetuned_4o_mini.pkl file is from an agent finetuned on 10 datapoints. It is only meant to be an example.
