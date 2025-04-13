# Building Effective Agents – LangGraph & CrewAI Colab Series

Welcome to the official GitHub repository for my multi-pattern agent design assignment. This project demonstrates:

- Core agent design patterns from the *Building Effective Agents* framework.
- Implementation using two orchestration libraries: **LangGraph** and **CrewAI**.
- Each pattern is structured in Colab notebooks with LangSmith/agent trace walkthroughs.
- All notebooks are **original**, agent-aware, and carefully explained in video walkthroughs.

---

## 🎥 Video Walkthroughs

Each Colab has been executed, traced, and explained in a dedicated walkthrough video:

- 🔗 **[LangGraph Patterns Walkthrough](./walkthrough_videos/langgraph_walkthrough.mp4)**
- 🔗 **[CrewAI Agent Patterns Walkthrough](./walkthrough_videos/crewai_walkthrough.mp4)**

---

## ✅ LangGraph Patterns

### 📘 [1_prompt_chaining.ipynb](#)
> **Focus**: Sequential refinement of LLM output through prompt chaining.

- Generated a joke → improved it → polished it
- Used a quality gate to stop or continue
- Illustrated LangGraph conditional transitions

---

### 📘 [2_parallel_execution.ipynb](#)
> **Focus**: Executing independent tasks in parallel.

- Generated a joke, story, and poem simultaneously
- Aggregated responses into a single output
- Demonstrated fan-out/fan-in pattern using LangGraph

---

### 📘 [3_routing.ipynb](#)
> **Focus**: Dynamic routing based on LLM decision.

- Routed input to joke/story/poem generators
- Used structured output from the router LLM
- Clean example of classification → branch logic

---

### 📘 [4_orchestrator_worker.ipynb](#)
> **Focus**: Plan a task and assign subtasks to worker agents.

- Orchestrator plans report sections
- Workers generate each section in parallel
- Final report synthesized from all outputs

---

### 📘 [5_evaluator_optimizer.ipynb](#)
> **Focus**: Feedback loop with structured evaluation.

- LLM generates a joke
- Evaluator agent grades its quality
- Loops until a “funny” grade is achieved

---

### 📘 [6_agent_loop.ipynb](#)
> **Focus**: Tool-using agent with reasoning loop.

- Agent solves arithmetic tasks using tools
- Dynamically selects tools: add, multiply, divide
- Iterates until final response is produced

---

## 🤝 CrewAI Patterns

### 📘 [1_prompt_chaining_crewai.ipynb](#)
> **Focus**: Sequential improvement via role-based agents.

- Writer → Improver → Editor agents
- Agent chaining using CrewAI task delegation
- Structured response flow across roles

---

### 📘 [4_orchestrator_worker_crewai.ipynb](#)
> **Focus**: Crew-based report generation pipeline.

- Planner agent decides report layout
- Multiple writer agents generate sections
- Editor agent compiles final report

---

### 📘 [6_agent_loop_crewai.ipynb](#)
> **Focus**: Role-driven task completion using tools.

- Solver agent uses built-in tools
- Executes multi-step arithmetic task
- Demonstrates loop + tool use within CrewAI

---

## 📚 Resources & References

- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [CrewAI Documentation](https://docs.crewai.io/)
- [LangSmith Studio](https://smith.langchain.com/)
- [Building Effective Agents – Anthropic Blog](https://www.anthropic.com/research/building-effective-agents)
- [Agents in LangGraph – DeepLearning.AI Course](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)

---

