---
name: mfm-orchestration
description: Master orchestration skill that coordinates multiple ECC agents, skills, and tools in complex workflows. Provides intelligent task decomposition, component selection, and execution coordination for the everything-claude-code ecosystem.
origin: ECC
---

# MFM Orchestration Skill

Master orchestration skill for coordinating everything-claude-code components in complex workflows.

## When to Activate

- Complex multi-step development tasks
- Cross-domain projects requiring multiple specialists
- Workflow optimization and automation
- Large-scale refactoring or architecture changes
- End-to-end feature development
- System-wide audits or migrations

## Orchestration Framework

### 1. Task Analysis & Decomposition
```markdown
**TASK ANALYSIS:**
- Primary objective: [clear goal statement]
- Complexity level: [simple/medium/complex/enterprise]
- Required domains: [list relevant domains]
- Success criteria: [measurable outcomes]
- Risk factors: [potential blockers]
```

### 2. Component Selection Matrix
```markdown
**COMPONENT SELECTION:**
| Phase | Primary Agent | Supporting Skills | Commands | Rules |
|-------|---------------|-------------------|----------|-------|
| Planning | planner | blueprint, product-capability | plan | coding-standards |
| Architecture | architect | backend-patterns, api-design | | |
| Implementation | [lang]-reviewer | [lang]-patterns, tdd-workflow | build-fix | |
| Testing | tdd-guide | [lang]-testing, e2e-testing | test-coverage | |
| Review | code-reviewer | security-review | code-review | |
| Deployment | deployment-patterns | docker-patterns | | |
```

### 3. Workflow Orchestration Patterns

#### Pattern A: Feature Development
```
1. planner → Break down requirements
2. architect → Design system architecture  
3. [lang]-reviewer → Implement with patterns
4. tdd-guide → Ensure test coverage
5. code-reviewer → Quality validation
6. security-reviewer → Security check
7. [Optional] performance-optimizer → Optimize
```

#### Pattern B: Security Audit
```
1. security-reviewer → Comprehensive analysis
2. security-scan → Automated vulnerability detection
3. [lang]-reviewer → Language-specific security issues
4. AgentShield → Advanced threat detection
5. security-reviewer → Final validation
```

#### Pattern C: Performance Optimization
```
1. performance-optimizer → Identify bottlenecks
2. database-reviewer → Query optimization
3. [lang]-reviewer → Code-level optimizations
4. e2e-testing → Performance validation
5. refactor-cleaner → Clean up optimizations
```

#### Pattern D: System Migration
```
1. planner → Migration strategy
2. architect → Target architecture
3. [source]-reviewer → Analyze current system
4. [target]-reviewer | patterns → Implement target
5. testing skills → Comprehensive validation
6. deployment-patterns → Rollout strategy
```

### 4. Agent Coordination Protocol

#### Agent Delegation Format
```markdown
**DELEGATING TO [agent-name]:**
*Context:* [current state and requirements]
*Scope:* [specific responsibilities]
*Expected Output:* [deliverables]
*Dependencies:* [what this agent needs from others]
```

#### Inter-Agent Communication
```markdown
**AGENT HANDOFF:**
*From:* [previous-agent]
*To:* [next-agent]
*Artifacts:* [delivered components]
*Context:* [state transfer]
*Next Steps:* [continuation requirements]
```

### 5. Skill Integration Patterns

#### Sequential Skill Activation
```markdown
**SKILL PIPELINE:**
1. [skill-1] → Initial processing
2. [skill-2] → Refinement
3. [skill-3] → Validation
4. [skill-4] → Finalization
```

#### Parallel Skill Execution
```markdown
**PARALLEL SKILLS:**
- [skill-a] → Independent task A
- [skill-b] → Independent task B  
- [skill-c] → Independent task C
*Merge at:* [integration point]
```

### 6. Rule Enforcement Integration

#### Automatic Rule Application
- **coding-standards** → All code generation
- **security rules** → Security-sensitive operations
- **testing rules** → Test development
- **language-specific rules** → Language operations

#### Rule Validation Checkpoints
```markdown
**RULE CHECKPOINTS:**
□ Pre-implementation: [applicable rules]
□ During development: [continuous validation]
□ Pre-commit: [compliance check]
□ Pre-deployment: [final validation]
```

### 7. Command Utilization

#### Command Integration Strategy
```markdown
**COMMAND INTEGRATION:**
- plan → Feature planning phases
- code-review → Review checkpoints
- security-scan → Security validation
- test-coverage → Testing verification
- build-fix → Error resolution
```

### 8. Hook Simulation

#### Manual Hook Execution
```markdown
**HOOK SIMULATION:**
- Pre-commit quality checks
- Security vulnerability scanning
- Performance monitoring
- Context optimization
```

### 9. Error Handling & Recovery

#### Component Failure Protocol
```
1. Detect failure in [component-name]
2. Analyze failure cause and impact
3. Select fallback component [alternative-name]
4. Adjust workflow to accommodate
5. Document failure for learning
6. Continue with modified approach
```

#### Workflow Recovery Patterns
```markdown
**RECOVERY STRATEGIES:**
- *Partial failure*: Continue with unaffected components
- *Critical failure*: Restart with alternative approach
- *Cascade failure*: Abort and reassess strategy
```

### 10. Progress Tracking & Reporting

#### Milestone Tracking
```markdown
**WORKFLOW MILESTONES:**
□ [Phase 1]: [Description] - [Status]
□ [Phase 2]: [Description] - [Status]  
□ [Phase 3]: [Description] - [Status]
□ [Phase 4]: [Description] - [Status]
```

#### Comprehensive Reporting
```markdown
**ORCHESTRATION REPORT:**
*Components Used:* [list of agents/skills/commands]
*Execution Summary:* [what was accomplished]
*Key Decisions:* [architectural choices made]
*Quality Metrics:* [coverage, security score, etc.]
*Performance Metrics:* [efficiency, optimization gains]
*Risk Assessment:* [identified risks and mitigations]
*Recommendations:* [next steps and improvements]
```

## Complex Workflow Examples

### Example 1: E-commerce Platform Feature
```
Components: planner + architect + typescript-reviewer + 
           database-reviewer + security-reviewer + 
           e2e-testing + api-design

Workflow:
1. planner → Feature breakdown (user management, payments, inventory)
2. architect → Microservices architecture design
3. api-design → REST API specifications
4. database-reviewer → Schema design and optimization
5. typescript-reviewer → Node.js implementation
6. security-reviewer → Payment security and data protection
7. e2e-testing → Full user journey validation
```

### Example 2: ML Model Deployment Pipeline
```
Components: mle-reviewer + python-reviewer + 
           deployment-patterns + docker-patterns + 
           monitoring skills + security-reviewer

Workflow:
1. mle-reviewer → Production ML pipeline design
2. python-reviewer → Production-grade Python code
3. deployment-patterns → Cloud deployment strategy
4. docker-patterns → Containerization
5. security-reviewer → Model and data security
6. monitoring skills → Performance and drift monitoring
```

### Example 3: Legacy System Modernization
```
Components: planner + architect + [legacy]-reviewer + 
           [modern]-reviewer + migration patterns + 
           testing skills + deployment-patterns

Workflow:
1. planner → Modernization strategy and roadmap
2. architect → Target architecture design
3. [legacy]-reviewer → Current system analysis
4. [modern]-reviewer → Modern implementation
5. migration patterns → Data and logic migration
6. testing skills → Comprehensive validation
7. deployment-patterns → Gradual rollout strategy
```

## Optimization Guidelines

### Token Efficiency
- Select only relevant components
- Minimize redundant operations
- Cache results across components
- Use parallel execution when possible

### Quality Assurance
- Apply relevant rules at each stage
- Validate outputs before handoffs
- Maintain comprehensive documentation
- Ensure security throughout workflow

### Performance Optimization
- Profile component execution times
- Identify bottlenecks early
- Optimize critical paths
- Monitor resource usage

## Integration Points

### External Systems
- CI/CD pipelines
- Code hosting platforms
- Monitoring systems
- Security scanning tools

### Internal Coordination
- Agent handoff protocols
- Skill integration patterns
- Rule enforcement checkpoints
- Command utilization strategies

This skill provides the master orchestration layer for everything-claude-code, enabling complex workflows that leverage the full power of the ECC ecosystem.
