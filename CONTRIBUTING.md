# Contributing to Dopoamind

Thank you for your interest in contributing! This document provides guidelines for adding content, improving existing documentation, and maintaining the quality and scope of the Dopoamind repository.

## Our Mission

Dopoamind aims to provide **educational, evidence-based information** about dopamine neurobiology, stimulant withdrawal, and recovery. We focus on:
- Summarizing peer-reviewed literature
- Explaining complex neuroscience in accessible language
- Providing accurate, balanced information without prescriptive claims
- Maintaining safety-first approach to all content

## Core Principles

### 1. Evidence-Based
All factual claims should be supported by peer-reviewed scientific literature. Summaries of research are welcome; speculation or anecdotal claims should be clearly labeled.

### 2. Educational Focus
Content should inform and explain, not prescribe or recommend specific treatments. Avoid:
- Dosing instructions or protocols
- Guarantees of effectiveness
- Medical advice
- Unverified or experimental claims

### 3. Safety-First
All content related to withdrawal or recovery should include:
- Clear disclaimers that information is not medical advice
- Emergency resources and crisis contact information
- Recommendations to consult healthcare providers
- Acknowledgment of individual variation and risk factors

### 4. Inclusive and Accessible
Write for a diverse audience:
- Researchers, clinicians, students, and informed lay readers
- Explain technical terms; provide context
- Use clear, logical organization
- Include visual aids (diagrams, tables) when helpful

### 5. Neutral and Balanced
Present evidence fairly:
- Acknowledge uncertainty and areas of active research
- Present both supporting and contradictory evidence
- Avoid sensationalism or exaggeration
- Distinguish between "established" and "emerging" findings

## How to Contribute

### Reporting Issues or Suggesting Changes

1. **Check existing content**: Browse the repository to ensure your suggestion isn't already addressed.
2. **Open an issue**: Describe your suggestion clearly:
   - What content is missing or needs improvement?
   - Why is this important?
   - Any relevant citations or resources?
3. **Discussion**: Maintainers will respond to discuss feasibility and approach.

### Submitting Content

#### For Small Changes (typos, clarifications, minor additions)

1. **Fork the repository** and create a branch:
   ```bash
   git checkout -b fix/your-description
   ```
2. **Make changes** following the style guide below
3. **Commit with a clear message**:
   ```bash
   git commit -m "docs: fix typo in receptors.md"
   ```
4. **Push and open a pull request** with a description of changes

#### For Substantial Content (new sections, major revisions)

1. **Open an issue first** proposing the new content (see "Reporting Issues" above)
2. **Wait for discussion** to confirm the addition fits the repository's scope
3. **Create a branch** and develop content
4. **Include citations** for all factual claims (see Citation Guidelines below)
5. **Request review** from maintainers
6. **Revise** based on feedback before merging

### Content Organization

Follow the existing structure:

```
docs/
├── dopamine-neurobiology/
│   ├── README.md (overview and index)
│   ├── synthesis-and-metabolism.md
│   ├── receptors.md
│   └── [additional topics].md
├── withdrawal-protocols/
│   ├── README.md (overview and index)
│   ├── withdrawal-timeline.md
│   └── [additional topics].md
├── chemicals/
│   ├── README.md (overview and index)
│   └── [substance profiles].md
```

**For new files:**
- Use descriptive, lowercase, hyphenated names
- Include a clear title (H1 heading) and introduction
- Link to related files using relative paths
- Add entry to section README.md
- Update INDEX.md

## Style Guide

### Writing Style

- **Tone**: Formal but accessible; explain jargon
- **Audience**: Educated generalist (researcher, clinician, student, informed lay reader)
- **Length**: Comprehensive but not excessive; use subsections for organization
- **Clarity**: Use active voice; define technical terms on first use

### Markdown Formatting

**Headings:**
```markdown
# Main Title (H1 — only one per file)
## Section (H2)
### Subsection (H3)
#### Detail (H4 if needed)
```

**Emphasis:**
```markdown
**Bold** for important terms or first mentions
*Italic* for emphasis or variables
```

**Lists:**
```markdown
- Bullet points for unordered lists
  - Use indentation for nested items

1. Numbered lists for ordered steps
   1. Nested numbering with indentation
```

**Code and Chemical Formulas:**
```markdown
Use `inline code` for chemical abbreviations (e.g., `DAT`, `VMAT2`)
Use code blocks for longer technical content
```

**Links:**
```markdown
[Link text](url) for external links
[Link text](../path/to/file.md) for internal links within docs
```

**Tables:**
```markdown
| Header 1 | Header 2 |
|----------|----------|
| Data 1   | Data 2   |
```

### Terminology

- Use consistent terminology (create a glossary if needed)
- Define technical terms on first mention
- Provide abbreviations in parentheses: "Dopamine Transporter (DAT)"
- Use appropriate level of formality for audience

### Safety and Disclaimers

All content related to substances, withdrawal, or health should include:

**Required disclaimer template:**
```markdown
## IMPORTANT: Safety and Medical Disclaimer

This information is **for educational purposes only**. It is **not medical advice**. 
Always consult a licensed healthcare provider before:
- Starting any supplement, medication, or treatment
- Making changes to existing treatment
- Addressing mental or physical health concerns
```

**Emergency resources in withdrawal/recovery content:**
```markdown
### Crisis Resources

If experiencing suicidal thoughts, self-harm urges, or medical emergency:
- **Emergency**: Call 911 (US)
- **National Suicide Prevention Lifeline**: 988 or 1-800-273-8255
- **SAMHSA National Helpline**: 1-800-662-4357 (free, confidential, 24/7)
```

## Citation Guidelines

### How to Cite

**In-text citations:**
- Use author-year format: "Research shows X (Author et al., Year)"
- Include DOI or URL in parentheses if available

**Full citations:**
- Follow this format:
  ```
  Author(s) (Year). "Title." Journal Name, Volume(Issue), Pages. DOI: https://doi.org/...
  ```

**Example:**
```markdown
Dopamine system dysregulation has been implicated in major depression (Belujon & Grace, 2017). 
DOI: https://doi.org/10.1093/ijnp/pyy099

Full citation:
Belujon, P., & Grace, A. A. (2017). Dopamine system dysregulation in major depressive disorders. 
International Journal of Neuropsychopharmacology, 20(12), 1036–1046. 
DOI: https://doi.org/10.1093/ijnp/pyy099
```

### Sources to Prioritize

1. **Peer-reviewed journal articles** (highest priority)
2. **Review articles** from reputable journals
3. **Books** from academic publishers
4. **Grey literature** (textbooks, government resources) — use with caution
5. **Avoid**: Blogs, forums, unverified websites, anecdotal claims

### Adding to References.md

If citing a reference not already in [References.md](References.md):

1. Add the full citation to References.md
2. Include a 1–2 sentence summary of relevance
3. Provide DOI and/or URL if available
4. Maintain alphabetical or logical ordering

## Review Process

1. **Pull Request**: Submit PR with your changes and description
2. **Automated Checks**: Verify markdown syntax, links, and formatting
3. **Peer Review**: Maintainers review for:
   - Accuracy and evidence support
   - Alignment with repository scope and principles
   - Clarity and accessibility
   - Safety and appropriate disclaimers
   - Integration with existing content
4. **Revision**: Make requested changes; discuss any disagreements
5. **Approval and Merge**: Once approved, your contribution is merged

## What We're Looking For

### High-Priority Contributions
- Filling gaps in existing sections
- Adding new evidence-based summaries
- Improving clarity or accessibility
- Expanding sections on withdrawal, recovery, or neurobiology
- Correcting errors or outdated information
- Adding peer-reviewed references

### Lower-Priority or Out-of-Scope
- Personal narratives or anecdotes
- Unverified claims or experimental treatments
- Prescriptive dosing or treatment protocols
- Political or advocacy content
- Content that duplicates existing material
- Promotional content for specific products/services

## Questions?

If you have questions about contributing:

1. **Check existing issues** to see if your question has been discussed
2. **Open a new issue** with the label "question" or "discussion"
3. **Reference relevant sections** in your question
4. **Maintainers will respond** to provide guidance

## Code of Conduct

This repository is committed to providing a welcoming, inclusive environment. We expect all contributors to:
- Treat others with respect
- Assume good intentions
- Provide constructive feedback
- Accept feedback graciously
- Avoid harassment, discrimination, or hostile behavior

Violations may result in removal from the project.

## Attribution

All contributors will be acknowledged:
- In commit messages
- In pull request history
- Optionally in a CONTRIBUTORS.md file (to be created)

## License

By contributing, you agree that your contributions will be licensed under the [MIT License](LICENSE) of this repository.

---

**Thank you for helping make Dopoamind a valuable resource for education and understanding!**
