<img src="https://capsule-render.vercel.app/api?type=waving&color=0:092E20,100:3776AB&height=200&section=header&text=Hi,%20I'm%20Artur&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Python%20and%20Django%20developer%20%E2%80%94%20from%20Kyiv%2C%20based%20in%20Krak%C3%B3w&descAlignY=58&descSize=18&animation=fadeIn" width="100%" alt="Hi, I'm Artur">

<p align="center">
  <a href="https://github.com/Artui">
    <picture>
      <source media="(prefers-reduced-motion: reduce)" srcset="assets/tagline.svg">
      <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=3200&pause=900&color=3776AB&center=true&vCenter=true&width=640&lines=Declare+an+operation+once%2C+serve+it+everywhere;REST%2C+HTML%2C+CLI%2C+MCP+and+AI+agents+from+one+spec;Agent+hosts+and+chat+UIs+for+Django;100%25+coverage+and+fully+typed" alt="Declare an operation once, serve it everywhere">
    </picture>
  </a>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,django,ts,go,postgres,redis,docker,githubactions,react,vue,svelte,angular&perline=12" alt="Python, Django, TypeScript, Go, PostgreSQL, Redis, Docker, GitHub Actions, React, Vue, Svelte, Angular">
</p>

## What I'm building

**One operation, declared once, served everywhere.** A Django operation is declared as a *spec*: its parameters, permission check, validation and output. The same spec is then served over REST, HTML, the command line, MCP, and to AI agents, without writing it again for each.

```mermaid
flowchart LR
    K["django-service-specs<br/><i>declare once</i>"]
    K --> R["spec-rest<br/>REST"]
    K --> H["spec-html<br/>HTML + htmx"]
    K --> C["spec-cli<br/>manage.py"]
    K --> T["spec-tasks<br/>background"]
    K --> M["spec-mcp<br/>MCP"]
    M --> A["spec-agents<br/>Pydantic-AI host"]
    K --> A
    A --> U["django-ag-ui<br/>AG-UI endpoint"]
    U --> W["agents-web-components<br/>&lt;ag-ui-chat&gt;"]
    U --> D["django-admin-agent<br/>admin sidebar"]
    W --> D
```

| Package | What it does | Release |
| --- | --- | --- |
| [django-service-specs](https://github.com/Artui/django-service-specs) | The kernel: declare an operation once, dispatch it from any transport | ![PyPI](https://img.shields.io/pypi/v/django-service-specs?style=flat-square&label=&color=3776AB) |
| [django-spec-rest](https://github.com/Artui/django-spec-rest) | Specs over HTTP with Django REST Framework | ![PyPI](https://img.shields.io/pypi/v/django-spec-rest?style=flat-square&label=&color=3776AB) |
| [django-spec-html](https://github.com/Artui/django-spec-html) | Specs as server-rendered pages, HTML first and htmx-capable | ![PyPI](https://img.shields.io/pypi/v/django-spec-html?style=flat-square&label=&color=3776AB) |
| [django-spec-cli](https://github.com/Artui/django-spec-cli) | Specs as `manage.py` subcommands, options generated from parameters | ![PyPI](https://img.shields.io/pypi/v/django-spec-cli?style=flat-square&label=&color=3776AB) |
| [django-spec-mcp](https://github.com/Artui/django-spec-mcp) | Specs to agents over the Model Context Protocol | ![PyPI](https://img.shields.io/pypi/v/django-spec-mcp?style=flat-square&label=&color=3776AB) |
| [django-spec-tasks](https://github.com/Artui/django-spec-tasks) | Specs as background tasks with a durable run record | ![PyPI](https://img.shields.io/pypi/v/django-spec-tasks?style=flat-square&label=&color=3776AB) |
| [django-spec-agents](https://github.com/Artui/django-spec-agents) | A Django agent host for Pydantic-AI, with specs as tools | ![PyPI](https://img.shields.io/pypi/v/django-spec-agents?style=flat-square&label=&color=3776AB) |
| [django-ag-ui](https://github.com/Artui/django-ag-ui) | An AG-UI agent endpoint for Django | ![PyPI](https://img.shields.io/pypi/v/django-ag-ui?style=flat-square&label=&color=3776AB) |
| [agents-web-components](https://github.com/Artui/agents-web-components) | A framework-free `<ag-ui-chat>` web component: a drop-in chat sidebar with client-side tools | ![npm](https://img.shields.io/npm/v/@artooi/agents-web-components?style=flat-square&label=&color=CB3837) |
| [django-admin-agent](https://github.com/Artui/django-admin-agent) | A chat-agent sidebar inside the Django admin | ![PyPI](https://img.shields.io/pypi/v/django-admin-agent?style=flat-square&label=&color=3776AB) |

See it all working together in **[django-agent-examples](https://github.com/Artui/django-agent-examples)**: one Django backend, one agent, five frontends (React, Vue, Svelte, Angular and the Django admin).

## Standalone Django libraries

| Package | What it does | Release |
| --- | --- | --- |
| [django-domain-events](https://github.com/Artui/django-domain-events) | A domain-event log with a durable outbox, per-receiver retry and dead-letter | ![PyPI](https://img.shields.io/pypi/v/django-domain-events?style=flat-square&label=&color=3776AB) |
| [django-outbound-webhooks](https://github.com/Artui/django-outbound-webhooks) | Customer-facing webhooks with Standard Webhooks signing | ![PyPI](https://img.shields.io/pypi/v/django-outbound-webhooks?style=flat-square&label=&color=3776AB) |
| [django-query-contract](https://github.com/Artui/django-query-contract) | Catch N+1s, query growth and bad plans at test time | ![PyPI](https://img.shields.io/pypi/v/django-query-contract?style=flat-square&label=&color=3776AB) |
| [django-data-shape](https://github.com/Artui/django-data-shape) | A realistically shaped test database from your models, loaded by `COPY` | ![PyPI](https://img.shields.io/pypi/v/django-data-shape?style=flat-square&label=&color=3776AB) |
| [django-tiptap-editor](https://github.com/Artui/django-tiptap-editor) | A drop-in TipTap rich-text editor for Django forms and admin | ![PyPI](https://img.shields.io/pypi/v/django-tiptap-editor?style=flat-square&label=&color=3776AB) |

**Also:** [go-services](https://github.com/Artui/go-services), the same declare-once idea for Go, and [held-back-check](https://github.com/Artui/held-back-check), a GitHub Action that says which dependency holds another below its newest release.

## How I work

<p>
  <img src="https://img.shields.io/badge/coverage-100%25%20line%20%2B%20branch-2ea44f?style=for-the-badge" alt="100% coverage">
  <img src="https://img.shields.io/badge/types-ty-3776AB?style=for-the-badge" alt="ty">
  <img src="https://img.shields.io/badge/lint-ruff-D7FF64?style=for-the-badge&logo=ruff&logoColor=black" alt="ruff">
  <img src="https://img.shields.io/badge/docs-MkDocs-526CFE?style=for-the-badge&logo=materialformkdocs&logoColor=white" alt="MkDocs">
</p>

A fix lands with the test that failed before it.

## Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Artui&theme=transparent" height="160" alt="GitHub stats">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Artui&theme=transparent" height="160" alt="Repositories per language">
  <img src="https://streak-stats.demolab.com?user=Artui&hide_border=true&background=00000000&ring=3776AB&fire=3776AB&currStreakLabel=3776AB&currStreakNum=3776AB&sideNums=8b949e&sideLabels=8b949e&dates=8b949e&stroke=8b949e" height="160" alt="Contribution streak">
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Artui/Artui/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/Artui/Artui/output/github-snake.svg" width="100%" alt="Contribution graph eaten by a snake">
</picture>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:3776AB,100:092E20&height=110&section=footer" width="100%" alt="">
