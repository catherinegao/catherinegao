# Qing Gao

Software Engineer with extensive experience building enterprise-scale React applications for telecom and education. Owns the shared React and TypeScript UI libraries that power Nokia's WaveSuite NMS across multiple repositories and release branches, and architected the real-time event-channel layer supporting dozens of live UI surfaces. Expert in React, TypeScript, Redux, real-time systems, WCAG 2.x accessibility, and AI-assisted development. Seeking to leverage this background to deliver high-quality, scalable front-end solutions that drive customer success. 

## What's public here

Most of my 8+ years of professional work lives in Nokia's private enterprise
GitLab, including two shared React + TypeScript UI libraries I sole-maintain
across the WaveSuite product suite. This GitHub is where I publish sanitized,
generalized versions of the patterns I work with day to day.

### Featured project

🛠 **[mcp-server-frontend-context](https://github.com/catherinegao/mcp-server-frontend-context)**

A Model Context Protocol (MCP) server that exposes frontend-project context —
component inventory, framework detection, conventions, in-repo examples —
to LLM agents like Cursor and Claude Desktop. Built to make AI-assisted
engineering more grounded: instead of letting the agent guess what your
project looks like, this server tells it. The public counterpart to the MCP
server I built for my team at Nokia.

`TypeScript` · `Node.js` · `@modelcontextprotocol/sdk` · `vitest` ·
`GitHub Actions CI`

## What I work on

- **Component libraries and design systems** — the architecture that lets a
  small shared surface scale across many product teams without duplicating
  UI code
- **Data-visualization-heavy frontends** — Highcharts as the primary engine,
  plus ECharts, D3.js, interactive SVG, and HTML5 Canvas across the full
  chart spectrum (line, bar, stacked, gauge, heatmap, time-series,
  network-topology), with vector-preserving Image/SVG/PDF export pipelines
  built on top of Highcharts' SVG output
- **AI-assisted engineering** — Cursor, GitHub Copilot, custom MCP servers,
  agentic workflow patterns (plan mode, tool-using agents, multi-step
  orchestration), prompt engineering, audit-tagged commits, and
  human-in-the-loop review for regulated codebases
- **Web performance for data-heavy dashboards** — memoization, list
  virtualization, Redux store normalization, code splitting, tree shaking,
  lazy loading, bundle-size optimization
- **Legacy modernization** — most recently migrating a Dojo Toolkit
  application onto modern React, Redux, and TypeScript without regressing
  tier-1 customer deployments
- **GitHub Actions CI/CD and code-merge quality gates** — PR validation,
  branch-merge gating, lint / type-check / unit / build verification across
  7 repositories and 15+ concurrent long-lived release branches

## Stack at a glance

**Languages.** TypeScript, JavaScript (ES6+), Python, Java, HTML5, CSS3, SQL.

**Frontend.** React 16/17/18 (Hooks, Context, Suspense), Redux + Redux
Toolkit, React Router, React Hook Form, React-Dazzle, AG Grid (enterprise),
MUI, Tailwind CSS, styled-components.

**Data viz.** Highcharts, ECharts, D3.js, interactive SVG, HTML5 Canvas;
jspdf + svg2pdf.js for vector PDF/SVG export.

**Tooling.** Webpack, Vite, Babel, ESLint, Prettier; Jest, React Testing
Library, Cypress, vitest, Storybook + MSW; npm, yarn, semver.

**CI/CD.** GitHub Actions, Jenkins, GitLab CI, Docker (build, run, debug,
multi-stage).

**Backend.** Python + Flask with OWASP-aligned secure coding and pytest;
Node.js, REST + JSON; prior Java with Spring MVC, Hibernate, Oracle, Maven.

**AI / LLM.** Cursor, GitHub Copilot, Model Context Protocol (MCP),
agentic workflow patterns, prompt and context engineering, LLM guardrails
and human-in-the-loop review.

## Reach out

If you're working on data-dense visualization, AI-assisted developer
tooling, component-library architecture, or large-codebase modernization,
I'd love to talk.
