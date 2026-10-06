# Security and Privacy

This repository describes a real home platform. Public documentation therefore
uses stricter disclosure rules than an ordinary sample project.

## Never publish

- Credentials, tokens, cookies, pairing codes, or secret references
- Public or private IP addresses tied to the real environment
- Personal browser profiles, history, messages, or document contents
- Device names that reveal household layout or access patterns
- Unredacted logs, screenshots, backups, or configuration exports
- Employer information, systems, branding, or intellectual property

## Architectural safeguards

- Give capability nodes distinct identities and narrowly scoped routes.
- Keep browser automation in an isolated profile.
- Require explicit approval for external, destructive, or sensitive actions.
- Target individual entities rather than wildcard device groups.
- Prefer synthetic data when demonstrating retrieval and memory.
- Verify outcomes end to end after upgrades or configuration changes.

## Before publishing an artifact

1. Search for secrets and private network data.
2. Review screenshots manually, including browser chrome and notifications.
3. Replace identifiers with obvious examples rather than realistic-looking values.
4. Confirm that commands cannot mutate an unspecified target.
5. Test the instructions in a clean or disposable environment.
6. Document permissions, cleanup, and rollback.

## Reporting a problem

Do not open a public issue containing sensitive data. Until a dedicated security
contact is published, describe the problem without operational details and ask for
a private reporting channel.

