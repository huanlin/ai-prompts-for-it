# API Documentation Generator

## Description

Generates comprehensive API documentation from code, including endpoints, parameters, responses, and usage examples. Perfect for creating professional API docs quickly and consistently.

## Category

- Primary: Writing
- Secondary: API Documentation

## Use Cases

- REST API documentation
- GraphQL API documentation
- SDK documentation
- Internal API documentation
- Public API reference creation

## Prompt

```text
Please generate comprehensive API documentation for the following code. Create professional documentation that includes:

**API Overview:**
- Brief description of the API's purpose
- Base URL and versioning information
- Authentication requirements
- Rate limiting information (if applicable)

**For Each Endpoint:**
- HTTP method and endpoint path
- Brief description of functionality
- Request parameters (path, query, body)
- Request headers required
- Response format and status codes
- Error responses and codes
- Usage examples with sample requests/responses

**Additional Sections:**
- Authentication guide
- Error handling patterns
- Common use cases
- SDK/client library information (if applicable)

**Format Requirements:**
- Use clear headings and subheadings
- Include code examples in appropriate syntax highlighting
- Provide both success and error response examples
- Use consistent formatting throughout
- Include table of contents for longer documentation

**Code to document:**
[PASTE_YOUR_API_CODE_HERE]

**Additional Context:**
- API Purpose: [DESCRIBE_WHAT_THE_API_DOES]
- Target Audience: [WHO_WILL_USE_THIS_API]
- Authentication Method: [AUTH_TYPE]
- Base URL: [BASE_URL_IF_KNOWN]
```

## Example Usage

```text
Please generate comprehensive API documentation for the following code. Create professional documentation that includes:

[... full prompt structure ...]

**Code to document:**
@app.route('/api/v1/users', methods=['GET'])
def get_users():
    page = request.args.get('page', 1, type=int)
    per_page = request.args.get('per_page', 10, type=int)
    users = User.query.paginate(page=page, per_page=per_page)
    return jsonify({
        'users': [user.to_dict() for user in users.items],
        'total': users.total,
        'pages': users.pages,
        'current_page': page
    })

@app.route('/api/v1/users/<int:user_id>', methods=['GET'])
def get_user(user_id):
    user = User.query.get_or_404(user_id)
    return jsonify(user.to_dict())

**Additional Context:**
- API Purpose: User management system for web application
- Target Audience: Frontend developers and mobile app developers
- Authentication Method: JWT Bearer tokens
- Base URL: https://api.example.com
```

## Expected Output

The AI will generate:

- Professional API documentation with clear structure
- Complete endpoint descriptions with all HTTP methods
- Detailed parameter documentation with types and requirements
- Sample request/response examples in JSON format
- Error handling documentation with status codes
- Authentication and usage guidelines
- Table of contents and navigation structure

## Tested With

- [x] Gemini CLI
- [x] ChatGPT
- [x] Claude
- [ ] Other: ___________

## Tips

- Include as much context as possible about the API's purpose
- Provide sample data structures if they're complex
- Mention any special authentication or security requirements
- Include information about rate limiting or usage restrictions
- Specify the target audience to adjust technical depth
- Request specific formats (OpenAPI, Markdown, etc.) if needed
- Ask for interactive examples or code snippets in specific languages
