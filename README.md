# 🤖 AI Agent Prompts Directory

This directory contains comprehensive prompt templates and agent instructions that power complex AI agent orchestration systems. Each prompt is carefully designed for specific workflows, ensuring consistent behavior across different agent interactions.

## 📁 Directory Structure

### `agents/` - Specialized Agent Directory
**Comprehensive collection of specialized AI agents for domain-specific tasks**

This directory contains 25+ specialized agents organized by expertise area, from development and research to business operations and creative work. Each agent is designed for specific workflows and can be invoked through various AI platforms.

**📖 [See detailed agents README](agents/README.md)** for complete descriptions of all agents, usage guidelines, and integration instructions across different platforms (Cursor, Claude Code, Gemini, etc.)

**Key Agent Categories:**
- **Core Development**: Project orchestration, QA, implementation
- **Research & Analysis**: Technical research, gap analysis, strategic intelligence
- **Business Operations**: Executive coordination, financial planning, marketing
- **Creative & Design**: UX design, content creation, innovation
- **Technical Infrastructure**: Data analysis, security, tooling, networking

### `creation/` - Artifact Creation Templates
Prompts for generating structured documents and artifacts:

- **`CREATE-AUDITABLE-RECORD.md`** - Generates comprehensive audit trails and compliance documentation with full traceability
- **`CREATE-FEATURE-REQUEST.md`** - Captures detailed feature requirements and specifications for development
- **`CREATE-WORK-PROPOSAL.md`** - Creates detailed work proposals with scope, timeline, and resource requirements

### `general/` - Core Workflow Prompts
Essential prompts for common agent operational workflows:

- **`autonomous-mode-now.md`** - Autonomous engineering mode for independent task completion with documentation-first approach
- **`verify-previous-work.md`** - Skeptical verification of work claims with concrete evidence requirements
- **`prepare-work-for-review.md`** - Packages completed work for peer review with full context and documentation
- **`review-my-plan.md`** - Prepares implementation plans for review before execution begins
- **`do-you-know-what-to-do-next.md`** - Autonomous task progression and state assessment for ongoing work

### `handoffs/` - Work Transfer Protocols
Standardized handoff templates for seamless agent-to-agent work transfers:

- **`HANDOFF.md`** - Standard handoff protocol for routine work transfers
- **`HANDOFF-MINIMAL.md`** - Lightweight handoff for simple, quick transfers
- **`HANDOFF-DETAILED.md`** - Comprehensive handoff with full context, risks, and next steps

### `modes/` - Behavioral Mode Definitions
Special operational modes that change agent behavior:

- **`DISCUSSION-MODE.md`** - Read-only analysis mode for planning, discussion, and theoretical exploration without code changes

### `research/` - Research & Investigation
Specialized prompts for research workflows:

- **`deep-research-prompt-generator.md`** - Transforms research briefs into comprehensive, multi-model research prompts with complexity assessment and execution guidance

### `work-orders/` - Work Order Lifecycle
Complete work order management system:

- **`CREATE-WORK-ORDER.md`** - Generates self-contained, executable work orders with complete context
- **`EXECUTE-WORK-ORDER.md`** - Executes work orders with progress tracking and validation
- **`WORK-ORDER-INDEX.md`** - Maintains work order registries and tracking

### `archive/` - Legacy & Backup Files
Historical artifacts and migration backups (not actively used):
- Migration manifests and backup files from system evolution

## 🚀 Usage Context

These prompts power complex AI agent orchestration systems and are referenced by:

- **AGENTS.md** - Central system configuration and agent definitions
- **Project tracking** - Work order and session management
- **Mode orchestration** - Dynamic behavior switching
- **Work order execution** - Structured task completion pipelines

### When to Use Each Category:

| Category | Use Case |
|----------|----------|
| **agents/** | Define specialized agent roles for specific domains |
| **creation/** | Generate structured documents and proposals |
| **general/** | Handle common development and review workflows |
| **handoffs/** | Transfer work between agents or sessions |
| **modes/** | Change agent behavior for specific contexts |
| **research/** | Conduct deep research and investigation |
| **work-orders/** | Manage structured, trackable work execution |

## 📝 Adding New Prompts

### Process:
1. **Choose Category** - Select the most appropriate subdirectory based on the prompt's primary function
2. **Naming Convention** - Use clear, descriptive names: `ACTION-OBJECT.md` or `ROLE-NAME.md`
3. **Documentation** - Add the new prompt to this README with a clear description
4. **Integration** - Update AGENTS.md if the prompt needs system-wide references

### Quality Guidelines:
- **Purpose-driven** - Each prompt should serve a specific, well-defined function
- **Self-contained** - Include all necessary context and instructions
- **Consistent** - Follow established patterns and formatting
- **Testable** - Should produce predictable, reliable results

## 🔗 Integration Points

These prompts integrate with the broader AI agent infrastructure:

- **AGENTS.md** - Central configuration and mode definitions
- **Project tracking** - Work order and session management
- **Submodule system** - Private repository for prompt management
- **Mode orchestration** - Dynamic behavior switching
- **Audit trails** - Comprehensive work documentation

## 🔄 Sync Management

This directory is synchronized with a private agents-prompts repository. To update the prompts:

```bash
cd docs/team/prompts
git pull origin main  # Get latest from your private repo
```

This keeps your local prompt developments in sync with your private repository.
