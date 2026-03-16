<!-- Inspired by: https://contribute.cncf.io/projects/best-practices/security/security-hygiene/#3-securitymd -->
## Security vulnerabilities

Review how the agentregistry project handles the lifecycle of Common Vulnerability and Exposures (CVEs).

### 📨 Where to report

<!-- TODO: The agentregistry-vulnerability-reports@googlegroups.com Google group is not yet set up. -->
To report a security vulnerability, email the private Google group agentregistry-vulnerability-reports@googlegroups.com.

### ✅ When to send a report

Send a report when:
- You discover that an agentregistry component has a potential security vulnerability.
- You are unsure whether or how a vulnerability affects agentregistry.

### 🔔 Check before sending

If in doubt, send a private message about potential vulnerabilities such as:
- Any crash, especially in agentregistry.
- Any potential Denial of Service (DoS) attack.

### ❌ When NOT to send a report

Do not send a report for vulnerabilities that are not part of the agentregistry project, such as:
- You want help configuring agentregistry components for security purposes.
- You want help applying security related updates to your agentregistry configuration or environment.
- Your issue is not related to security vulnerabilities.
- Your issue is related to base image dependencies, such as AutoGen.

### Evaluation

The agentregistry team evaluates vulnerability reports for:
- Severity level, which can affect the priority of the fix
- Impact of the vulnerability on agentregistry code as opposed to backend code
- Potential dependencies on third-party or backend code that might delay the remediation process

The agentregistry team strives to keep private any vulnerability information with us as part of the remediation process. We only share information on a need-to-know basis to address the issue.
