# ReAct-Agents

Welcome to the ReAct-Agents project! This repository aims to guide you through the process of creating a ReAct (Reasoning and Acting) AI agent from the ground up.

## Introduction

ReAct is an AI paradigm that combines reasoning and acting in a synergistic manner. This project will help you understand the core concepts of ReAct and implement your own AI agent capable of reasoning about tasks and taking appropriate actions.

## Project Structure

The project is organized as follows:

```
├── src/
│   ├── agent.py
│   ├── prompts.py
│   ├── tools.py
│   └── utils.py
├── notebooks/
│   └── ReAct_Agent_Demo.ipynb
├── tests/
│   └── test_agent.py
├── requirements.txt
├── README.md
└── LICENSE
```

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/tushar2704/Lets_Build_ReAct_AI_Agent_From_Scratch.git
   cd Lets_Build_ReAct_AI_Agent_From_Scratch
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Explore the `src` directory to understand the core components of the ReAct AI agent.

4. Run the Jupyter notebook in the `notebooks` directory for a step-by-step demonstration of the ReAct agent in action.

## Key Components

- `agent.py`: Contains the main ReAct agent implementation.
- `prompts.py`: Defines the prompts used for reasoning and action generation.
- `tools.py`: Implements various tools that the agent can use to interact with its environment.
- `utils.py`: Provides utility functions for the agent and other components.

## Usage

To use the ReAct AI agent in your own projects:

1. Import the necessary modules:
   ```python
   from src.agent import ReActAgent
   from src.tools import available_tools
   ```

2. Initialize the agent:
   ```python
   agent = ReActAgent(available_tools)
   ```

3. Run the agent on a task:
   ```python
   result = agent.run("Your task description here")
   print(result)
   ```

## Contributing

Contributions to this project are welcome! If you have ideas for improvements or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Author

**©2024 Tushar Aggarwal. All rights reserved**

- [GitHub](https://github.com/tushar2704)
- [Website](https://tushar-aggarwal.com)
- [Medium](https://medium.com/@tushar_aggarwal)
- [LinkedIn](https://www.linkedin.com/in/tusharaggarwalinseec)
