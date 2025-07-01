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

## Use Cases (optional)

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

---

Thank you for helping make AI more accessible and useful for the IT community! 🚀
