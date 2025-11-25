# 🤖 AI Agent Prompts Directory

This directory contains comprehensive prompt templates and agent instructions that power the entire AI agent orchestration system. Each prompt is carefully designed for specific workflows, ensuring consistent behavior across different agent interactions.

## 📁 Directory Structure

### `agents/` - Specialized Agent Roles
Individual agent role definitions for specific domains and functions:

**Core Engineering Agents:**
- `agent-dev-general-contractor.md` - Oversees large-scale development projects and coordinates multiple agents
- `agent-dev-overseer.md` - Manages development workflows and quality assurance
- `agent-dev-worker.md` - Executes specific development tasks and implementation work
- `agent-orchestrator.md` - Coordinates multiple agents and manages complex workflows
- `agent-software-product-builder.md` - Builds complete software products from concept to deployment

**Analysis & Intelligence:**
- `agent-data-analysis-visualization.md` - Analyzes data and creates visualizations
- `agent-document-analysis-audit.md` - Performs detailed document analysis and auditing
- `agent-research-analysis.md` - Conducts research and analysis tasks
- `agent-research-gap-analysis.md` - Identifies gaps in research and knowledge
- `agent-strategic-intelligence.md` - Provides strategic analysis and insights

**Business & Operations:**
- `agent-chief-of-staff.md` - Executive coordination and strategic planning
- `agent-chief-reality-officer.md` - Ensures realistic assessments and feasibility analysis
- `agent-financial-analysis-planning.md` - Financial analysis and planning
- `agent-marketing-expert.md` - Marketing strategy and execution
- `agent-project-coordinator.md` - Project management and coordination

**Process & Quality:**
- `agent-process-analysis-retrospective.md` - Analyzes processes and retrospectives
- `agent-process-analysis-retrospective-quick.md` - Quick process analysis and feedback
- `agent-process-design-optimization.md` - Designs and optimizes processes
- `agent-testing-validation.md` - Testing and validation workflows
- `agent-security-compliance.md` - Security and compliance management

**Creative & Communication:**
- `agent-communication-stakeholder.md` - Stakeholder communication and management
- `agent-content-crafting-alignment.md` - Content creation and alignment
- `agent-innovation-ideation.md` - Innovation and idea generation
- `agent-ux-design.md` - User experience design and interface design

**Support & Infrastructure:**
- `agent-learning-knowledge-management.md` - Knowledge management and learning systems
- `agent-synthesis-integration.md` - Synthesizes information and integrates systems
- `agent-tooling.md` - Tool development and infrastructure
- `NETWORK-DIAGNOSTICS-SPECIALIST.md` - Network diagnostics and troubleshooting

**Reference Materials:**
- `claude-code-agent-format-guide.md` - Formatting guidelines for Claude Code agents

---

### `creation/` - Artifact Creation Templates
Prompts for generating structured documents and artifacts:

- **`CREATE-AUDITABLE-RECORD.md`** - Generates comprehensive audit trails and compliance documentation with full traceability
- **`CREATE-FEATURE-REQUEST.md`** - Captures detailed feature requirements and specifications for development
- **`CREATE-WORK-PROPOSAL.md`** - Creates detailed work proposals with scope, timeline, and resource requirements

---

### `general/` - Core Workflow Prompts
Essential prompts for common agent operational workflows:

- **`autonomous-mode-now.md`** - Autonomous engineering mode for independent task completion with documentation-first approach
- **`verify-previous-work.md`** - Skeptical verification of work claims with concrete evidence requirements
- **`prepare-work-for-review.md`** - Packages completed work for peer review with full context and documentation
- **`review-my-plan.md`** - Prepares implementation plans for review before execution begins
- **`do-you-know-what-to-do-next.md`** - Autonomous task progression and state assessment for ongoing work

---

### `handoffs/` - Work Transfer Protocols
Standardized handoff templates for seamless agent-to-agent work transfers:

- **`HANDOFF.md`** - Standard handoff protocol for routine work transfers
- **`HANDOFF-MINIMAL.md`** - Lightweight handoff for simple, quick transfers
- **`HANDOFF-DETAILED.md`** - Comprehensive handoff with full context, risks, and next steps

---

### `modes/` - Behavioral Mode Definitions
Special operational modes that change agent behavior:

- **`DISCUSSION-MODE.md`** - Read-only analysis mode for planning, discussion, and theoretical exploration without code changes

---

### `research/` - Research & Investigation
Specialized prompts for research workflows:

- **`DEEP-RESEARCH-CURSOR-MCP-PLAYWRIGHT.md`** - Advanced research workflows using Cursor IDE tools and browser automation

---

### `work-orders/` - Work Order Lifecycle
Complete work order management system:

- **`CREATE-WORK-ORDER.md`** - Generates self-contained, executable work orders with complete context
- **`EXECUTE-WORK-ORDER.md`** - Executes work orders with progress tracking and validation
- **`WORK-ORDER-INDEX.md`** - Maintains work order registries and tracking

---

### `archive/` - Legacy & Backup Files
Historical artifacts and migration backups (not actively used):
- Migration manifests and backup files from system evolution

---

## 🚀 Usage Context

These prompts power the entire AI agent orchestration system and are referenced by:

- **AGENTS.md** - Main system configuration and agent definitions
- **Mode definitions** in `~/.agents/modes/` - Behavioral mode implementations
- **Agent orchestration scripts** - Automated agent coordination workflows
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

---

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

---

## 🔗 Integration Points

These prompts integrate with the broader AI agent infrastructure:

- **AGENTS.md** - Central configuration and mode definitions
- **Project tracking** - Work order and session management
- **Submodule system** - Private repository for prompt management
- **Mode orchestration** - Dynamic behavior switching
- **Audit trails** - Comprehensive work documentation

