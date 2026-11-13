# SAST Implementation Using Psalm tool

## 1. Overview
A brief introduction to the lab, explaining the use of Psalm for static code analysis of a PHP application and its relevance to application security within a DevSecOps workflow.

## 2. Tools & Technologies
- Psalm – Static Application Security Testing
- PHP – Programming language
- Composer – Dependency management
- Linux – Testing environment


## 1. Installation and Initial Setup

| Commands | Purpose |
|---|---|
| `php --version` | Check installed PHP version. |
| `composer --version` | Check Composer installation. |
| `composer require --dev vimeo/psalm` | Install Psalm as a development dependency. |
| `./vendor/bin/psalm --version` | Display Psalm version. |
| `./vendor/bin/psalm --help` | Display available commands and options. |
| `./vendor/bin/psalm --init` | Generate a Psalm configuration file. |

Psalm's installation process involves installing the tool through Composer, generating its configuration file, and running an initial analysis.

# 2. Running Static Application Security Testing (SAST)

These commands are used to execute and customise static code analysis.

| Commands | Purpose |
|---|---|
| `./vendor/bin/psalm` | Analyse the configured PHP project. |
| `./vendor/bin/psalm --no-cache` | Run analysis without using cached results. |
| `./vendor/bin/psalm --debug` | Display debugging information. |
| `./vendor/bin/psalm --show-info=true` | Include informational issues in the output, where supported by your version. |
| `./vendor/bin/psalm filename.php` | Analyse a specific PHP file. |
| `./vendor/bin/psalm --config=psalm.xml` | Specify the configuration file to use. |


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
   
<p align="center">
  Check images to see the processes involved and scan them using VirusTotal:<br/>
<img alt="image" src="https://github.com/user-attachments/assets/825fa099-aa35-4509-83cf-995e1a7e1d7b" height="80%" width="80%"/>

<br />
<br />

   
4. Executed static code analysis.
5. Reviewed the reported findings.

**Command used:**
```bash
vendor/bin/psalm
```

## 5. Findings & Observations


## 6. Remediation



## 8. References
- [Psalm Official Documentation](https://psalm.dev/)
- [Psalm Configuration Guide](https://psalm.dev/docs/running_psalm/configuration/)
