# Memory Bank

This directory contains Cline's Memory Bank - a structured documentation system that enables Cline to maintain context across memory resets.

## File Structure and Hierarchy

The Memory Bank follows a hierarchical structure where files build upon each other:

```
projectbrief.md (Foundation)
    ↓
    ├─→ productContext.md (Why & How)
    ├─→ systemPatterns.md (Architecture)
    └─→ techContext.md (Technology)
         ↓
         └─→ activeContext.md (Current Focus)
              ↓
              └─→ progress.md (Status)
```

## Core Files

### 1. projectbrief.md
**Foundation Document**
- Project overview and core requirements
- Goals and success criteria
- Scope definition
- This shapes all other documentation

### 2. productContext.md
**Purpose and Goals**
- Why the project exists
- Problems it solves
- How it should work
- User experience goals

### 3. systemPatterns.md
**Architecture and Design**
- System architecture
- Key technical decisions
- Design patterns in use
- Component relationships

### 4. techContext.md
**Technology Stack**
- Technologies used
- Development setup
- Technical constraints
- Dependencies

### 5. activeContext.md
**Current Work Focus**
- What's being worked on now
- Recent changes
- Next steps
- Active decisions and considerations

### 6. progress.md
**Project Status**
- What works (completed features)
- What's left to build
- Current status and milestones
- Known issues

## Usage Guidelines

### For Cline (AI Agent)
1. **ALWAYS** read ALL Memory Bank files at the start of EVERY task
2. Start with `projectbrief.md` to understand the foundation
3. Read files in hierarchical order for best understanding
4. Update `activeContext.md` and `progress.md` most frequently
5. Update other files when discovering new patterns or making significant changes

### For Humans
- These files document the project for AI agent continuity
- They provide a comprehensive project overview
- They can serve as onboarding documentation
- They capture the "why" behind decisions, not just the "what"

## Maintenance

The Memory Bank should be updated when:
- Discovering new project patterns
- After implementing significant changes
- When context needs clarification
- When user requests with "update memory bank"

Files are written in Markdown for readability and version control compatibility.
