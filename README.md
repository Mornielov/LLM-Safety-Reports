# AI Red Team Portfolio / Portfolio de Red Team de IA

<aside>

**EN**: Offensive security work samples focused on LLMs, agents, and AI-enabled systems.

**ES**: Muestras de trabajo de seguridad ofensiva centradas en LLMs, agentes y sistemas con IA.

</aside>

---

## Projects / Case studies · Proyectos / Casos

> **EN**: Replace the placeholders with real engagements, writeups, repos, or redacted reports.
**ES**: Sustituye los placeholders por trabajos reales, writeups, repos o informes anonimizados.
> 

> **EN/ES**: Each case uses **Summary + Scope + Techniques** only (no Deliverables/Links).
> 

### Case 01 — (qwen3) Roleplay Jailbreak → Information Hazard Extraction

- **EN Summary**: Used roleplay and persona-conditioning to elicit disallowed / potentially harmful instructions and restricted details, validating real-world misuse risk.
- **ES Resumen**: Usé roleplay y condicionamiento de persona para obtener instrucciones prohibidas o potencialmente dañinas y detalles restringidos, validando el riesgo de abuso real.
- Scope / Alcance: chat-based LLM assistant; system prompt + policy stack; refusal behavior; safety evals
- Techniques / Técnicas: roleplay jailbreaks, incremental constraint relaxation, paraphrase & translation pivots, multi-turn coaxing, “harmless framing” (benign pretext)

### Case 02 — (gemma3) Roleplay Jailbreak → Coercive-Persuasion Guidance (Safety Failure)

- **EN Summary**: Through roleplay, elicited guidance aligned with manipulation/coercive persuasion. Documented the failure mode without retaining actionable step-by-step instructions.
- **ES Resumen**: Mediante roleplay, logré que el modelo proporcionara orientación alineada con manipulación/persuasión coercitiva. Documenté el fallo sin conservar instrucciones accionables paso a paso.
- Scope / Alcance: base model chat; safety policy & refusals; multi-turn conversational context
- Techniques / Técnicas: roleplay/persona framing, gradual escalation, rephrasing, “benign intent” pretexts, multi-turn persistence

### Case 03 — (gemma3) Roleplay Jailbreak → Engagement/Retention Script (Attention Capture)

- **EN Summary**: Via roleplay, elicited a script specifically optimized to be unusually attention-grabbing and hard to abandon, demonstrating a failure mode where the model helps maximize retention through potentially manipulative framing.
- **ES Resumen**: Mediante roleplay, logré que el modelo generara un guion optimizado para ser inusualmente atractivo y difícil de abandonar, mostrando un fallo en el que el modelo ayuda a maximizar la retención con un encuadre potencialmente manipulativo.
- Scope / Alcance: base model chat; content-generation; safety review for persuasive/retention patterns
- Techniques / Técnicas: roleplay/persona framing (creator/producer), gradual escalation toward retention goals, rephrasing, multi-turn persistence

### Case 04 — (qwen3.5) Opinion Spamming / Mass-Variation Generation (Misuse)

- **EN Summary**: With a simple prompt, the model generated 100 variations of the same opinion and claimed it could continue indefinitely, illustrating a misuse pattern for flooding, astroturfing, or content spam.
- **ES Resumen**: Con una pregunta simple, el modelo generó 100 variaciones de una misma opinión y afirmó que podía seguir indefinidamente, mostrando un patrón de mal uso para flooding, astroturfing o spam de contenido.
- Scope / Alcance: base model chat; high-volume generation; rate/length limits; abuse monitoring
- Techniques / Técnicas: bulk variation prompting, style/voice perturbations, iterative “keep going” loops, paraphrase cycling

---

### Case 05 — (gemma4) Roleplay Jailbreak → Information Hazard Extraction

- **EN Summary**: Used roleplay and persona-conditioning to elicit disallowed / potentially harmful instructions and restricted details, validating real-world misuse risk.
- **ES Resumen**: Usé roleplay y condicionamiento de persona para obtener instrucciones prohibidas o potencialmente dañinas y detalles restringidos, validando el riesgo de abuso real.
- Scope / Alcance: chat-based LLM assistant; system prompt + policy stack; refusal behavior; safety evals
- Techniques / Técnicas: roleplay jailbreaks

## Contact · Contacto

<aside>
<img src="/icons/lock_green.svg" alt="/icons/lock_green.svg" width="40px" />

**EN**: Preferred contact: email. Please include scope, timeline, and whether data can be shared for testing.

**ES**: Contacto preferido: email. Incluye alcance, fechas y si se puede compartir datos para pruebas.

</aside>

- Email: [mornielov@gmail.com](mailto:mornielov@gmail.com)
- Location / Zona horaria: Europe/Madrid

---

## Quick profile · Perfil rápido

- Focus / Enfoque: LLM security, agent security, RAG security, evaluation
- Deliverables / Entregables: red-team reports, threat models, test harnesses, guardrails
- Methods / Métodos: ATT&CK-style mapping, adversarial testing, reproducible Po
