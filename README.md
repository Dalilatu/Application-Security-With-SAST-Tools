# SAST Implementation Using Psalm tool

## 1. Overview
A brief introduction to the lab, explaining the use of Psalm for static code analysis of a PHP application and its relevance to application security within a DevSecOps workflow.

## 2. Tools & Technologies
- Psalm – Static Application Security Testing
- PHP – Programming language
- Composer – Dependency management
- Linux – Testing environment

## 3. Configuration
Briefly explain how Psalm was configured using `psalm.xml`.

Include:
- Target directory for code analysis.
- Excluded directories (e.g. `vendor`).
- Configured error reporting level.

**Evidence:** Screenshot of the XML configuration.

## 4. Implementation
Document the main steps performed:
1. Installed or verified Psalm.
2. Configured the analysis scope.
3. Executed static code analysis.
4. Reviewed the reported findings.

**Command used:**
```bash
vendor/bin/psalm
```

## 5. Findings & Observations
Briefly document:
- Issues identified by Psalm.
- Potential security weaknesses or coding defects.
- Relevant observations from the analysis.

Include screenshots of the scan results.

## 6. Remediation
Explain any issues you investigated and fixed.

Include a before-and-after result where applicable.

## 7. Key Takeaways
Summarise what you learned about:
- Static code analysis.
- Identifying potential weaknesses in PHP applications.
- The importance of integrating SAST into the SDLC.
- The role of automated security testing in DevSecOps.

## 8. References
- [Psalm Official Documentation](https://psalm.dev/)
- [Psalm Configuration Guide](https://psalm.dev/docs/running_psalm/configuration/)
