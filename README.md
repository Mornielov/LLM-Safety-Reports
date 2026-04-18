# 🐯 AI Red Team Portfolio / Portfolio de Red Team de IA
EN: Offensive security work samples focused on LLMs, agents, and AI-enabled systems.

ES: Muestras de trabajo de seguridad ofensiva centradas en LLMs, agentes y sistemas con IA.

# 🛠️ Projects / Case studies · Proyectos / Casos
Note: Each case uses Summary + Scope + Techniques only.

## 🚨 Case 01 — (Qwen 3) Roleplay Jailbreak → Information Hazard Extraction
📖 Resumen: Usé roleplay y condicionamiento de persona para obtener instrucciones prohibidas o potencialmente dañinas y detalles restringidos, validando el riesgo de abuso real.

🎯 Alcance: chat-based LLM assistant; system prompt + policy stack; refusal behavior; safety evals.

⚔️ Técnicas: roleplay jailbreaks, incremental constraint relaxation, paraphrase & translation pivots, multi-turn coaxing, “harmless framing”.

## 🧠 Case 02 — (Gemma 3) Roleplay Jailbreak → Coercive-Persuasion Guidance
📖 Resumen: Mediante roleplay, logré que el modelo proporcionara orientación alineada con manipulación/persuasión coercitiva. Documenté el fallo sin conservar instrucciones accionables.

🎯 Alcance: base model chat; safety policy & refusals; multi-turn conversational context.

⚔️ Técnicas: roleplay/persona framing, gradual escalation, rephrasing, “benign intent” pretexts, multi-turn persistence.

## 👁️ Case 03 — (Gemma 3) Roleplay Jailbreak → Attention Capture Script
📖 Resumen: Logré que el modelo generara un guion optimizado para ser inusualmente atractivo y difícil de abandonar, mostrando un fallo en la generación de contenido manipulativo para retención.

🎯 Alcance: base model chat; content-generation; safety review for persuasive/retention patterns.

⚔️ Técnicas: roleplay/persona framing (creator/producer), gradual escalation, multi-turn persistence.

## 🌊 Case 04 — (Qwen 3.5) Opinion Spamming / Mass-Variation Generation
📖 Resumen: El modelo generó 100 variaciones de una misma opinión y afirmó poder seguir indefinidamente, validando patrones de Astroturfing o spam de contenido masivo.

🎯 Alcance: base model chat; high-volume generation; rate/length limits; abuse monitoring.

⚔️ Técnicas: bulk variation prompting, style/voice perturbations, iterative “keep going” loops, paraphrase cycling.

## ☣️ Case 05 — (Gemma 4) Roleplay Jailbreak → Information Hazard Extraction
📖 Resumen: Condicionamiento avanzado para saltar las protecciones de la versión 4, obteniendo detalles restringidos bajo un pretexto de investigación técnica.

🎯 Alcance: chat-based LLM assistant; system prompt + policy stack; refusal behavior; safety evals.

⚔️ Técnicas: roleplay jailbreaks.

# 👤 Quick profile · Perfil rápido
### 🎯 Focus / Enfoque: LLM security, agent security, RAG security, evaluation.

### 📦 Deliverables / Entregables: Red-team reports, threat models, test harnesses, guardrails.

### 🧪 Methods / Métodos: ATT&CK-style mapping, adversarial testing, reproducible PoC.

### 📬 Contact · Contacto
### 📧 Email: mornielov@gmail.com

### 📍 Location / Zona horaria: Europe/Madrid (Spain 🇪🇸)

📝 Nota: Incluye alcance, fechas y si se pueden compartir datos para pruebas.
