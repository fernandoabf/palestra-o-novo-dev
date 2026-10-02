# O Novo Dev: o que o mercado está contratando na era da IA

De LLMs a agentes: RAG, SLMs e MCP na prática, com casos reais.

Palestra de **Fernando Braga**, cofundador e CTO da DomusTec e da Vastech, no **Tech Day**, em Camocim-CE, em 02/10/2026. Tema oficial do evento: IA e Futuro do Trabalho.

**Tese:** o mercado não está contratando menos devs; está contratando outro dev.

Os slides em PDF entram aqui depois do evento. Contato: [LinkedIn](https://www.linkedin.com/in/fernandobraga-dev) · [GitHub](https://github.com/fernandoabf)

## Referências

Os dados e casos citados na palestra, por bloco, e algumas leituras de apoio. Os números autodeclarados pelas empresas estão indicados como tal na palestra.

### 1. Abertura: o que está acontecendo com as vagas de dev

- [Indeed Hiring Lab](https://www.hiringlab.org/2026/07/08/ai-and-job-postings-from-destruction-to-creation/): alta de quase 15% nas vagas de dev, 71% sênior e 37% com IA no título
- [Yahoo Finance](https://finance.yahoo.com/technology/ai/articles/jobs-hit-hardest-ai-era-211351738.html): queda de 73% entre 2022 e 2025
- [FRED, Software Development Job Postings on Indeed in the United States](https://fred.stlouisfed.org/series/IHLIDXUSTPSOFTDEVE): série oficial do Indeed usada no esquema do gráfico

### 2. IA no ciclo de desenvolvimento

- [The Decoder](https://the-decoder.com/amazons-ai-assistant-saves-4500-years-of-development-time-ceo-andy-jassy-says/): Amazon Q e a migração para Java 17
- [Mobile Time](https://www.mobiletime.com.br/?p=854164): Nubank, +50% de produtividade em engenharia e +90% de testes
- [TechCrunch](https://techcrunch.com/2025/12/09/openai-anthropic-and-block-join-new-linux-foundation-effort-to-standardize-the-ai-agent-era/): AGENTS.md, goose, MCP e os membros da fundação

### 3. LLMs: o que são, como funcionam e como escolher

- [Attention Is All You Need, arXiv 1706.03762](https://arxiv.org/abs/1706.03762): artigo original da arquitetura transformer
- [Stanford HAI, AI Index 2026](https://hai.stanford.edu/ai-index/2026-ai-index-report): relatório completo
- [UNU, resumo do AI Index 2026](https://c3.unu.edu/blog/2026-stanford-ai-index-report-takeaways): capacidade irregular e distância entre modelos abertos e fechados
- [Burges Salmon, resumo do AI Index 2026](https://www.burges-salmon.com/articles/102mpq6/ai-in-2026-what-does-stanfords-ai-index-tell-us/): salto no SWE-bench Verified
- [Correio Braziliense](https://www.correiobraziliense.com.br/cbradar/o-papel-da-inteligencia-artificial-no-futuro-do-nubank/): assistente do Nubank e passagem para humano

### 4. RAG: dar ao modelo o conhecimento da empresa

- [PYMNTS](https://www.pymnts.com/artificial-intelligence-2/2023/morgan-stanley-to-launch-ai-powered-assistant-for-financial-advisors/): Morgan Stanley, 100 mil documentos
- [OpenAI](https://openai.com/index/morgan-stanley/): Morgan Stanley, 98% de adoção, acesso de 20% para 80% e avaliação

### 5. SLMs: modelos pequenos no mundo corporativo

- [CogitX](https://cogitx.ai/blog/small-language-models-slms-comprehensive-guide-2026): definição de SLM e quantização
- [Forbes](https://www.forbes.com/sites/johnkoetsier/2026/02/10/att-says-slms-run-at-10-of-the-cost-of-llms-while-being-about-as-accurate/): AT&T, SLM a cerca de 10% do custo
- [VentureBeat](https://venturebeat.com/orchestration/8-billion-tokens-a-day-forced-at-and-t-to-rethink-ai-orchestration-and-cut): AT&T, super agentes, até 90% de economia e 27 bilhões de tokens por dia
- [H2O.ai](https://h2o.ai/case-studies/att-call-center/): AT&T, Danube 1,8B no call center
- [arXiv 2504.16584](https://arxiv.org/pdf/2504.16584): modelo de 350M para detectar vulnerabilidades
- [arXiv 2405.20347](https://arxiv.org/pdf/2405.20347): estudo da Microsoft com SLMs
- [LoRA, arXiv 2106.09685](https://arxiv.org/abs/2106.09685) e [QLoRA, arXiv 2305.14314](https://arxiv.org/abs/2305.14314): artigos originais

### 6. MCP: dar ao modelo acesso aos sistemas

- [Linux Foundation](https://www.linuxfoundation.org/press/linux-foundation-announces-the-formation-of-the-agentic-ai-foundation): criação da Agentic AI Foundation e mais de 10 mil servidores MCP
- [Blog do MCP](https://blog.modelcontextprotocol.io/posts/2025-12-09-mcp-joins-agentic-ai-foundation/): governança do MCP na fundação

### 7. Agentes: juntando todas as peças

- [VentureBeat](https://venturebeat.com/orchestration/8-billion-tokens-a-day-forced-at-and-t-to-rethink-ai-orchestration-and-cut): AT&T, super agentes e agentes trabalhadores
- [Techbuddies](https://www.techbuddies.io/2026/02/27/inside-atts-agentic-ai-stack-how-8-billion-tokens-a-day-led-to-a-90-cost-cut/): AT&T, agentes trabalhadores

### 8. Confiança: segurança e avaliação

- [Law360](https://www.law360.ca/ca/articles/1804075): Air Canada, o tribunal rejeita a tese do chatbot como entidade separada
- [LoyaltyLobby](https://loyaltylobby.com/2024/02/19/passenger-sues-air-canada-over-bereavement-fare-discount-following-incorrect-guidance-by-chat-feature/): Air Canada, valor da condenação
- [Invicti](https://invicti.com/blog/web-security/owasp-top-10-risks-llm-security-2025): OWASP Top 10 para LLMs (2025)
- [Fast Company](https://www.fastcompany.com/91532091/mcdonalds-ai-bot-didnt-go-rogue) e [DeviceDaily, republicação da matéria](https://www.devicedaily.com/pin/theres-no-rogue-mcdonalds-ai-bot-but-prompt-injection-is-still-a-risk-for-companies/): o bot do McDonald's que "escreveu Python" era boato (abril de 2026)
- [Let's Data Science](https://letsdatascience.com/news/echoleak-exposes-data-via-microsoft-365-copilot-1fd222bf) e [AAAI](https://ojs.aaai.org/index.php/AAAI-SS/article/view/36899): EchoLeak, ataque, gravidade e correção
- [Ian Carroll](https://ian.sh/mcdonalds): McHire, do McDonald's: prompt injection tentada e sem sucesso, senha 123456 e cerca de 64 milhões de registros de candidaturas acessíveis (2025)
- [Krebs on Security](https://krebsonsecurity.com/2025/07/poor-passwords-tattle-on-ai-hiring-bot-maker-paradox-ai/) e [Paradox](https://paradox.ai/blog/responsible-security-update): McHire, a continuação e a resposta da empresa
- [Bloomberg](https://bloomberg.com/news/articles/2023-05-02/samsung-bans-chatgpt-and-other-generative-ai-use-by-staff-after-leak) e [Daum](https://v.daum.net/v/20230503140609036): Samsung, proibição de IA generativa e os três casos de vazamento
- [Invariant Labs](https://invariantlabs.ai/blog/mcp-github-vulnerability) e [DevClass](https://devclass.com/2025/05/27/researchers-warn-of-prompt-injection-vulnerability-in-github-mcp-with-no-obvious-fix/): GitHub MCP, vazamento de repositórios privados e mitigações
- [OpenAI](https://openai.com/index/morgan-stanley/): Morgan Stanley e o framework de avaliação

### 9. Fechamento: o novo dev

- [Klarna, comunicado de 27/02/2024](https://www.klarna.com/international/press/klarna-ai-assistant-handles-two-thirds-of-customer-service-chats-in-its-first-month/): o assistente fez dois terços dos chats no primeiro mês, o trabalho de 700 atendentes
- [Entrepreneur](https://www.entrepreneur.com/business-news/klarna-ceo-reverses-course-by-hiring-more-humans-not-ai/): Klarna, o assistente e os 700 atendentes
- [Xataka](https://www.xatakaon.com/robotics-and-ai/klarna-claimed-its-ai-was-doing-the-work-of-700-employees-its-now-rehiring-humans): Klarna, a volta atrás
- [Tech.co](https://tech.co/news/klarna-reverses-ai-overhaul): Klarna, o modelo que combina IA e humanos
