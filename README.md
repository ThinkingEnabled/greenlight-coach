# Greenlight Coach

A free coach from [Thinking Enabled](https://thinkingenabled.com) that helps a leader turn a broad AI idea into **one workflow their team already does**, one question at a time, and leave with a one-page **Assessment Prep Brief** that separates evidence from assumptions.

The coach prepares; it doesn't decide. More about it, with a sample brief: <https://thinkingenabled.com/greenlight-coach>

## Use it in any AI chat

Copy [PROMPT.md](PROMPT.md) (also on <https://thinkingenabled.com/greenlight-coach#prompt>) and paste it as the first message of a new chat in ChatGPT, Claude, Microsoft Copilot, Gemini or another assistant. A pasted prompt lasts for that one chat. If the coach drifts, start a new chat and paste it again.

## Use it in Claude (claude.ai or the desktop app)

1. Download [Greenlight_Coach_for_Claude.zip](https://thinkingenabled.com/downloads/Greenlight_Coach_for_Claude.zip). Keep it zipped.
2. In Claude, open **Settings > Capabilities** and turn on **Code execution and file creation**.
3. Go to **Customize > Skills**, click **+**, choose **Create skill**, then **Upload a skill**, and select the file.
4. Start a new chat and say "Help me narrow a broad AI idea to one workflow."

Works on every Claude plan. On Team or Enterprise, an administrator may need to allow custom skills. See [Use skills in Claude](https://support.claude.com/en/articles/12512180-using-skills-in-claude).

## Use it in Claude Code

```
/plugin marketplace add ThinkingEnabled/greenlight-coach
/plugin install greenlight-coach@thinking-enabled
```

## Use it in ChatGPT

Until the ChatGPT listing is available, use the prompt above. The listing link will appear at <https://thinkingenabled.com/greenlight-coach>.

## Privacy and terms

The coach runs inside the AI app you use. It has no external service or account connection, so Thinking Enabled doesn't receive your conversation or your brief. Describe the work in general terms, use job roles instead of names, and leave out customer records and confidential details.

- [Privacy](https://thinkingenabled.com/privacy#greenlight-coach)
- [Terms of use](https://thinkingenabled.com/terms)
- [Support](https://thinkingenabled.com/greenlight-coach#support)

## Contents

- `PROMPT.md`: the copyable prompt for any AI chat
- `skills/greenlight-coach/SKILL.md`: the coach's instructions as a skill
- `.claude-plugin/`: plugin and marketplace files for Claude Code

© 2026 Thinking Enabled. All rights reserved. You may use the coach as described above.
