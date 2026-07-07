# LangGraph Tutorials

A collection of progressive tutorials for learning and building agentic workflows with LangGraph and LangChain.

## {:books:} Project Structure

The `src/` directory contains notebook tutorials in order of complexity:

* **0-Langgrap_intro.ipynb**: Introduction to LangGraph basics (StateGraph, States, Nodes, and Edges) using a BMI Calculator.
* **1-Simple_lmm_workflow.ipynb**: Single-node Q&A workflow integrated with ChatGroq.
* **3_prompt_chaining.ipynb**: Linear prompt chaining pattern (Blog Outline -> Content Generator).
* **4_Batsman_workflow.ipynb**: Parallel node execution. Runs independent stat calculations in parallel and aggregates them.
* **5_UPSC_essay.ipynb**: Advanced workflow featuring structured outputs (Pydantic), parallel grading criteria nodes, and custom state reducers/accumulators (`Annotated`).
* **main.py**: Minimal application entry point.

## {:wrench:} Setup

1. Install package dependencies:
   ```bash
   uv pip install -e .
   ```
2. Configure your environment in a `.env` file:
   ```env
   GROQ_API_KEY=your_groq_api_key
   ```
