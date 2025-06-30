# Systematic Debugging Assistant

## Description

A structured approach to debugging that helps identify root causes, analyze error patterns, and provide step-by-step troubleshooting guidance for various types of programming issues.

## Use Cases

- Runtime error troubleshooting
- Logic bug identification
- Performance issue diagnosis
- Integration problem solving
- Production incident analysis

## Prompt

```text
I need help debugging an issue. Please analyze the problem systematically and provide a structured troubleshooting approach.

**Problem Description:**
[DESCRIBE_THE_ISSUE_HERE]

**Error Messages/Symptoms:**
[PASTE_ERROR_MESSAGES_OR_DESCRIBE_SYMPTOMS]

**Code Context:**
[PASTE_RELEVANT_CODE_HERE]

**Environment Details:**
- Programming Language: [LANGUAGE]
- Framework/Libraries: [FRAMEWORKS]
- Operating System: [OS]
- Version Information: [VERSIONS]

**Steps Already Tried:**
[LIST_WHAT_YOU_HAVE_ALREADY_ATTEMPTED]

Please provide:

1. **Root Cause Analysis:**
   - Most likely causes of this issue
   - Why this error is occurring
   - Related components that might be affected

2. **Debugging Strategy:**
   - Step-by-step troubleshooting plan
   - What to check first, second, third, etc.
   - Debugging tools or techniques to use

3. **Immediate Actions:**
   - Quick fixes to try right now
   - Temporary workarounds if available
   - What to avoid doing

4. **Long-term Solutions:**
   - Proper fixes for the root cause
   - Code improvements to prevent recurrence
   - Best practices to implement

5. **Prevention:**
   - How to avoid this issue in the future
   - Testing strategies
   - Monitoring recommendations
```

## Example Usage

```text
I need help debugging an issue. Please analyze the problem systematically and provide a structured troubleshooting approach.

**Problem Description:**
My Node.js API is returning 500 errors intermittently, about 2-3 times per hour. The errors seem random and don't correlate with specific endpoints.

**Error Messages/Symptoms:**
Error: Cannot read property 'id' of undefined
    at /app/routes/users.js:45:12
    at Layer.handle [as handle_request] (/app/node_modules/express/lib/router/layer.js:95:5)

**Code Context:**
app.get('/users/:userId', async (req, res) => {
    try {
        const user = await User.findById(req.params.userId);
        const profile = await Profile.findOne({ userId: user.id });
        res.json({ user, profile });
    } catch (error) {
        res.status(500).json({ error: error.message });
    }
});

**Environment Details:**
- Programming Language: Node.js v16.14.0
- Framework/Libraries: Express 4.18.1, Mongoose 6.3.1
- Operating System: Ubuntu 20.04 (Docker container)
- Version Information: MongoDB 5.0

**Steps Already Tried:**
- Added try-catch blocks
- Checked database connectivity
- Reviewed recent code changes
```

## Expected Output

The AI will provide:

- Detailed analysis of the likely root cause (null user object)
- Step-by-step debugging plan starting with input validation
- Immediate fixes like null checks and better error handling
- Long-term solutions including database query optimization
- Prevention strategies like input validation and monitoring

## Tested With

- [x] Gemini CLI
- [x] ChatGPT
- [x] Claude
- [ ] Other: ___________

## Tips

- Be as specific as possible about the problem symptoms
- Include relevant error logs and stack traces
- Provide context about when the issue started occurring
- Mention any recent changes to code or environment
- Include sample data or inputs that trigger the issue
- Follow up with results of suggested debugging steps
