# github-contribution-log

# Contribution [1]: [Issue Title]

**Contribution Number:** [1 / 2 / 3]  
**Student:** Syeda Rahman
**Issue:** [\[GitHub issue link\]](https://github.com/autowarefoundation/agnocast/issues/943)  
**Status:** [**Phase I** / Phase II / Phase III / Phase IV] [**In Progress** / Complete]

---

## Why I Chose This Issue

I chose this issue because it sits directly at the intersection of my coursework and hands-on project experience. I've taught Operating Systems and Computer Architecture at the university level, and I've built low-level systems projects involving lock-free data structures, multithreading, and Linux process management. Kernel-userspace data transfer via ioctl is exactly the kind of problem I find most interesting — it requires thinking carefully about memory, boundaries, and performance simultaneously.  

The page boundary edge case flagged in the issue description is what really drew me in. Changing copy_to_user to copy only ret_entry_num entries is straightforward, but reasoning correctly about what happens when a large array crosses page boundaries is a genuine systems challenge. I want to understand how production kernel code handles that class of problem, and contributing a correct solution here would push me to think at that level.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]
1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**
- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
