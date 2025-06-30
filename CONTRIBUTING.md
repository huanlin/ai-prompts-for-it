# Contributing to AI Prompts for IT

Thank you for your interest in contributing to this collection! This guide will help you contribute effectively and maintain the quality of our prompt library.

## 🎯 What We're Looking For

We welcome prompts that are:

- **IT-focused**: Relevant to programming, DevOps, technical writing, or system administration
- **Well-tested**: Proven to work effectively with AI assistants
- **Clear and specific**: Easy to understand and use
- **Reusable**: Applicable to common IT scenarios

## 📋 Before You Contribute

1. **Search existing prompts** to avoid duplicates
2. **Test your prompt** with at least one AI assistant (Gemini CLI, ChatGPT, Claude, etc.)
3. **Follow our template** for consistency
4. **Choose the right category** for your prompt

## 🚀 How to Contribute

### Step 1: Fork and Clone

```bash
# Fork the repository on GitHub, then clone your fork
git clone https://github.com/YOUR_USERNAME/ai-prompts-for-it.git
cd ai-prompts-for-it
```

### Step 2: Create a Branch

```bash
git checkout -b add-new-prompts
```

### Step 3: Add Your Prompts

1. Navigate to the appropriate category folder
2. Create a new `.md` file with a descriptive name
3. Use our [prompt template](prompt-template.md)
4. Follow the naming convention: `task-description.md`

### Step 4: Test Your Prompts

- Test with at least one AI assistant
- Verify the output quality
- Make adjustments if needed

### Step 5: Submit a Pull Request

```bash
git add .
git commit -m "Add [category]: [brief description]"
git push origin add-new-prompts
```

Then create a pull request on GitHub with:

- Clear title describing what you're adding
- Description of the prompts and their use cases
- Which AI assistants you tested with

## 📝 Prompt Template

Use this template for all new prompts:

````markdown
# [Prompt Title]

## Description
Brief description of what this prompt does and when to use it.

## Category

- Primary: [e.g., Programming, Writing, DevOps]
- Secondary: [e.g., Code Review, Documentation, Deployment]

## Use Cases
- Use case 1
- Use case 2
- Use case 3

## Prompt

```text
[Your actual prompt text here]

Replace [PLACEHOLDER] with your specific content.
```

## Example Usage

```text
[Show an example of the prompt in action]
```

## Expected Output

Describe what kind of output this prompt typically generates.

## Tested With

- [ ] Gemini CLI
- [ ] ChatGPT
- [ ] Claude
- [ ] Other: ___________

## Tips

- Any specific tips for using this prompt effectively
- Common variations or modifications
- What to do if results aren't satisfactory

````

## ✅ Quality Standards

### Prompt Quality

- **Clear objective**: The prompt should have a specific, well-defined goal
- **Proper context**: Include necessary background information
- **Actionable instructions**: Tell the AI exactly what to do
- **Output format**: Specify the desired format when relevant
- **Examples**: Include examples when they help clarify expectations

### Documentation Quality

- **Complete template**: Fill out all sections of the template
- **Clear descriptions**: Write descriptions that non-experts can understand
- **Practical examples**: Show real-world usage scenarios
- **Testing verification**: Confirm the prompt works as described

### File Organization

- **Correct category**: Place prompts in the most appropriate directory
- **Descriptive names**: Use clear, descriptive filenames
- **Consistent formatting**: Follow markdown best practices
- **No duplicates**: Ensure your prompt doesn't already exist

## 🔍 Review Process

1. **Automated checks**: Basic formatting and structure validation
2. **Community review**: Other contributors may provide feedback
3. **Maintainer review**: Final review by project maintainers
4. **Testing verification**: Confirmation that prompts work as described

## 💡 Tips for Great Contributions

### Writing Effective Prompts

- **Be specific**: Vague prompts produce inconsistent results
- **Provide context**: Give the AI enough background information
- **Set constraints**: Specify format, length, style requirements
- **Use examples**: Show the AI what good output looks like
- **Test iterations**: Refine based on actual AI responses

### Documentation Best Practices

- **Write for beginners**: Assume readers are new to AI prompts
- **Include edge cases**: Mention when prompts might not work well
- **Provide alternatives**: Suggest variations for different scenarios
- **Keep it updated**: Update prompts if you find better versions

## 🚫 What Not to Contribute

- Prompts that could be used for harmful purposes
- Overly generic prompts that aren't IT-specific
- Prompts that consistently produce poor results
- Duplicate or near-duplicate content
- Prompts that violate AI platform terms of service

## 🤝 Community Guidelines

- **Be respectful**: Treat all contributors with respect
- **Be constructive**: Provide helpful feedback on others' contributions
- **Be collaborative**: Work together to improve prompts
- **Be patient**: Reviews and responses may take time

## 📞 Getting Help

- **Questions**: Open a [GitHub Discussion](../../discussions)
- **Issues**: Report problems via [GitHub Issues](../../issues)
- **Ideas**: Share suggestions in [GitHub Discussions](../../discussions)

## 🏆 Recognition

Contributors will be recognized in:

- Repository contributors list
- Release notes for significant contributions
- Special mentions for exceptional prompts

---

Thank you for helping make AI more accessible and useful for the IT community! 🚀
