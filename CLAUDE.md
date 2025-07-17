We are writing a collaborative textbook about IP and Internet Law.
- Source code is: ~/src/wikijuris (gh: @nicsuzor/wikijuris)
- Text is Markdown format
- Incoming files are in ./incoming

We need to edit suggestions that come in, convert them to Markdown, ensure they match tone and style and are correct, and place them in the correct place in the book.

# WikiJuris LLM Agent Instructions

## Project Overview
- **Repo**: @nicsuzor/wikijuris
- **Purpose**: IP and Internet Law textbook (Markdown)
- **Task**: Process Word docs from `./incoming/` → edit → integrate → commit

## Workflow
1. Read document from `./incoming/$NAME.docx`
2. Use a tool to convert from docx to Markdown and save to `./incoming/working/$NAME-converted.md`
3. Find appropriate placement in textbook (`./cyberlaw/`)
4. Edit per guidelines below and update saved draft in `./incoming/working/$NAME.md`
5. Merge into source file
6. Git commit with descriptive message
7. Archive original document by moving file to `./processed`

## Editorial Guidelines

### Content Treatment
- **Minor issues** = examples/case studies (use `###` heading max)
- **Major issues** = full sections with multiple headings
- Ask: "actual problem" or "example of harm"?
- Don't over-structure minor content

### Human rights centric approach
- Approach issues in a way that maximizes support for human rights, prioritizing interests of marginalized groups.
- e.g No slut shaming; no victim-blaming; no negative gender stereotypes or ableism. Prefer consent and respect for bodily autonomy over sexual morality. Ensure, for example, that discussion of criminal offences around sexual content are expressed in full sex-positive context that emphasises sexual health and access to reproductive rights and information.

### Legal Analysis
- Highlight digital/physical law gaps
- Show enforcement challenges
- Use examples to illustrate broader principles
- Primarily focus on Australian law, ensuring that both Federal and State laws are considered and included
- Include international comparisons proportionately

### Tone
- Academic but accessible
- Write for law students/practitioners
- Use concrete examples
- Focus on legal gaps, not moral panic
- Present facts without sensationalizing
- Include prevalence data for context

### Red Flags
- Over-treating minor issues
- Sex-negative assumptions
- Conflating consensual/non-consensual activity
- Unnecessary academic jargon
- Missing intersectional analysis
- Disproportionate structure

### Writing Guidelines
- Do not create new abbreviations. Avoid abbreviations except where they are very well known.

## Git Commands
```bash
cd ~/src/wikijuris
git add [file.md]
git commit -m "Add: [brief description]"
git push origin main
```