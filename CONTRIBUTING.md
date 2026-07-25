# How to Contribute to NOVUS-OS Matrices

You can contribute by creating a new pull request or testing existing pull requests. Testing is very important and highly appreciated!

## General Rules for Game Matrices

- **Don't be afraid to submit PRs**. We welcome all contributions! Feel free to open a draft PR if your matrix isn't quite finished yet.
- **Keep it secure**. Do not include start scripts that a user can easily exploit. If a complex start script is needed, it should be heavily sanitized.
- **Keep it simple**. We don't need massive install scripts. Keep installation clean, optimized, and readable.
- **Keep it small**. Only download what is absolutely needed. Use standardized NOVUS-OS core Docker images.
- **Use Official NOVUS-OS Runtimes**. If you need a specific environment, use our official images. Self-hosted or undocumented third-party images will not be accepted for security reasons.
- **Export from the Panel**. Please use the NOVUS-OS panel tools to manage and export your matrix JSON files. This ensures the structure remains strictly compliant.

## Making a Pull Request

1. **Test Your Matrix**: Make sure your install process is rock solid. We will test matrices before they are merged.
2. **Make a Branch**: Please make a separate branch for your work (e.g., `feature/add-minecraft-bedrock`). Do not PR directly from your `main` branch.
3. **Open a PR**: [Click here to open a Pull Request](https://github.com/SGC-NOVUS/matrices/compare). Ensure your English `.json` matrix is properly formatted. 
4. **AI Security Audit**: All Pull Requests are subject to an automated AI security audit. The AI will scan your matrix for malicious scripts, insecure containers, and compliance with our guidelines. A detailed report will be generated and sent to our team.
5. **Localization is Automatic**: You DO NOT need to translate your matrix. Simply provide the English JSON, and the NOVUS-OS Compiler will automatically translate your matrix into all supported languages using Gemini AI when we merge it!

---

## Feedback & Support

Have ideas for improvement or found an issue? We are always open to suggestions!
- **Email:** contribute@sgc-novus.fun 
