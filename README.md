# WorkBuddy Skills

My personal collection of [WorkBuddy AI](https://www.workbuddy.cn) skills.

## Install a skill

Copy the skill folder into your user-level skills directory:

- macOS / Linux: `~/.workbuddy-ai/skills/<skill-name>/`
- Windows: `%USERPROFILE%\.workbuddy-ai\skills\<skill-name>\`

WorkBuddy AI picks up skills from that directory automatically — no restart needed.

## Skills

| Skill                                                    | Description                                                                                                     |
| -------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| [`high-value-life-guide`](skills/high-value-life-guide/) | High-Value Life Guide (高性价比人生指南). Delivers a curated "宝藏好物" resource collection via a Quark netdisk share link. |

## Adding a new skill

```
skills/
└── <skill-name>/
    └── SKILL.md      # YAML frontmatter (name, description) + instructions
```

The `name` field must match the folder name. The `description` field is what the  
agent matches against — put the trigger phrases there.

