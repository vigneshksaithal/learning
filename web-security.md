# Web Security

## XSS (Cross Site Scription)
- Consider user input as evil.
- Don't use innerHTML on user input, instead use textContent.
- Sanitize user inputs.

## Content Security Policy
Telling browsers which all resources to load.

## httpOnly Cookie
Set cookies to httpOnly.

## Data Validation
- Never ever trust any input coming from users.
- Always verify two things, type and size of data. e.g. password shouldn't be 5000 characters, username cannot be 0 characters.
- Always limit amount of data coming to your servers.
- Use data validators such as joi.dev.
