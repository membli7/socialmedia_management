# Social Media Manager

A reusable Agent Skill for an AI agent acting as a business's professional social media manager.

## What it covers

- Social media strategy and business onboarding
- Platform-specific content planning and creation
- Publishing and scheduling through authorized integrations
- Community management and customer engagement
- Paid campaign planning and controlled execution
- Analytics, reporting, and continuous improvement
- Human approval, privacy, security, and accountability

## Install / use

This repository follows the Agent Skills convention:

```text
socialmedia_management/
└── SKILL.md
```

Install the skill using the mechanism documented by your agent platform. The skill directory should be named `social-media-manager` to match the `name` in the SKILL.md frontmatter when the platform enforces name matching.

If your platform does not support Agent Skills, provide the contents of `SKILL.md` as instructions or adapt them to that platform's supported configuration.

## Important limitations

This skill is an instruction package. It does **not** itself connect social accounts, grant permissions, provide platform APIs, store durable memory, or guarantee autonomous publishing. Actual posting, scheduling, messaging, advertising, and analytics require authorized integrations and account permissions.

The agent must report an action as published or scheduled only after the relevant platform confirms it. Human approval requirements should be configured for each business.

## Recommended setup

1. Load the skill in a compatible agent runtime.
2. Supply the business profile, approved brand guidelines, audience, goals, and content constraints.
3. Connect only the social accounts and analytics tools the agent is authorized to use.
4. Define approval rules, spending limits, escalation contacts, and timezone.
5. Test with draft-only work before granting publishing permissions.
6. Review audit records and performance regularly.

## Repository structure

- `SKILL.md` — the complete skill instructions.

## License

No license has been selected yet. Unless a license is added, normal copyright restrictions apply; public visibility on GitHub does not automatically grant permission to reuse or redistribute the contents.
