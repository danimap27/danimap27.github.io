# Visibilidad del paper CMES 148(1):26 en respuestas de LLM

Paper: *Hybrid Classical-Quantum Transfer Learning with Noisy Quantum Circuits* — DOI 10.32604/cmes.2026.082712, CC BY 4.0, arXiv 2603.16973.

## Hecho (16-nov-2026)

| Acción | Resultado |
|---|---|
| Página propia del paper, con resumen citable, tablas de resultados reales, FAQ en forma de pregunta y JSON-LD `ScholarlyArticle` + `FAQPage` | https://danimap27.github.io/papers/cmes-082712/ |
| Mirror del PDF (CC BY 4.0) con nombre descriptivo y metadata | https://danimap27.github.io/files/MartinPerez-2026-Hybrid-Classical-Quantum-Transfer-Learning-CMES.pdf |
| Página de autor (entidad) + `llms.txt` | https://danimap27.github.io/ · https://danimap27.github.io/llms.txt |
| `robots.txt` que permite explícitamente GPTBot, ClaudeBot, PerplexityBot, CCBot, Google-Extended, OAI-SearchBot… | https://danimap27.github.io/robots.txt |
| IndexNow enviado (Bing → alimenta Copilot y ChatGPT Search, Yandex, Seznam) | 202 Accepted |
| README de `qtl-experiments` con cita completa, DOI, arXiv y enlace a la página + topics + homepage | https://github.com/danimap27/qtl-experiments |

## El problema de fondo

`techscience.com` bloquea en su `robots.txt` a CCBot, ClaudeBot, GPTBot y Google-Extended,
y declara `Content-Signal: ai-train=no`. La copia que los LLM pueden leer es **arXiv**,
no la editorial. Por eso todo lo anterior apunta a arXiv + página propia, y no a TSP.

## Pendiente (requiere tu login — 15 min, en este orden)

1. **arXiv v2 con journal-ref** (10.48550/arXiv.2603.16973 solo tiene v1). Entra en
   https://arxiv.org/abs/2603.16973 → *Submission history* → editar y añadir en Comments:
   `Accepted in Computer Modeling in Engineering & Sciences 148(1):26, 2026. doi:10.32604/cmes.2026.082712`
   y en Journal-ref: `Comput. Model. Eng. Sci. 148(1):26 (2026)`. Refuerza el enlace DOI ↔ arXiv,
   que es lo que leen Semantic Scholar/OpenAlex/INSPIRE.
2. **Wikidata**: crea el ítem del paper con https://sourcemd.toolforge.org (pegas el DOI y genera
   el ítem con Crossref). Wikidata alimenta el grafo que usan Google y los LLM.
   Después, si quieres, crea tu ítem de persona con ORCID 0009-0002-4302-0928 y enlázalo.
3. **Google Scholar**: si no tienes perfil, créalo y verifica con el email @upo.es. Sin perfil,
   el paper no se agrupa con tus citas y pierde señal de autoridad. Con perfil, añade también
   el enlace al PDF de arXiv.
4. **RiUPO** (repositorio institucional UPO) o idUS: deposita el accepted manuscript. Otro
   full-text en dominio .edu/.es = otra fuente que los buscadores y LLM pueden leer.
5. **ResearchGate**: añade el paper con el DOI (importa metadatos) y sube el PDF; RG aparece
   mucho en respuestas de Perplexity/ChatGPT por su buena indexación.

## Palancas lentas pero las que más pesan

- **Citas**. Cada paper que te cite mete tu título en texto que los LLM leen. Es el factor
  dominante a 12-24 meses.
- **Menciones en sitios muy rastreados**: GitHub (hecho), Hugging Face, Reddit r/QuantumComputing,
  Hacker News, dev.to, Wikipedia solo si un artículo ya habla del tema.
- **Traducción a lenguaje natural de tus propios resultados**: la FAQ de la página está escrita
  con las cifras reales justo para que un LLM pueda copiar la respuesta sin equivocarse. Ese es
  el mecanismo que hace que te citen.
- **Latencia**: los modelos ya entrenados no te van a citar por esto; mejora la recuperación en
  vivo (ChatGPT Search, Perplexity, Copilot, AI Overviews) en semanas, y el entrenamiento futuro
  en meses.
