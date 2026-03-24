# Contributing to Awesome NotebookLM Slide Decks Prompts

First off, thank you for considering contributing to this project! It's people like you that make this repository such a great resource.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to the maintainers.

## How Can I Contribute?

### 1. Add New Prompts
Have a NotebookLM prompt that works really well? Share it!

**What makes a good prompt contribution:**
- ✅ Field-tested and proven to work
- ✅ Clear, well-structured
- ✅ Solves a real problem
- ✅ Includes context and example
- ✅ Fits into one of our categories

**How to submit:**
1. Edit `COMPLETE_PROMPTS.md`
2. Add your prompt in the appropriate section (or create a new section if needed)
3. Include a brief description of what the prompt does
4. Add an example of how to use it
5. Submit a PR with a clear description

**Template for new prompts:**
```markdown
### [Prompt Name]
```
[Full prompt text here]
```

**When to use this:**
[Describe the use case and situation]

**Example:**
```
[Show example with real content]
```

**Tips for best results:**
- [Any special tips]
```
### 2. Add New Design Styles
Discovered a design style that produces amazing results? Document it!

**What we need:**
- ✅ Style name
- ✅ Full prompt specification
- ✅ Example image or description
- ✅ When to use it
- ✅ Color palette
- ✅ Typography guidelines
- ✅ Layout patterns

**How to submit:**
1. Create a detailed specification following our format
2. Include the style in `COMPLETE_PROMPTS.md` under "Artistic & Avant-Garde Styles" or appropriate section
3. Add a checklist for the style in `QUICK_REFERENCE.md`
4. Submit PR with examples

**Template for new styles:**
```markdown
### [Style Name]

[Brief description]

```
# [STYLE_NAME] Specification

Visual Identity:
- Colors: [list]
- Typography: [describe]
- Key Characteristics: [list]
- Mood: [describe]

Layout Patterns:
- [Pattern 1]
- [Pattern 2]
- [Pattern 3]

When to Use:
- [Use case 1]
- [Use case 2]

Best For Audiences:
- [Audience 1]
- [Audience 2]
```

Design Rules:
- [Rule 1]
- [Rule 2]
```

### 3. Create Usage Examples
Show people how to actually use these prompts!

**What we need:**
- ✅ Real-world scenario
- ✅ Step-by-step walkthrough
- ✅ Actual prompt used
- ✅ Tips and tricks
- ✅ Common pitfalls to avoid

**How to submit:**
1. Create a new file in `examples/` folder
2. Use format: `[type]-[purpose].md`
3. Include: scenario, prompt, tips, refinements
4. Add link to README.md
5. Submit PR

**Example file template:**
```markdown
# Example: [Scenario]

## Situation
[Describe the real-world scenario]

## Goal
[What we're trying to achieve]

## Initial Prompt
[The actual prompt we use]

## Sources Used
[What materials we uploaded to NotebookLM]

## Results
[Describe what we got back]

## Refinement Prompts
[Follow-up prompts to improve it]

## Pro Tips
[What worked well]

## Common Mistakes
[What to avoid]

## Time Estimate
[How long this took]
```

### 4. Improve Documentation
Help make the guides clearer and more useful!

**What we need:**
- ✅ Better explanations
- ✅ Clearer examples
- ✅ Fixed typos
- ✅ Better organization
- ✅ Additional context
- ✅ Better formatting

**How to submit:**
1. Make your improvements
2. Submit PR with clear description
3. Explain what you improved and why

### 5. Report Issues & Bugs
Found a problem? Let us know!

**Good bug reports include:**
- ✅ Clear title
- ✅ Step-by-step reproduction
- ✅ What you expected to happen
- ✅ What actually happened
- ✅ Your environment (if relevant)
- ✅ Screenshots or examples

**How to submit:**
1. Go to Issues tab
2. Click "New Issue"
3. Use the bug report template
4. Provide all relevant details
5. Submit

### 6. Suggest Improvements
Have an idea to make this better?

**Good suggestions include:**
- ✅ Clear problem statement
- ✅ Proposed solution
- ✅ Why this matters
- ✅ Examples if relevant

**How to submit:**
1. Go to Issues/Discussions
2. Describe your suggestion
3. Explain the benefit
4. Be open to feedback
5. Submit

---

## Submission Guidelines

### Pull Request Process

1. **Fork the repository** on GitHub
   ```bash
   git clone https://github.com/YOUR-USERNAME/awesome-notebooklm-prompts.git
   cd awesome-notebooklm-prompts
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-contribution-name
   ```

3. **Make your changes**
   - Edit files following the style guides below
   - Test your prompts (actually use them in NotebookLM if possible)
   - Ensure formatting is consistent
   - Update README.md if adding major new content

4. **Commit with clear messages**
   ```bash
   git add .
   git commit -m "Add: [clear description of what you added]"
   # Examples:
   # git commit -m "Add: Watercolor design style with full specification"
   # git commit -m "Add: Example - Conference talk workflow"
   # git commit -m "Improve: Clearer explanation in Sharp-Edged Minimalism section"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-contribution-name
   ```

6. **Open a Pull Request**
   - Provide a clear title
   - Describe what you added/changed
   - Link any related issues
   - Explain why this contribution is valuable
   - Be ready for discussion/feedback

### Style Guide for Contributions

#### Markdown Formatting
- Use clear headers (##, ###, ####)
- Use bullet points for lists
- Use code blocks for prompts (```markdown)
- Bold important terms (**term**)
- Include links where relevant

#### Prompt Guidelines
- **Clarity**: Use clear, direct language
- **Completeness**: Include all necessary context
- **Testability**: Should work as written
- **Flexibility**: Allow for customization
- **Examples**: Show how to use it

#### Writing Style
- Write for clarity, not fancy language
- Assume some NotebookLM experience, but explain basics
- Use active voice where possible
- Keep sentences concise
- Proofread before submitting

#### File Naming
```
examples/[type]-[purpose].md
# Examples:
examples/academic-conference-talk.md
examples/sales-investor-pitch.md
examples/training-educational-module.md
```

#### Section Organization
- New design styles → `COMPLETE_PROMPTS.md`
- New use cases → Add example file to `examples/`
- New best practices → `QUICK_REFERENCE.md`
- New resources → `RESOURCES.md`
- New sections → Update `README.md` table of contents

---

## Content Quality Standards

### For Prompts
- [ ] Actually tested with NotebookLM
- [ ] Produces reliable results
- [ ] Clear and unambiguous
- [ ] Includes context needed
- [ ] Well-formatted
- [ ] Example provided

### For Design Styles
- [ ] Full specification included
- [ ] Color palette defined
- [ ] Typography guidelines clear
- [ ] Layout patterns described
- [ ] Use cases identified
- [ ] Design rules listed

### For Examples
- [ ] Real-world scenario
- [ ] Step-by-step walkthrough
- [ ] Actual prompt shown
- [ ] Results described
- [ ] Tips included
- [ ] Common mistakes noted

### For Documentation
- [ ] Clear and concise
- [ ] Well-organized
- [ ] Correct links
- [ ] Proper formatting
- [ ] Examples included
- [ ] Proofread

---

## Community Guidelines

### Be Respectful
- Assume good intent
- Provide constructive feedback
- Respect different opinions
- Be welcoming to newcomers

### Be Helpful
- Help others with their contributions
- Share knowledge generously
- Provide detailed feedback
- Suggest improvements thoughtfully

### Be Honest
- Acknowledge limitations
- Be transparent about testing
- Admit when you don't know something
- Share both successes and failures

### Be Professional
- Follow the Code of Conduct
- Keep discussions on-topic
- Respect others' time
- Give credit where due

---

## Recognition

Contributors will be recognized in:
- ✅ README.md (Contributors section)
- ✅ PR acknowledgment
- ✅ Release notes (for major contributions)
- ✅ Repository insights

We value all contributions, from new prompts to typo fixes!

---

## Development Setup

### To work locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/awesome-notebooklm-prompts.git
   cd awesome-notebooklm-prompts
   ```

2. **Make changes to files**
   - Markdown files are plain text, use any editor
   - Follow the style guides above
   - Test thoroughly

3. **Preview your changes**
   - Use a Markdown preview tool
   - Check formatting looks good
   - Verify links work

4. **Commit and push**
   ```bash
   git add .
   git commit -m "Your clear commit message"
   git push origin your-branch-name
   ```

---

## Getting Help

### Questions?
- 💬 Open a Discussion
- 📧 Check existing issues/PRs first
- 📚 Read the existing documentation
- 🎓 Check the examples

### Stuck?
- Break it into smaller steps
- Look at similar contributions
- Ask in the discussion thread
- No such thing as a dumb question!

---

## Review Process

### What we look for:
1. **Quality** - Does it meet our standards?
2. **Relevance** - Fits the repository's scope?
3. **Accuracy** - Is it correct/tested?
4. **Clarity** - Easy to understand?
5. **Value** - Helps the community?

### Timeline:
- Reviews typically within 3-7 days
- Maintainers may ask for changes
- We'll provide constructive feedback
- Merged when ready!

---

## Attribution

When contributing, you agree that:
- Your contribution can be used under the MIT License
- You have the right to contribute this content
- You're not violating anyone's rights
- You're comfortable with it being public and freely used

---

## Questions or Need Help?

- 📖 Read the README.md
- 🔍 Check existing Issues/PRs
- 💬 Open a Discussion
- 📧 DM if needed

---

## Thank You! 🙏

Every contribution—whether it's a single prompt, an improvement, or feedback—helps make this resource better for everyone. Thank you for being part of the community!

---

**Happy Contributing!**

For more info, see:
- [Code of Conduct](CODE_OF_CONDUCT.md)
- [License](LICENSE)
- [README](README.md)
