# crofbench
tool calling and coding benchmark that gets to the point without pulverizing your wallet

## results
| Provider | Percentage | Total | General (/15) | Quality (/10) | Agentic (/5) | Model |
|---|---:|---:|---:|---:|---:|---|
| openrouter | 96.7% | 29/30 | 14/15 | 10/10 | 5/5 | `z-ai/glm-5.1` |
| crof -precision update | 96.7% | 29/30 | 15/15 | 10/10 | 4/5 | `glm-5.1-precision` |
| 5090 | 93.3% | 28/30 | 13/15 | 10/10 | 5/5 | `qwen3.6-35b-a3b` |
| crof (old precision) | 90.0% | 27/30 | 12/15 | 10/10 | 5/5 | `glm-5.1-precision` |
| crof | 86.7% | 26/30 | 12/15 | 9/10 | 5/5 | `greg` (v2) |
| crof | 83.3% | 25/30 | 12/15 | 10/10 | 3/5 | `glm-5.1` |
| crof | 80.0% | 24/30 | 12/15 | 9/10 | 3/5 | `greg` (v1) |
