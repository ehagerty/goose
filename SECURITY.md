> [!CAUTION]
> Goose is a developer agent with access to a variety of systems that perform actions on behalf of the user on their local machine. Please be aware that since developer agents have the ability to run code and take actions on your computer, they pose a unique risk compared to chat based LLM interactions. While most foundational models include baseline protections against prompt injection, there is still inherent risk when using Goose to interact with the internet or through other untrusted data sources. To minimize these risks, consider taking the following precautions:
>
> - Use a dedicated virtual machine or container (Docker/Kubernetes) with limited privileged capabilities. This will minimize the risk of local system attacks or unintended access to critical system resources.
> - Always review the code and tests generated by Goose for accuracy.
> - Avoid providing Goose with sensitive or confidential information to prevent information leakage.
> - For any systems and actions that may result in significant changes, always require human confirmation.
> - If possible, break down complex Goose instructions into smaller, isolated operations. This reduces the risk of an errant command affecting multiple parts of the system at once and makes it easier to detect abnormal behaviour.
> - Only connect Goose with MCP extensions that you have reviewed
>
> In some circumstances, Goose may follow commands found embedded in content even if those commands conflict with the task given to Goose. We suggest taking the precautions above to limit risks from prompt injection. By taking these steps, you can reduce the potential security risks associated with developer agents and better protect your systems and users.
>
> Block recognizes the important contributions our open source community makes. Part of keeping Block and its customers safe is by making sure that we find and fix any security issues found in our open source projects. If you find a security vulnerability, we encourage you to privately report it in the repository’s Security tab -> Report a vulnerability.
>
> Please see [privately reporting a security vulnerability](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability#privately-reporting-a-security-vulnerability) for more information. For assistance or escalation, please contact the [Block Open Source Governance Committee](mailto:open-source-governance@block.xyz)
