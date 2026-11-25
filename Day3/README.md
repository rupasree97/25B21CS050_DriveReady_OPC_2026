# Day 3 – First Agent Using LangChain

## Objective
Build a business assistant using LangChain and understand the basic concept of an AI agent.

## Business Problem
Sweet Crumbs Home Bakery needs an assistant that can answer customer questions about menu prices, eggless cakes, order notice periods, and delivery information.

## Concepts Learned
- What is an AI agent?
- LangChain basics
- Chat prompt templates
- System prompts
- Conversation history
- LLM chains
- CSV-based testing
- Prompt improvement
- Temperature and response variation
- Agent creation using LangChain

## Technologies Used
- Python
- Google Colab
- Groq API
- LangChain
- langchain-groq
- CSV

## Implementation
Created a bakery assistant using a LangChain prompt template and an LLM chain. Added conversation history and tested the assistant using customer questions stored in a CSV file.

Also created an agent demonstration using LangChain.

## Testing and Experiments

### Experiment 1 – Initial Prompt
Ran the customer question tests using the original system prompt.

Pass rate: [Enter your actual result]

### Experiment 2 – Improved Prompt
Changed the system prompt and ran the tests again.

Pass rate: [Enter your actual result]

### Experiment 3 – Temperature 1.0
Ran the tests twice using temperature 1.0 and observed whether the answers changed.

Run 1 pass rate: [Enter your actual result]

Run 2 pass rate: [Enter your actual result]

Observation: [Write what you actually observed.]

## Business Job Classification
1. Calculate product prices – Plain Python code.
2. Generate promotional messages – One LLM call.
3. Handle a complex order requiring multiple checks or actions – AI agent.

## Python Functions
Created two functions with type hints and docstrings:
- `get_price()` – Calculates the total price of a bakery item.
- `can_accept_order()` – Checks whether an order has the required 24-hour notice.

## Files
- `Day3_Sweet_Crumbs_LangChain_Agent.ipynb` – Day 3 implementation and experiments.
- `tests.csv` – Customer questions and expected answer keywords.

## How to Run
1. Open the notebook in Google Colab.
2. Add `GROQ_API_KEY` to Colab Secrets.
3. Enable access to the secret.
4. Run the notebook cells in order.
5. Make sure `tests.csv` is in the same working directory.

## Learning Outcome
Learned how to build a basic business assistant using LangChain, test LLM responses, improve prompts, and understand the difference between a normal LLM call and an agent.
