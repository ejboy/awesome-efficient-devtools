# Contributing

Local-first, small, composable, and single-purpose tools are preferred, but these are preferences rather than strict requirements.

Submissions are welcome when a tool has a clear, meaningful efficiency story. Good reasons for inclusion include reducing:

* CPU, RAM, disk, or network requirements
* AI, token, or context overhead
* command or build noise
* infrastructure requirements
* setup complexity
* repetitive work
* workflow friction

A trivial convenience alone is not necessarily enough; the benefit should be meaningful enough to justify recommending the tool. The tool should also have a resource footprint proportionate to its job and should not undermine its own efficiency story with excessive background processes, memory, CPU, network activity, or infrastructure. There are no arbitrary CPU, RAM, binary-size, star, download, maintainer-count, or similar thresholds. Some reasonable evidence that it is lightweight is expected, whether from its architecture, implementation, documentation, measurements, direct inspection, or credible user experience; formal benchmarks are not required.

### Deployment simplicity

For self-hosted services, we strongly prefer tools that can run as a single process with minimal external dependencies.

Small multi-process architectures are acceptable when they serve a clear purpose, such as distributed monitoring.

Tools requiring separate database servers, application services, or background workers face a higher bar for inclusion. A smaller footprint than an enterprise alternative is not sufficient by itself; the tool should demonstrate a meaningful reduction in operational complexity or resource usage.

Trust and safety are part of this editorial screening. Do not include software that appears deceptive, suspicious, malicious, privacy-invasive, scammy, or unsafe, including open-source software. Consider unexpected telemetry or tracking, unnecessary data collection or transmission, credential handling, installers or update mechanisms, misleading claims, bundled software or unrelated background services, and obvious security or privacy concerns. This is an editorial standard, not a formal security audit or certification.

Projects should be usable today, maintained enough to recommend, reasonably documented, and not obviously abandoned or broken. Early-stage projects may still qualify when their efficiency idea or implementation is particularly compelling, subject to the AI-Assisted Development requirements below.

Non-AI categories have no minimum project age. A new project can qualify when its usefulness and efficiency are already clear. New submissions to AI-Assisted Development must meet the minimum repository age below. However, projects built around very new, rapidly emerging, or highly speculative tool categories may need stronger evidence of durable real-world usefulness before inclusion. Early attention, launch-driven adoption, or novelty alone is not enough; the goal is to recommend tools whose value can be meaningfully evaluated rather than catalog every new trend.

## AI-Assisted Development

This category focuses on tools that make **human software developers more efficient when working with AI assistants**. It is not a general directory of AI agents, autonomous agent platforms, or AI infrastructure.

Because of the volume and rapid churn of AI projects, additional criteria apply to new submissions in this category.

### Human-centered development

The tool must primarily improve a human developer's workflow.

Examples include tools that help developers prepare context, direct AI assistants, inspect their actions, review results, debug failures, or understand resource and token usage.

Tools primarily focused on autonomous agent orchestration, agent-to-agent coordination, managing AI agent fleets, or general-purpose AI workforces are outside this category's scope.

Developers should retain meaningful visibility and control over the workflow. This does not require manual approval of every operation.

### Minimum project age

The project's GitHub repository must have been created at least **30 days before the pull request is submitted**.

This is a minimum cooling-off period intended to discourage immediate submissions of newly generated or experimental projects. It is not a measure of quality or maturity by itself.

There are no minimum GitHub star, fork, or download requirements.

### Demonstrable efficiency improvement

Submissions must demonstrate a concrete improvement to a developer workflow.

The PR description should explain:

1. **Problem:** What specific overhead or inefficiency does the tool address?
2. **Baseline:** How is the task normally accomplished without the tool?
3. **Improvement:** What becomes faster, simpler, cheaper, or less resource-intensive?
4. **Evidence:** What supports the improvement claim?

Evidence may include measurements, before-and-after examples, reproducible workflows, or implementation details that clearly explain the efficiency gain.

Examples include reducing token consumption, execution time, resource usage, duplicated configuration, manual steps, or operational complexity.

Formal benchmarks are not required. However, generic claims such as "boosts productivity," "streamlines workflows," or "supports multiple AI agents" are not sufficient without a concrete efficiency argument.

Meeting these requirements does not guarantee inclusion. The general contribution criteria, including differentiation, usability, maintenance, and trust and safety, continue to apply.

### Existing entries

These additional criteria apply prospectively to submission PRs opened after this policy takes effect. Previously accepted projects are not automatically removed or reconsidered, and PRs already open when the policy takes effect are unaffected. Historical inclusions that fall outside the narrower category scope may be identified in the README.

## Editorial and submission policies

Entries are maintained alphabetically by display name within each category.

This list is curated, not exhaustive: meeting the basic criteria does not guarantee inclusion. When several tools solve substantially the same problem, prefer the strongest default or tools that are meaningfully differentiated rather than listing every alternative.

Open-source tools are preferred. When two tools solve essentially the same problem to a similar standard, prefer the strong open-source option. Closed-source or paid software can still deserve inclusion when it is unusually good, trustworthy, lightweight, or meaningfully differentiated. The bar is higher for these tools, and there should generally be enough independent evidence of quality, adoption, or established usefulness to justify recommending them over, or alongside, strong open-source alternatives.

This list is editorial, and inclusion is ultimately at the maintainer's discretion. In a submission, disclose whether you are the author, maintainer, employee, sponsor, or otherwise affiliated with the project.

Affiliated submissions are welcome and are evaluated using the same criteria as any other submission. Disclosure neither disqualifies nor favors a project.

### Ongoing curation

This list is periodically reviewed to keep it useful and relevant.

Projects that appear abandoned or are no longer maintained may be reconsidered for inclusion. However, inactivity alone is not grounds for removal. Stable tools can remain valuable without frequent updates, especially when they continue to serve a real need in the developer ecosystem.

There is no automatic inactivity cutoff or removal schedule. Decisions are made case by case, considering the project's usability, relevance, and continued value to developers.

**Any removal must be documented in an explicit commit message explaining the reason.** Projects will not be silently removed from the list.

### PR authorship

Pull requests must be authored by the person submitting them. Do not list AI tools (such as Claude, ChatGPT, or Copilot) as co-authors or add AI `Co-Authored-By` trailers. Pull requests with AI tools credited as co-authors will be rejected; you are the author and are responsible for your submission.

If you find this list useful, consider starring the repository. It helps more developers discover the project, but is never required for contributing or inclusion.
