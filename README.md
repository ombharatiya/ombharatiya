<div align="center">

# Om Bharatiya

### Principal AI Engineer · Agentic Platforms, MCP & Eval Infrastructure

[![Website](https://img.shields.io/badge/ombharatiya.com-0A1226?style=flat-square&logo=googlechrome&logoColor=white)](https://www.ombharatiya.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ombharatiya)
[![X](https://img.shields.io/badge/@ombharatiya-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/ombharatiya)
[![Email](https://img.shields.io/badge/coffeewithom@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:coffeewithom@gmail.com)

📍 Dubai, UAE

**I build AI systems for places where a wrong answer costs money.**

Agentic platforms, MCP servers, and eval infrastructure for enterprise banking.
7+ years shipping production AI: ISRO → Swiggy → Mensa Brands → banking-scale platforms.
~7k stars on open source. Writing read by 80k+ engineers.

</div>

---

## Open source

**[AI System Design Guide](https://github.com/ombharatiya/ai-system-design-guide)** · ★ 1.7k
How to design production AI systems and evals. Actively maintained. This is where my current thinking lives.

**[FAANG Coding Interview Questions](https://github.com/ombharatiya/FAANG-Coding-Interview-Questions)** · ★ 5.1k
The curated interview prep list, forked 1.2k+ times.

**[TranscriptAI](https://github.com/ombharatiya/transcript-ai)**
Multilingual speech-to-text CLI on OpenAI Whisper. Batch processing, 8+ formats.

**[Screwdriver CI/CD](https://github.com/screwdriver-cd/ui/pulls?q=is%3Apr+is%3Amerged+author%3Aombharatiya)**
10+ merged PRs across UI, models, and core. Shipped GitHub/GitLab PR validations used by 10k+ engineers.

## Shipped to production

| System | The number | Context |
|--------|------------|---------|
| [Fintech Document AI](https://gist.github.com/ombharatiya/de4fe4c953859eb442499c6b143e02dd) | **$0.01 per doc** | 200k requests/min at 99.5% accuracy, 90% cost reduction |
| [Trade-docs compliance agents](https://www.ombharatiya.com/projects/compliance-ai) | **weeks → hours** | review time down from 1-3 weeks to 2-4 hours, 98% audit completeness |
| [Agentic Engineering Platform](https://www.ombharatiya.com/projects/agentic-engineering-platform) | **33% infra saved** | MCP orchestration with hierarchical tool taxonomy, 57% compute optimization |
| [DiffusionID portrait pipeline](https://www.ombharatiya.com/projects/diffusionid) | **95% cheaper** | than commercial APIs, at 450 images/hour and 10k+ cards per batch |
| Core platform reliability | **99.9% uptime** | up from 88%, queries cut from 45s to 200ms, $2M+ downtime saved |

## Writing: [The Real Signal](https://www.ombharatiya.com/blog)

No-hype takes on AI, written from inside production systems:

- [Uber Blew Its AI Budget in One Quarter. So Will You.](https://www.ombharatiya.com/blog/uber-ai-budget-blown)
- [Nobody Goes to Parties and Talks About TCP/IP](https://www.ombharatiya.com/blog/mcp-protocol-won) (on MCP quietly winning)
- [Karpathy Says He's Never Felt This Behind. That Should Scare You.](https://www.ombharatiya.com/blog/vibe-coding-trap)
- [You Don't Pick the Best Model. You Pick the One That Gets You.](https://www.ombharatiya.com/blog/ai-model-personalities)

## Stack

**AI/ML:** Claude, GPT-4, Llama 3.1 · SDXL, InstantID · LangChain, PyTorch, Hugging Face · RAG, agentic workflows, vector search
**Backend:** Python, Java, Go, TypeScript · PostgreSQL, Redis, DynamoDB, Elasticsearch · Kafka, SQS, EventBridge
**Infra:** AWS (Bedrock, SageMaker, EKS, CDK) · Kubernetes, Terraform · Datadog, Prometheus, NewRelic

## How I build

```python
def ship_ai_system(requirements):
    """
    Rules I learned in production, the expensive way:
    1. Build the meter before you turn on the tap
    2. No evals, no deploy
    3. Treat LLMs as unreliable services; design for failure
    4. The boring fallback saves you at 3 a.m.
    5. Agents need governance more than they need autonomy
    """
    if handles_money_or_compliance(requirements):
        return validation_layers() + audit_trails() + human_in_the_loop()
    if needs_scale(requirements):
        return async_pipelines() + caching() + cost_meters()
    return something_simple_that_works()
```

## Currently

Researching multi-agent orchestration and eval infrastructure. Mentoring engineers on distributed systems and AI system design. Consulting with teams taking agents from demo to production.

---

<div align="center">

### Let's build something together

AI system design, agents in production, scaling war stories. Always up for that conversation.

[![Website](https://img.shields.io/badge/ombharatiya.com-0A1226?style=flat-square&logo=googlechrome&logoColor=white)](https://www.ombharatiya.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ombharatiya)
[![X](https://img.shields.io/badge/@ombharatiya-000000?style=flat-square&logo=x&logoColor=white)](https://twitter.com/ombharatiya)

*In order to understand recursion, one must first understand recursion.*

</div>
