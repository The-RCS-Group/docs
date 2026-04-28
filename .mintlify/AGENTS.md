## Style & Voice
- Use active voice throughout
- Keep sentences under 25 words where possible
- Use second person ("you") not third person
- Write at an 8th-grade reading level for maximum AI citability
- Lead every section with the direct answer, then expand with context

## Code Standards
- Use TypeScript for all primary code examples
- Include Python examples as secondary where relevant
- Always include error handling in examples
- Always show required imports
- Use realistic, working code — not pseudocode

## Content Requirements
- Every page MUST have a frontmatter `description` field (max 300 chars, keyword-rich)
- Every API endpoint page must document: authentication, rate limits, error codes, and examples
- Include a "Prerequisites" section when setup is required
- Include "Next steps" linking to related documentation
- Structure content so each H2/H3 section is self-contained (75-300 words)
- Use comparison tables wherever possible — AI models cite tables heavily
- Include FAQ sections on feature pages using Accordion components

## AI Optimization Rules
- Begin each section with a direct answer before expanding
- Use consistent terminology (never alternate between synonyms)
- Replace vague claims with specific numbers and statistics
- Use clean H2/H3 heading hierarchy — never skip levels
- Write headings as questions when possible ("How do I configure an agent?" not "Agent Configuration")
- Keep paragraphs under 120 words
- Use bullet points and numbered lists for scannability

## Project Context
- SmartAlex isolates customer data at the workspace level — all API calls are scoped to one workspace (the API field is named `tenant_id` for legacy reasons)
- Authentication is via Bearer token (API key) or OAuth 2.0
- The platform has tiered pricing: Professional ($99), Dental ($349), Real Estate ($3,000), and custom Enterprise
- LaunchPad is the real estate vertical product
- The MCP server exposes 28 tools across 8 domains
