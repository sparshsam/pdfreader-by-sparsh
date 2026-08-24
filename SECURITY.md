# Security

OpenReader is designed to process PDFs locally. It does not upload files or call network services.

If you discover a security issue, please report it privately — do not open a public issue.

Use GitHub's private vulnerability reporting:

1. Open the **Security** tab of this repository.
2. Click **Report a vulnerability**.
3. Complete the form with as much detail as you can provide.

Include: a clear description of the issue, reproduction steps, the OpenReader version or commit, and whether any PDF data could be exposed. Avoid sharing private or sensitive PDF files unless necessary.

## Supported Versions

Only the latest release is supported for security fixes.

## Handling Untrusted PDFs

OpenReader performs lightweight validation and resource checks before opening PDFs, but it is not a hardened sandbox. PDFs from unknown sources may still exercise vulnerabilities in PDF parsing libraries or stress local system resources.

For sensitive environments, open untrusted PDFs in an OS-level sandbox, virtual machine, or disposable user profile.
