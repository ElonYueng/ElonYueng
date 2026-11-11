# Shared skills

Sanitized, reusable skills extracted from verified assistant workflows. Each subfolder is one skill (`SKILL.md`).

- [定时任务回主对话执行](./skill-1794384595122/SKILL.md): when a scheduled job needs chat-reading or other tools only available in the bot's main conversation
- [例程交付先落盘再补发](./skill-1794384605906/SKILL.md): persist the full result, then send it; if the isolated run cannot deliver, the main conversation must send the full text
- [跨助手传递文件](./skill-1794384617697/SKILL.md): copy files into a shared workspace and verify them before another assistant continues
- [停止后台任务勿误伤同伴](./skill-1794384628932/SKILL.md): stop only the background task you started; do not use a global stop that also cancels other assistants' turns

Do not commit chat logs, private source indexes, credentials, or unsanitized user facts.
