Follow Rules:
- Do not respond directly to user.
- Do not use codeblock fencing.

Generate a detailed Markdown mind map that systematically breaks down the skills, concepts, and knowledge areas related to the following subject: **${topic}**

The primary goal is to create a structured overview that digs deep into the subject matter, similar to how one might map out a comprehensive curriculum or skill tree. Follow these guidelines strictly:

1.  **Format:** Use Markdown. **Crucially, ensure no line in the output begins with any leading spaces or indentation.** The hierarchy must be defined *solely* by the Markdown heading levels (`#`, `##`, `###`, etc.).
2.  **Root Node:** Start with a single Level 1 heading (`#`) representing the main subject. Include the subject title followed by relevant high-level keywords/tags indicating its scope (e.g., `# [SUBJECT] #SkillsOverview #KnowledgeMap #Main`).
3.  **Hierarchy & Decomposition:** Use increasing levels of Markdown headings (`##`, `###`, `####`, etc.) starting at the beginning of the line to represent the breakdown. Focus on decomposing broader skills and topics into their constituent components, sub-skills, and specific concepts.
4.  **Node Content:** For *every* heading (node) at all levels:
    * Provide a clear title identifying the specific skill, concept, tool, or area.
    * Immediately follow the title (on the same line) with several relevant keywords or tags formatted as hashtags. **Each tag absolutely must start with the '#' symbol**, and tags should be separated from each other by single spaces (e.g., `#CoreSkill #Technique #Tooling #Concept #BestPractice`).
5.  **Depth & Granularity:** Break down the subject into **significant depth**. Do not stop at major categories; actively drill down into granular sub-topics, specific techniques, underlying principles, relevant tools/technologies, and finer details. Aim for multiple levels of hierarchy (potentially 5-6+ levels where appropriate) to fully explore complex areas.
6.  **Structure for Understanding:** Organize the topics logically. Structure the map to facilitate understanding, often moving from foundational concepts/skills to more specialized, advanced, or applied areas. Ensure related sub-topics are clearly grouped under appropriate parent nodes.
7.  **Comprehensive Coverage:** Aim for a comprehensive breakdown capturing the essential skills, knowledge domains, key concepts, critical tools/technologies, and important considerations within the subject. Think about what someone would need to learn to become proficient.
8.  **Decomposition Strategy:** When breaking down topics, consider aspects like:
    * Fundamental principles or theories
    * Specific techniques, methodologies, or processes
    * Required tools, software, or technologies
    * Common challenges or pitfalls
    * Best practices or standards
    * Different sub-disciplines or specializations
    * Prerequisite knowledge or related concepts
    * Practical applications or use cases
9.  **(Optional) Descriptions:** Brief descriptions *after* a node's heading/tag line (on a new line, starting with no leading spaces) are acceptable if they add essential clarification, but the primary focus is the structured hierarchy of titles and tags.

**Example Node Format (Strict Adherence Required):**

## Core Skill Area #Foundational #Concept

### Specific Technique #Methodology #Detail

#### Related Tool #Software #Implementation
Optional short description here, starting at the beginning of the line.

Please generate the complete Markdown mind map for ${topic}, emphasizing a deep and structured breakdown of its components and strictly adhering to all formatting rules (no leading spaces, all tags start with #).
