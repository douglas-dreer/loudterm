# Domain docs

This is a single-context repository.

Before exploring, read root `CONTEXT.md` and relevant decisions in `docs/adr/`
when they exist. If absent, proceed silently; create them lazily only when real
terms or durable decisions need recording. Do not generate architecture docs
just to satisfy this layout.

Use the glossary's vocabulary in code, tests, issues, and proposals. If a domain
concept is missing, note the gap rather than inventing competing terminology.
Flag conflicts with existing ADRs explicitly instead of silently overriding them.

Keep fixes proportionate to a small educational terminal/TTS project made for a
YouTube video and learning. Existing installation and dependency fixes are in
scope; broad platform guarantees or substantial new features require approval.
