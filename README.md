# ChatGPT Telegram Bot: **GPT-4. Fast. No daily limits. Special chat modes**

<div align="center">
<img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGZmdjZ0NGNjeXN6ajl3Mjl3ZjMxcjllZ2ZucWVia2o3dXN1dmJ2ZSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/poI06YUpmUKdpmnnqI/giphy.gif" align="center" style="width: 50%; border-radius: 20px" />
</div>

<br>



We all love [chat.openai.com](https://chat.openai.com), but... It's TERRIBLY laggy, has daily limits, and is only accessible through an archaic web interface.

This repo is ChatGPT re-created as Telegram Bot. **And it works great.**

You can deploy your own bot, or use mine: [Click Here](https://t.me/Master_AI_YESBHAUTIK_BOT)

## Features
- Low latency replies (it usually takes about 3-5 seconds)
- No request limits
- Message streaming (watch demo)
- GPT-4 support
- Group Chat support (/help_group_chat to get instructions)
- DALLE 2 (choose 👩‍🎨 Artist mode to generate images)
- Voice message recognition
- Code highlighting
- 15 special chat modes: 👩🏼‍🎓 Assistant, 👩🏼‍💻 Code Assistant, 👩‍🎨 Artist, 🧠 Psychologist, 🚀 Elon Musk and other. You can easily create your own chat modes by editing `config/chat_modes.yml`
- Support of [ChatGPT API](https://platform.openai.com/docs/guides/chat/introduction)
- List of allowed Telegram users
- Track $ balance spent on OpenAI API

<p align="center">
  <img src="https://github.com/Trendy-Trust/Master-AI-BOT/blob/66f5e01b26391c9076584b4c26ef61c27d9b0027/static/help_group.gif?raw=true" style="width: 50%; border-radius: 20px"/>
</p>

---

## Bot commands
- `/retry` – Regenerate last bot answer
- `/new` – Start new dialog
- `/mode` – Select chat mode
- `/balance` – Show balance
- `/settings` – Show settings
- `/help` – Show help

## Setup
1. Get your [OpenAI API](https://openai.com/api/) key

2. Get your Telegram bot token from [@BotFather](https://t.me/BotFather)

3. Edit `config/config.example.yml` to set your tokens and run 2 commands below (*if you're advanced user, you can also edit* `config/config.example.env`):
    ```bash
    nano config/config.yml
    nano onfig/config.env
    ```

4. 🔥 And now **run**:
    ```bash
    docker-compose --env-file config/config.env up --build
    ```


## References
1. [*Build ChatGPT from GPT-3*](https://learnprompting.org/docs/applied_prompting/build_chatgpt)

## 🔥 Show some support | Donation
If you find this repository helpful, show your support by giving it a 🌟! Your support means a lot to me and helps me keep contributing to the open-source community.

Also, if you'd like to support me financially, you can do so via my donation link: [https://go.yesbhautik.co.in/8i6wdu](https://go.yesbhautik.co.in/8i6wdu)
<br><br>
<a href="https://go.yesbhautik.co.in/8i6wdu">
  <img src="https://www.pngall.com/wp-content/uploads/2016/05/PayPal-Donate-Button-Free-Download-PNG.png" alt="Donate" width="100">
</a>

## 💬 Let's chat
Feel free to reach out to me if you have any questions, ideas or just want to chat. I'm always here to help and connect with the community.

## 📜 License
This repository is under the MIT License. For more information, see the [LICENSE](LICENSE) file.
