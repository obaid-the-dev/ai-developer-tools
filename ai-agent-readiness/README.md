# AI Agent Readiness Kit

Three plain-text templates for deciding whether a business workflow is ready for an AI agent, and for keeping it safe once it is.

| File | Use it to |
|---|---|
| `scorecard.md` | Score candidate workflows (1–5) on volume, clear "done", unstructured input, reversibility, data access and ownership |
| `approval-matrix.md` | List every action the agent can take, its risk, and who must approve it |
| `eval-cases.yaml` | Write test cases that assert on tool calls (must / must-not / must-escalate) |

Background: [AI Agents for Business in 2027](https://aidevplanner.com/blog/ai-agents-for-business) (business view) and the
[OWASP Top 10 for LLM Applications](https://genai.owasp.org/llmrisk/llm01-prompt-injection/) (security view).
