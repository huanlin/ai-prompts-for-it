# Comprehensive Code Review

## Description

A thorough code review prompt that analyzes code for quality, security, performance, and maintainability issues. Perfect for getting detailed feedback on code changes before merging.

## Category

- Primary: Programming
- Secondary: Code Review

## Use Cases

- Pre-merge code review
- Legacy code assessment
- Code quality improvement
- Security vulnerability detection
- Performance optimization identification

## Prompt

```text
Please conduct a comprehensive code review of the following code. Analyze it for:

**Code Quality & Readability:**
- Code structure and organization
- Naming conventions and clarity
- Code complexity and maintainability
- Documentation and comments

**Security:**
- Potential security vulnerabilities
- Input validation issues
- Authentication and authorization concerns
- Data exposure risks

**Performance:**
- Inefficient algorithms or operations
- Memory usage concerns
- Database query optimization
- Caching opportunities

**Best Practices:**
- Language-specific best practices
- Design patterns usage
- Error handling
- Testing considerations

**Specific Issues:**
- Bugs or logical errors
- Edge cases not handled
- Potential runtime exceptions

Please provide:
1. A summary of overall code quality (1-10 scale)
2. Critical issues that must be fixed
3. Suggestions for improvement
4. Positive aspects worth highlighting

Code to review:
[PASTE_YOUR_CODE_HERE]
```

## Example Usage

```text
Please conduct a comprehensive code review of the following code. Analyze it for:

**Code Quality & Readability:**
- Code structure and organization
- Naming conventions and clarity
- Code complexity and maintainability
- Documentation and comments

[... rest of prompt ...]

Code to review:
function processUserData(userData) {
    if (userData) {
        const result = userData.map(user => {
            return {
                id: user.id,
                name: user.firstName + ' ' + user.lastName,
                email: user.email
            };
        });
        return result;
    }
}
```

## Expected Output

The AI will provide a structured review covering:

- Overall quality score and summary
- Specific issues categorized by type (security, performance, etc.)
- Actionable recommendations for improvement
- Code snippets showing better implementations
- Positive feedback on well-written parts

## Tested With

- [x] Gemini CLI
- [x] ChatGPT
- [x] Claude
- [ ] Other: ___________

## Tips

- Include context about the application/system when possible
- Specify the programming language if not obvious
- Mention any specific concerns or areas of focus
- For large codebases, review smaller chunks at a time
- Follow up with specific questions about suggested improvements

## Version History

- v1.0 - Initial comprehensive review template
