# AI Development Task Tracker Template

A phase-based, AI-optimized template for planning and tracking feature/product development with concrete tasks, file paths, and acceptance criteria designed for independent execution by AI assistants.

## 🎯 What is this template?

This AI Development Task Tracker Template is designed to break down complex features/products into phased development with concrete, executable tasks. Each task includes specific implementation details, file paths, and acceptance criteria that allow AI assistants (like Claude, GPT-4, etc.) to work independently while maintaining clear progress tracking for human teams.

## 📋 Template Structure

The template follows a phase-based approach with:

1. **Mission Critical Context** - Core business value in one bold sentence
2. **Overall Progress Tracker** - At-a-glance status of all phases
3. **Phase 0-2 Templates** - Structured phases with:
   - **Phase Setup** - Branch creation, PR setup, project tracking
   - **Main Tasks** - Concrete objectives with specific subtasks
   - **Exit Criteria** - Binary checkpoints for phase completion
4. **LLM Extension Prompt** - Instructions for AI to add additional phases

Each phase includes:
- Strategic focus and timeline estimates
- Git branch naming conventions
- 3-4 main tasks with concrete subtasks
- File paths and commands where applicable
- Progress tracking reminders
- Clear exit criteria with version tags

## 🚀 How to Use This Template

### For Humans

1. **Copy the template** - Start with `FEATURE_PLAN_TEMPLATE.md`
2. **Define the mission** - Write one bold sentence clarifying core business value
3. **Plan phases** - Break work into 2-5 week phases
4. **Create concrete tasks** - Include specific file paths, commands, and tools
5. **Track progress** - Check off tasks as completed, update phase status
6. **Use version control** - Create branches and PRs as specified
7. **Extend as needed** - Use the LLM prompt to add more phases

### For AI Assistants

1. **Independent execution** - Each task is designed for autonomous completion
2. **Follow structure** - Maintain the exact phase/task/subtask hierarchy
3. **Update tracking** - Always end tasks with "Update progress in task tracker and commit changes"
4. **Be concrete** - Include specific file paths, commands, and implementation details
5. **Respect phases** - Complete current phase before moving to next
6. **Extend systematically** - When adding phases, follow the template exactly
7. **Version properly** - Use semantic versioning for phase releases

## 🎨 Customization Tips

### For Different Project Types

- **New Features**: Use 3-4 phases with comprehensive tasks
- **API Development**: Focus on endpoint definitions, types, and tests
- **UI/UX Implementation**: Include component paths and state management
- **Infrastructure Setup**: Add deployment commands and configuration files
- **Migration Projects**: Phase by data/system migration steps
- **Refactoring**: Break into safe, incremental transformation phases

### Scaling the Template

- **Small Features** (< 2 weeks): Use Phase 0 only with 2-3 tasks
- **Medium Features** (2-6 weeks): Use Phases 0-1 with standard structure
- **Large Features** (6-12 weeks): Use all phases plus LLM extension
- **Programs** (> 3 months): Create multiple linked templates with dependencies

## 🤝 Best Practices

### Writing Effective Task Plans

1. **One objective per task** - Keep tasks focused and measurable
2. **Concrete subtasks** - Include file paths, not abstract descriptions
3. **Binary exit criteria** - Clear yes/no checkpoints
4. **Realistic timelines** - Account for testing and review
5. **Git workflow** - Always specify branches and PR strategies
6. **Progress commits** - Regular updates to track advancement
7. **AI-friendly details** - Provide context an AI needs to work independently

### AI Collaboration Tips

1. **Complete context** - Include all needed info in the task description
2. **File paths** - Always specify exact locations for code changes
3. **Command examples** - Provide actual commands to run
4. **Test specifications** - Define what tests to write/run
5. **Dependencies** - List required packages/APIs upfront
6. **Acceptance criteria** - Make success measurable and clear
7. **Version control** - Specify commit message formats

## 💡 Example Use Cases

- **Authentication System**: Phase 0 (Setup), Phase 1 (Core Auth), Phase 2 (Advanced Features)
- **Payment Integration**: Phase 0 (PSP Setup), Phase 1 (Checkout), Phase 2 (Subscriptions)
- **Mobile App Feature**: Phase 0 (UI), Phase 1 (State), Phase 2 (API Integration)
- **Database Migration**: Phase 0 (Schema), Phase 1 (Data), Phase 2 (Cutover)
- **API Development**: Phase 0 (Core Endpoints), Phase 1 (Auth), Phase 2 (Advanced)
- **CI/CD Pipeline**: Phase 0 (Build), Phase 1 (Test), Phase 2 (Deploy)

## 🔧 Integration with Tools

This template integrates with:

- **Version Control**: GitHub/GitLab (branches, PRs, releases as specified)
- **Project Tracking**: GitHub Projects, Jira (milestones match phases)
- **CI/CD**: Automated via git tags (v0.x.y per phase)
- **AI Assistants**: Claude, GPT-4, Copilot (can execute tasks independently)
- **Documentation**: Markdown renders in all modern tools
- **IDE Integration**: VS Code task runner, IntelliJ TODOs

## ✨ Benefits

### For Development Teams
- **Clear phases** with specific deliverables and timelines
- **Concrete tasks** that can be assigned and tracked
- **Progress visibility** through checkbox tracking
- **Git workflow** integration with branches and releases

### For AI Assistants
- **Independent execution** capability for each task
- **Specific implementation** details and file paths
- **Clear acceptance** criteria for task completion
- **Extensibility** through structured prompts

### For Project Managers
- **Phase-based planning** with clear milestones
- **Progress tracking** at task and phase level
- **Risk mitigation** through exit criteria
- **Version control** with semantic versioning

### For Stakeholders
- **Transparent progress** with overall tracker
- **Predictable delivery** through phased approach
- **Quality gates** via exit criteria
- **Clear documentation** of what's being built

## 📂 Repository Contents

- `FEATURE_PLAN_TEMPLATE.md` - The main template file
- `examples/` - Sample completed plans for reference
- `LICENSE` - MIT license for open source use

## 🤔 Contributing

Contributions are welcome! Please feel free to submit a Pull Request with improvements to the template.

## 📄 License

This template is released under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Created by**: The Development Community
**Repository**: [ai-feature-plan-template](https://github.com/BO5AMIS/ai-feature-plan-template)