# Sakura Jarvis

Configuración de OpenClaw para el agente Sakura.

## Estructura
- `openclaw.json` — Config principal (sin tokens reales)
- `agents/sakura/SOUL.md` — Personalidad de Sakura
- Config real en `~/.openclaw/` del servidor

## Setup
1. Instalar OpenClaw: `npm install -g openclaw@latest`
2. Copiar `openclaw.json` a `~/.openclaw/` y rellenar tokens
3. Copiar `agents/sakura/SOUL.md` a `~/.openclaw/agents/sakura/`
4. `openclaw gateway start`
