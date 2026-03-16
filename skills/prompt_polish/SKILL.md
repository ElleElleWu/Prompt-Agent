---
name: prompt-polish
description: Polish and optimize user prompts for better AI interactions
---

## What I do

Transform rough, informal, or unclear prompts into well-structured, professional, and effective prompts that yield better results from AI systems.

## When to use me

Use this skill when:
- User provides a rough or incomplete prompt
- The prompt needs better structure and clarity
- User wants to optimize prompt effectiveness
- Need to add context, constraints, or role definitions

## Workflow

1. **Analyze** the original prompt to understand:
   - User's core intent and goal
   - Target domain (coding, writing, analysis, creative, etc.)
   - Missing context or unclear requirements
   - Current structure and organization

2. **Apply Polish Strategies** based on analysis:
   - **Structure Enhancement**: Organize into clear sections (Role, Task, Requirements, etc.)
   - **Context Enrichment**: Add necessary background and assumptions
   - **Constraint Clarification**: Define boundaries, limitations, and specific requirements
   - **Role Assignment**: Define the AI's persona/expertise for the task
   - **Output Specification**: Define expected format, length, and structure

3. **Generate Polished Versions**:
   - Primary polished prompt (most balanced)
   - Concise version (for quick tasks)
   - Detailed version (for complex tasks) - optional

4. **Provide Improvement Summary**:
   - List key changes made
   - Explain the rationale for each change
   - Suggest when to use each version

## Input Format

The skill accepts a user prompt in any form:
- Raw text or rough notes
- Fragmented thoughts or bullet points
- Informal language or shorthand
- Partial or incomplete descriptions

## Output Format

```markdown
## 原始Prompt分析
[Analysis of the original prompt in Chinese]

## 润色后的Prompt
```
[The polished prompt - in user's preferred language]
```

## 改进说明
1. [Change 1]: [Explanation in Chinese]
2. [Change 2]: [Explanation in Chinese]
...

## 替代版本（可选）
### 简洁版
```
[Concise version]
```

### 详细版
```
[Detailed version]
```
```

## Key Principles

1. **Preserve Intent**: Maintain the user's original goal and requirements
2. **Add Structure**: Use clear sections and formatting
3. **Be Specific**: Replace vague terms with concrete details
4. **Define Context**: Add necessary background information
5. **Set Expectations**: Clarify desired output format and quality

## Examples

### Example 1: Code Generation
**Original**: "写个排序算法"

**Polished**:
```
# Role
You are an expert computer scientist specializing in algorithms and data structures.

# Task
Implement a sorting algorithm with the following specifications:

## Requirements
- Algorithm: Quicksort (or suggest a better alternative if appropriate)
- Language: Python 3
- Input: A list of comparable elements
- Output: A new sorted list in ascending order

## Constraints
- Time complexity: O(n log n) average case
- Space complexity: O(log n) auxiliary space
- Must handle edge cases (empty list, single element, duplicates)

## Deliverables
1. Complete, well-documented implementation
2. Brief explanation of the algorithm
3. Time/space complexity analysis
4. Example usage with test cases
```

### Example 2: Writing Task
**Original**: "帮我写个产品介绍"

**Polished**:
```
# Role
You are a professional marketing copywriter with expertise in technology products.

# Task
Write a compelling product introduction for a new software product.

## Product Information
- Product name: [To be specified]
- Category: [To be specified]
- Target audience: [To be specified]
- Key features: [To be specified]
- Unique selling points: [To be specified]

## Requirements
- Tone: Professional yet approachable
- Length: 200-300 words
- Structure: 
  1. Hook/Opening statement
  2. Problem statement
  3. Solution (product introduction)
  4. Key benefits
  5. Call to action

## Output Format
Provide the copy in markdown format with clear headings.
```

## Notes

- Always ask for clarification if critical information is missing
- Adapt the polish level based on the complexity of the task
- Consider the target AI system when formatting the prompt
- Maintain the user's preferred language (Chinese or English) in the polished output
