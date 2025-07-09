# ZEUS - Assistente de Voz com Gemini

> Seu oráculo digital. Sua voz, seu comando.

---

## Visão Geral

ZEUS é um assistente pessoal por voz em Python, que usa a API Gemini do Google para responder perguntas, reconhecer comandos, agendar lembretes e enviar e-mails — tudo ativado com a wake word “zeus”.

---

## Funcionalidades

- Wake word “zeus” (Vosk)
- Respostas por voz (pyttsx3)
- Integração com API Gemini
- Comandos: hora, data, abrir sites, tocar música
- Agenda de lembretes com APScheduler
- Envio de e-mails via Gmail API
- Interface gráfica opcional (Tkinter)
- Histórico de conversas salvo em JSON

---

## Instalação

1. Clone o repositório  
2. Crie e ative o ambiente virtual  
3. Instale dependências  
4. Configure `.env` com sua GEMINI_API_KEY  
5. Configure Gmail API (arquivo `credentials.json`)  

---

## Como usar

- No terminal: `python main.py`  
- Interface gráfica: `python interface.py`  
- Diga “zeus” para ativar o assistente

---

## Personalização Wake Word

Para mudar a wake word, edite o arquivo `wake_word.py`, alterando a palavra “zeus” para a sua preferida.

---

## Roadmap

- MVP com Gemini e wake word  
- Agenda e envio de e-mails  
- Wake word customizável  
- Integrações futuras

---

## Licença

MIT © Alexpel-tech
