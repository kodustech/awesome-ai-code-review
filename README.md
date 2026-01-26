# Awesome AI Code Reviews [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of AI-powered tools, agents, and platforms dedicated to automating code reviews, enforcing guidelines, and improving software quality.

> **Maintainer Note:** This list is curated and maintained by the engineering team at **[Kodus](https://kodus.io)**. We love open source and building better devtools.

## Contents

- [Automated PR Agents](#automated-pr-agents)
- [IDE Assistants & Copilots](#ide-assistants--copilots)
- [Research & Benchmarks](#research--benchmarks)
- [Security & Static Analysis AI](#security--static-analysis-ai)
- [CLI & Local Workflows](#cli--local-workflows)
- [Open Source Models](#open-source-models-for-code)
- [Benchmarks](#benchmarks)

---

## Automated PR Agents

_Tools that connect directly to GitHub/GitLab to review Pull Requests, comment on code, and suggest fixes asynchronously._

_Note: This list is not intended to compare tools; as maintainers of Kodus, we are biased._

- **[Kodus](https://kodus.io)** (⭐ _Maintainer_)  
  An AI code review agent focusing on high-signal feedback. It allows teams to define custom review guidelines (using plain English) to enforce architectural patterns and best practices, reducing noise in the review process.

- **[CodeRabbit](https://coderabbit.ai)** Provides line-by-line feedback on pull requests and generates summaries of changes. Features a chat interface within the PR to discuss the feedback with the AI.

- **[Greptile](https://greptile.com)** An AI engine that indexes the entire codebase to understand context. It focuses on answering complex questions about the repo and reviewing code with full-repository awareness.

- **[Zenable](https://zenable.io)** AI guardrails that learn your team's standards and ensure coding agents follow them. Works across IDE (via MCP), pre-commit, and PR review to catch bugs and security issues in AI-generated code in real-time.

- **[Cursor Bugbot](https://cursor.com/bugbot)** AI-powered PR review that runs automatically to catch real bugs and security issues with a low false-positive rate.

## IDE Assistants & Copilots

_Tools that integrate with editors or local environments for autocomplete, chat, and agentic coding._

- **[GitHub Copilot](https://github.com/features/copilot)** - The standard AI pair programmer for autocomplete, chat, and inline edits.
- **[Cursor](https://cursor.com)** - AI-first code editor with built-in chat, autocomplete, and agent workflows.
- **[Claude Code](https://claude.com/product/claude-code)** - Claude's coding agent for terminal, IDE, and web workflows that can manage large codebases and implement changes.
- **[OpenAI Codex](https://developers.openai.com/codex/ide)** - OpenAI's coding agent that can read, modify, and run code, available as a VS Code extension with optional cloud delegation.
- **[Google Antigravity](https://antigravity.google)** - Agent-first IDE with tab autocomplete, natural language commands, and cross-surface agents across editor, terminal, and browser.
- **[Kilo Code](https://kilo.ai)** - Open-source agentic engineering platform with IDE/CLI support, tab autocomplete, and multi-agent orchestration.
- **[Cline](https://github.com/cline/cline)** - Autonomous IDE agent that can create/edit files, run commands, and use the browser with user approval.
- **[OpenCode](https://opencode.ai)** - Open-source coding agent for terminal, IDE, or desktop with multi-session workflows and broad model support.

## Key Research & Papers

_Fundamental reading on how LLMs are transforming software engineering._

- **[AI-Assisted Assessment of Coding Practices in Modern Code Review](https://arxiv.org/abs/2405.13565)**: LLM-based system for enforcing coding best practices in code review.

- **[Towards Practical Defect-Focused Automated Code Review](https://arxiv.org/abs/2505.17928)**: Automation pipeline for defect detection in C++ codebases using AI.

- **[Automated Code Review Using Large Language Models at Ericsson: An Experience Report](https://arxiv.org/abs/2507.19115)**: LLM tool with static analysis for code review in industry.

- **[DeputyDev -- AI Powered Developer Assistant: Breaking the Code Review Logjam through Contextual AI to Boost Developer Productivity](https://arxiv.org/abs/2508.09676)**: AI assistant for efficient code reviews to boost productivity.

- **[CRScore++: Reinforcement Learning with Verifiable Tool and AI Feedback for Code Review](https://arxiv.org/abs/2506.00296)**: RL framework for improving code review comment generation.

- **[Leveraging Reviewer Experience in Code Review Comment Generation](https://arxiv.org/pdf/2409.10959)**: Integrating reviewer experience into AI models for comment generation.

- **[A Survey on Machine Learning Techniques for Source Code Analysis](https://export.arxiv.org/pdf/2110.09610v2)**: Overview of ML applications in source code tasks including review.

- **[BitsAI-CR: Automated Code Review via LLM in Practice](https://conf.researchr.org/details/fse-2025/fse-2025-industry-papers/24/BitsAI-CR-Automated-Code-Review-via-LLM-in-Practice)**: Practical LLM-based automated code review in large-scale environments.

- **[AutoCodeRover: Autonomous Program Improvement](https://arxiv.org/abs/2404.05427v1)**: LLM for program improvement via code review and repair.

- **[Prompting and Fine-tuning Large Language Models for Automated Code Review Comment Generation](https://arxiv.org/abs/2411.10129)**=: Fine-tuning LLMs with QLoRA for generating accurate code review comments.

- **[Fine-Tuning Large Language Models to Improve Accuracy and Comprehensibility of Automated Code Review](https://dl.acm.org/doi/10.1145/3695993)**: Enhancing LLM accuracy and comprehensibility in automated code reviews.

 **[Lessons from Building Static Analysis Tools at Google](https://cacm.acm.org/magazines/2018/4/226371-lessons-from-building-static-analysis-tools-at-google/fulltext)**: Why low false-positive rates are crucial (validating the need for specialized agents).


## Security & Static Analysis AI

_Tools focusing specifically on vulnerabilities and SAST (Static Application Security Testing)._

- **[Snyk DeepCode](https://snyk.io/platform/deepcode-ai/)** - AI-powered engine to find security flaws faster than traditional static analysis.
- **[Semgrep AI](https://semgrep.dev)** - Combines rule-based static analysis with AI to reduce false positives in security scanning.

## CLI & Local Workflows

_Command-line tools for local reviews and "hacker" workflows._

- **[Aider](https://github.com/paul-gauthier/aider)** - AI pair programming in your terminal.
- **[Mentat](https://github.com/biobootloader/mentat)** - Coordinate edits across multiple files using command line.
- **[OpenCommit](https://github.com/di-sukharev/opencommit)** - Generates semantic git commit messages automatically.


## Benchmarks
- **[Code Review Benchmark](https://codereviewbench.com/)**: Comprehensive evaluation of LLM performance in AI-powered code review tasks.
- **[SWE-bench](https://www.swebench.com/)** - Evaluation framework for language models on real-world software engineering issues.
- **[HumanEval](https://github.com/openai/human-eval)** - OpenAI's dataset for evaluating code generation capabilities.

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.
If you are a founder or maintainer of a tool listed here and want to update your description, feel free to open a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
