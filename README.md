# API Security Testing Lab

A practical API security testing project focused on understanding how
REST APIs can be assessed for authentication, authorization, input
validation, and access-control weaknesses.

## Objectives

- Understand REST API architecture
- Discover and map API endpoints
- Test authentication mechanisms
- Analyze authorization controls
- Identify broken object-level authorization
- Test JWT-based authentication
- Analyze API parameters and responses
- Document vulnerabilities and remediation

## Testing Areas

### API Reconnaissance

- Endpoint discovery
- HTTP methods
- Parameters
- API versioning
- Response analysis

### Authentication

- Login mechanisms
- Session handling
- JWT analysis
- Token validation
- Authentication bypass testing

### Authorization

- IDOR / BOLA
- Broken Function Level Authorization
- Privilege escalation
- Horizontal access-control testing
- Vertical access-control testing

### Input Validation

- Parameter manipulation
- Injection testing
- Unexpected input handling
- Content-Type testing

## Tools

- Burp Suite
- Postman
- cURL
- Nmap
- FFUF

## Testing Methodology

```text
API Discovery
      ↓
Endpoint Enumeration
      ↓
Authentication Analysis
      ↓
Authorization Testing
      ↓
Input Validation
      ↓
Vulnerability Verification
      ↓
Impact Analysis
      ↓
Remediation
      ↓
Security Report
