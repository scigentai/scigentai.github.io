---
# Banner
banner:
  title: "Accelerating Health and Life Sciences Research with AI Agents"
  content: "Scigent is an open-source agentic platform that integrates validated scientific tools, published literature, and researcher oversight, turning general-purpose AI models into trustworthy scientific collaborators."
  image: "/images/scigent-logo-only.png"
  button:
    enable: false
    label: ""
    link: ""

# Features
features:
  - title: "The Rate-Limiting Step in Modern Science"
    image: "/images/platforms.svg"
    content: "Even expert researchers can engage with only a fraction of the data, literature, and tools relevant to their work. General-purpose AI coding assistants generate scripts but lack the scientific grounding to meaningfully accelerate discovery."
    bulletpoints:
      - "Vast volumes of scattered data, tools, and literature slow discovery from depression's neural signatures to genomic variant interpretation."
      - "AI agents without grounding hallucinate parameters and duplicate effort."
      - "The result: months-long timelines from raw data to advanced analysis."
    button:
      enable: false
      label: ""
      link: ""

  - title: "How Scigent Works"
    video:
      poster: "/videos/neurodesk.jpeg"
      webm: "/videos/neurodesk.webm"
      mp4: "/videos/neurodesk.mp4"
    content: "Scigent combines agentic AI with a validated research ecosystem. Researchers and agents collaborate to plan and execute end-to-end scientific analyses, with the researcher in control at every step. From neuroscience biomarkers to rare-variant interpretation to tissue-level disease mechanisms, full pipelines come together in days instead of weeks."
    bulletpoints:
      - "**Skill files** encode domain knowledge and parameter constraints to steer agents toward valid workflows."
      - "**Validated tool registry** built on 200+ containerised scientific tools."
      - "**Literature grounding** via published evidence and DOIs."
      - "**Full provenance** and reproducibility built in by default."
      - "**Model-agnostic** — wraps commercial and open-source LLMs as they evolve."
      - "**Runs anywhere** — laptop, hosted research, or partner infrastructure."
    button:
      enable: false
      label: ""
      link: ""

  - title: "Built on Neurodesk"
    image: "/images/neurodesk-logo.svg"
    content: "Scigent extends [Neurodesk](https://neurodesk.org), our open-source platform for biomedical imaging analysis, published in Nature Methods. Neurodesk provides the validated tool foundation Scigent builds on."
    bulletpoints:
      - "200+ containerised, version-pinned scientific tools."
      - "3,800 monthly users across 100+ countries, with several institutional deployments underway in 2026."
      - "Australian iAwards 2025 winner — Best Technology Platform."
      - "Backed by $2.5M+ AUD from ARDC, CZI, Wellcome Trust, and NIF."
    button:
      enable: true
      label: "Visit Neurodesk"
      link: "https://neurodesk.org"

  - title: "Measuring What Matters"
    terminal:
      steps: 180
      text: |
        $ scigent run "cortical thickness from this BIDS dataset" <br/>
        planning pipeline... 3 tools, 7 steps <br/>
        executing with claude-sonnet-4 in fmriprep container <br/>
        ✓ pipeline complete &nbsp;&nbsp;tokens -50% &nbsp;compute -20%
    content: "We co-develop [Terminal Bench Science](https://www.tbench.ai/news/tb-science-announcement) with Stanford and the Laude Institute as the primary benchmark for scientific AI agents. Early results across 20 neuroimaging workflows show meaningful efficiency gains."
    bulletpoints:
      - "**20% reduction** in compute across benchmarked workflows."
      - "**50% reduction** in token usage."
      - "Systematic evaluation across commercial and open-source models."
      - "Openly released benchmark suite as a community reference."
    button:
      enable: false
      label: ""
      link: ""
---
