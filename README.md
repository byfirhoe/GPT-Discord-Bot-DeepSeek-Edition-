# 🤖 GPT Discord Bot (DeepSeek Edition)

Un bot de Discord que utiliza el modelo `deepseek-chat` para mantener conversaciones naturales y continuar contextos en tiempo real. Este bot responde a los mensajes enviados en canales específicos o cuando se le menciona, simulando una personalidad amigable y orientada al roleplay.

## ✨ Características

- 💬 Conversación contextual basada en los últimos 10 mensajes del canal.
- 🤖 Integración con la API de DeepSeek mediante el SDK de OpenAI.
- 🧠 Personalidad configurable desde el mensaje del sistema.
- 🔁 Ignora mensajes con un prefijo (`!`) y los de otros bots.
- 📡 Indica que está escribiendo (`sendTyping`) durante el procesamiento.
- 🧵 Divide respuestas largas en múltiples mensajes para respetar el límite de Discord (2000 caracteres).

## 🔧 Requisitos

- Node.js v18 o superior
- Cuenta en [DeepSeek](https://deepseek.com) u [OpenRouter](https://openrouter.ai)
- Token de bot de Discord
- Clave API de DeepSeek u OpenRouter

## 📁 Estructura

- `index.js`: Lógica principal del bot.
- `.env`: Contiene variables sensibles como `TOKEN` y `OPENAI_KEY`.

## 🚀 Instalación

```bash
git clone https://github.com/tuusuario/discord-gpt-bot
cd discord-gpt-bot
npm install
cp .env.example .env
# Luego edita .env y coloca tu TOKEN y OPENAI_KEY
node index.js
```
