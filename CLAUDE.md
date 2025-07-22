# WikiJuris LLM Agent Instructions

We are writing a collaborative textbook about IP and Internet Law.

- Source code is: ~/src/wikijuris (gh: @nicsuzor/wikijuris)
- Text is Markdown format
- Uses Jekyll with just-the-docs theme
- Each .md file is a chapter or sub-chapter, with navigation based on front matter in each file.

## Project Overview

- **Repo**: @nicsuzor/wikijuris
- **Purpose**: Two academic law textbooks (IP and Internet Law)
- **Format**: Markdown with Jekyll/just-the-docs

## Core Principles

- **Accessible writing**: No jargon, neologisms, or unnecessary complexity. Formal academic tone.
- **Neutral perspective**: Remove opinion/interpretation. Flag contentious points via GitHub issues.
- **Inclusive language**: Avoid implicit bias (no carceral preference, sex-negative language, or loaded terms like "theft" for infringement).
- **Human rights centric**: Maximize support for human rights, prioritizing interests of marginalized groups.

## Workflow Types

### A. Processing Incoming Contributions

1. Read incoming document and save to `./incoming/`
2. If necessary, use a tool to convert to Markdown and save to `./incoming/working/$NAME-converted.md`
3. Find appropriate placement in textbook
4. Update textbook content with new material, edited according to our guidelines
5. For any material not incorporated, save in `./incoming/working/$NAME-leftover.md` and, if necessary, raise a github issue to draw editor's attention to it.
6. ALWAYS Git commit with descriptive message documenting your changes
7. Archive original document by moving original file to `./processed`
8. Create pull request if required

### B. Reviewing Pull Requests
1. Review changed files for compliance with editorial guidelines
2. Verify citations and factual claims
3. Check for duplication or structural issues
4. Comment on PR with specific feedback
5. Approve or request changes as appropriate

### C. Responding to GitHub Issues
1. Analyze the issue and any referenced content
2. If research needed, verify facts/citations
3. Implement fixes or create comprehensive response
4. Reference issue number in commits/PRs
5. Close issue with explanation of resolution


## Editorial Guidelines

### Content Treatment
- **Minor issues** = examples/case studies (use `###` heading max)
- **Major issues** = full sections with multiple headings
- Ask: "actual problem" or "example of harm"?
- Don't over-structure minor content

### Legal Analysis

- **Primary focus**: Australian law (Federal and State)
- **International comparisons**: Include proportionately
- **Clear labeling**: Always specify jurisdiction

### Tone & Writing

- Academic but accessible
- Write for law students/practitioners
- Use concrete examples
- Focus on legal gaps, not moral panic
- Present facts without sensationalizing
- Include prevalence data for context
- Do not create new abbreviations

### Red Flags

- Over-treating minor issues
- Sex-negative assumptions
- Conflating consensual/non-consensual activity
- Unnecessary academic jargon
- Missing intersectional analysis
- Disproportionate structure
- Neologisms 

## Quality Standards

### Verification
1. **Use RAG tools** to check all citations and factual claims
2. **Structure review**: Ensure logical flow and fit
3. **Remove duplication**: Check across and within chapters
4. **Flag uncertainties**: Create GitHub issues for unverifiable claims

### Source Management
- **Conflicts**: Flag conflicting sources via GitHub issues
- **Hierarchy**: Primary sources > authoritative secondary > general commentary
- **Currency**: Verify legal updates; flag outdated content with `{: .warning}`

### Technical Terms
- **Essential terms**: Define on first use when unavoidable
- **Glossary links**: Link to entries where available
- **Plain language**: Provide alternatives alongside technical terms

## Formatting Standards

### Content Blocks
- `{: .ed}` - Editorial notes (temporary)
- `{: .example}` - Case studies, examples, case notes
- `{: .note}` - Reader notes
- `{: .warning}` - Potentially incorrect/incomplete info
- `{: .help}` - Content requests

### Citations

- Medium-neutral AGLC style
- Hyperlink document names and pinpoints where possible
- Footnotes: `[^ref_name]` in text, `[^ref_name]: citation` at section end

### Structure

- Each file = one chapter/sub-chapter
- Use markdown headings for logical sections
- Keep sections focused and reasonable length

### Visual Elements

- **Tables**: Use markdown tables for comparisons
- **Diagrams**: Store in `/assets/images/` with alt text
- **Flowcharts**: Consider mermaid diagrams

## Git Workflow

### Commits

- **Always commit changes** with descriptive messages
- **Format**: `[Action]: Brief description (contributor: name if applicable)`
- Examples:
  - `Add: Privacy law section on data breaches`
  - `Fix: Update GDPR references to current regulation`
  - `Edit: Clarify copyright fair use examples (contributor: J.Smith)`

### GitHub Issues

Create issues for:
- Unverifiable claims or missing citations
- Proposed structural changes
- Conflicting sources or interpretations
- Content gaps or update needs
- Legal developments requiring attention

### Pull Requests

- **When**: For major changes affecting multiple files/chapters
- **Title**: Clear description of changes
- **Body**: Include:
  - Summary of changes
  - Rationale
  - Any issues addressed
  - Required reviewer attention points


## When in Doubt

Create GitHub issue rather than making assumptions about:

- Chapter reorganization needs
- Contentious legal interpretations
- Unverifiable claims
- Major structural changes