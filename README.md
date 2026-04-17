# ov-chat

A bilingual conversation practice skill for Claude Code that helps users practice English and Chinese through interactive dialogue with translation and grammar correction.

一个用于 Claude Code 的双语对话练习技能，通过翻译和语法纠正帮助用户练习中英文对话。

## Features / 功能特点

- **Bilingual Responses**: Every English response includes Chinese translation
  **双语回复**：每个英文回复都包含中文翻译
- **Grammar Correction**: Automatic detection and correction of grammar errors when you write in English
  **语法纠正**：当你用英文书写时，自动检测并纠正语法错误
- **Chinese Translation**: Your Chinese input is translated to English for learning purposes
  **中文翻译**：你的中文输入会被翻译成英文以便学习
- **Natural Conversation Practice**: Focus on practical, conversational language usage
  **自然对话练习**：专注于实用的、会话式的语言使用
- **Friendly Learning Environment**: Encouraging tone with clear explanations
  **友好的学习环境**：鼓励性的语气和清晰的解释

## Installation / 安装

### Install Globally (All Projects) / 全局安装（所有项目可用）

```bash
git clone https://github.com/Oveln/ov-chat ~/.claude/skills/ov-chat
```

### Verify Installation / 验证安装

After installation, verify that the skill is available:

安装后，验证技能是否可用：

```bash
# List all installed skills
# 列出所有已安装的技能
claude skill list
```

You should see `ov-chat` in the list of available skills.

你应该在可用技能列表中看到 `ov-chat`。

### Test the Skill / 测试技能

Once installed, test it in Claude Code:

安装完成后，在 Claude Code 中测试：

```
/ov-chat
Hello, how are you today?
```

You should receive a bilingual response with Chinese translation.

你应该会收到包含中文翻译的双语回复。

## How to Use / 使用方法

1. **Invoke the skill** by using the `/ov-chat` command in Claude Code
   **启动技能**：在 Claude Code 中使用 `/ov-chat` 命令

2. **Write in either language**:
   - **English**: I'll correct any mistakes and respond bilingually
   - **Chinese**: I'll translate your message and respond bilingually
   **用任一语言书写**：
   - **英文**：我会纠正任何错误并以双语回复
   - **中文**：我会翻译你的消息并以双语回复

3. **Practice naturally**: Talk about any topic you'd like to practice
   **自然练习**：谈论任何你想练习的话题

## Example Interactions / 交互示例

### When you write in English / 当你用英文书写时：

**You**: "I go to market yesterday and buy some apple."

**Me**:
```
Corrections:
- "I go to market yesterday" → "I went to the market yesterday" (past tense)
- "buy some apple" → "bought some apples" (past tense + plural)

That sounds like a productive day! Did you find everything you needed at the market?
那天听起来很充实！你在市场找到你需要的东西了吗？
```

### When you write in Chinese / 当你用中文书写时：

**You**: "我昨天去市场买了一些水果。"

**Me**:
```
Your message translated: I went to the market yesterday and bought some fruits.

That's great! Fresh fruits from the market are always wonderful. What kind of fruits did you buy?
太好了！市场上的新鲜水果总是很棒。你买了什么水果？
```

## Purpose / 目的

This skill is designed to help language learners:
- Improve their English grammar and vocabulary
- Practice Chinese translation and comprehension
- Build confidence in bilingual conversation
- Learn natural, conversational language usage

这个技能旨在帮助语言学习者：
- 提高英语语法和词汇
- 练习中文翻译和理解
- 建立双语对话的信心
- 学习自然的、会话式的语言使用

## Technical Details / 技术细节

- **Skill Type**: Claude Code Custom Skill
- **技能类型**：Claude Code 自定义技能
- **Invocation**: Manual only via `/ov-chat` command
- **调用方式**：仅通过 `/ov-chat` 命令手动调用
- **Languages Supported**: English and Chinese
- **支持的语言**：英语和中文
- **Primary Focus**: Conversation practice with grammar correction
- **主要重点**：带语法纠正的对话练习

## Learning Tips / 学习建议

1. **Write naturally**: Don't worry about making mistakes - that's how we learn!
   **自然书写**：别担心犯错——这就是我们的学习方式！

2. **Ask questions**: Feel free to ask about vocabulary, grammar, or cultural differences
   **提问**：随时询问词汇、语法或文化差异

3. **Practice regularly**: The more you practice, the more confident you'll become
   **定期练习**：练习得越多，你就会越自信

4. **Choose topics you care about**: Conversation flows better when discussing familiar subjects
   **选择你关心的话题**：讨论熟悉的话题时，对话会更流畅

## Contributing / 贡献

This is a personal language learning tool. Feel free to customize the skill settings to better fit your learning goals.

这是一个个人语言学习工具。随意调整技能设置以更好地适应你的学习目标。

---

Happy learning! / 祝学习愉快！
