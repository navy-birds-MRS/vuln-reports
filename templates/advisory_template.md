# {{CVE_ID}} – {{Full Vulnerability Title}}

**Title:** {{Full Vulnerability Title}}  
**CVE ID:** {{CVE_ID}}  
**Vendor:** {{Vendor Name}}  
**Product:** {{Product Name}}  
**Hardware Version:** {{HW Version}}  
**Firmware Version:** {{Firmware Version}}  
**Status:** {{Reserved/Published}}  
**Severity:** {{CVSS Base Score}} ({{CVSS Vector}})  
**Discoverer:** {{Your Name}}  
**Public Date:** {{YYYY-MM-DD}}

---

## Summary
{{A clear, 3–4 sentence overview of the vulnerability — what it is, what happens, and its impact.}}

---

## Vulnerability Details

**Vulnerability Type:** {{Type (e.g., Improper Authentication, Command Injection, etc.)}}  
**Attack Vector:** {{Network/Local/Physical}}  
**Authentication Required:** {{Yes/No}}  
**User Interaction:** {{Yes/No}}  
**Affected Endpoint or Component:** `{{/path/to/endpoint}}`

### Technical Description
{{Explain how the vulnerability occurs. Include example HTTP requests, parameters, or configurations.  
Avoid including destructive exploit code; only safe demonstrations or pseudo-code.}}

Example:
```http
POST /boaform/getASPdata/new_formPasswordSetup
Host: <router-ip>
Content-Type: application/x-www-form-urlencoded

username=admin&password=newpassword
