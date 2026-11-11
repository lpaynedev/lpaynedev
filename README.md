# Luke Payne

Software Engineer | Python, TypeScript and Applied AI

I build Python APIs and TypeScript/Node.js applications, with C++ systems and ML data-pipeline experience. My applied AI work includes retrieval, structured LLM tool use and automated evaluation.

Based in Virginia and open to fully remote software and applied AI engineering opportunities without travel requirements.

[Portfolio](https://lukepayne.web.app/) · [LinkedIn](https://www.linkedin.com/in/lukepaynesci/)

## Selected AI projects

### LLM Tool Calling Lab

Built an experimental local chatbot to explore how an LLM can use specialized ML models as tools. It answers questions about numerical data, compares methods and shows recorded results, with limits on model runs and tool calls.

[Source and setup](https://github.com/lpaynedev/llm-tool-calling-lab) · [Illustrated case study](https://lukepayne.web.app/lab/llm-tool-calling-lab-first-release/) · [Download v0.1.0](https://github.com/lpaynedev/llm-tool-calling-lab/releases/tag/v0.1.0)

The first release is experimental and includes a frozen evaluation across four task families. The first pass found **33/48 grounded completions for generic tool calling and 31/48 with structured planning**. Added planning instructions did not improve measured completion. Results concern synthetic data and unblinded AI review; they do not demonstrate improved general reasoning.

My direction is inspectable local AI: validated execution, replaceable models, and explanations tied to recorded evidence. The next proposed work targets anomaly answers, unsupported requests, and evidence-supported next actions. [Vision and priorities](https://github.com/lpaynedev/llm-tool-calling-lab/blob/main/docs/VISION.md).

### Earth Science Metadata Agent

Built an independent prototype for finding Earth science datasets from plain-language questions. It searches NASA's public metadata API, retrieves related context with Chroma and summarizes returned records using FastAPI and LangGraph.

[Source and setup](https://github.com/lpaynedev/NASA_CMR_AGENT) · [Case study](https://lukepayne.web.app/projects/nasa-cmr-agent/)

This is a metadata-discovery prototype, not an official NASA product or an operational NASA service. It does not download and analyze Earth-observation measurements; dataset suitability still requires scientific review.

## Other selected work

| Project | Focus |
| --- | --- |
| [Brain in Computer (BiC)](https://github.com/lpaynedev/BiC) | Small neural learner with verified English curricula, an external local tutor loop, a CPU demo, and measured limits on acquisition and composition. |
| [AutoAgent](https://github.com/lpaynedev/AutoAgent) | Experimental code-review tooling with retrieval, structured findings and explicit failure handling. |
| [Smart Image Insights](https://github.com/lpaynedev/smart-image-insights) | Image-upload interface backed by object detection and captioning services. |
| [Fuguely case study](https://lukepayne.web.app/projects/fuguely) | Music lesson scheduling and connected teacher/student workflows. |
| [PRIM case study](https://lukepayne.web.app/projects/prim) | Deterministic simulation, experiment comparison and inspectable run state. |

## Engineering interests

- Python services, TypeScript applications and clear API boundaries.
- Reproducible workflows, useful tests and observable failure behavior.
- Retrieval and model integrations with explicit limits.
- Software for music, games and everyday organizational problems.
