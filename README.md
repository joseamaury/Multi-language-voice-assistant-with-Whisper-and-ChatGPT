# 🎙️ AI Voice Assistant API

> Um assistente de voz completo que captura áudio, transcreve, processa com IA e responde em voz — tudo de ponta a ponta.

---

## 📌 Sobre o Projeto

Este projeto implementa um **assistente de voz inteligente** utilizando tecnologias modernas de captura de áudio, reconhecimento de fala e inteligência artificial.

A solução permite que o usuário:

🎤 Fale diretamente no navegador  
🧠 Tenha sua fala transcrita com IA  
💬 Receba uma resposta inteligente do ChatGPT  
🔊 Ouça a resposta convertida em voz  

Tudo isso de forma fluida e automatizada.

---

## 🧠 Arquitetura da Solução

O projeto foi dividido em quatro etapas principais:

### 1️⃣ Captura de Áudio (Frontend + Backend)

- Utilização da **Web API MediaDevices** (JavaScript)
- Captura de áudio em tempo real no navegador
- Envio do áudio para o backend em Python
- Armazenamento e preparação do arquivo para processamento

---

### 2️⃣ Reconhecimento de Fala (Whisper)

- Uso do modelo **Whisper**
- Transcrição precisa de áudio para texto
- Suporte a múltiplos idiomas
- Alta robustez para diferentes sotaques e ruídos

---

### 3️⃣ Integração com IA (ChatGPT)

- Envio do texto transcrito para a API do ChatGPT
- Processamento da requisição em linguagem natural
- Geração de respostas inteligentes e contextuais

---

### 4️⃣ Conversão de Texto para Voz (gTTS)

- Uso da biblioteca **gTTS (Google Text-to-Speech)**
- Conversão da resposta em áudio
- Configuração de idioma e velocidade
- Retorno da resposta falada ao usuário

---

## 🔄 Fluxo da Aplicação

 id="flow"
Usuário fala 🎤  
   ↓  
Áudio capturado (JS)  
   ↓  
Backend Python recebe  
   ↓  
Whisper transcreve 🧠  
   ↓  
ChatGPT processa 💬  
   ↓  
gTTS gera voz 🔊  
   ↓  
Resposta retorna ao usuário

---


🛠️ Tecnologias Utilizadas
🔹 Backend
Python 🐍
Whisper (OpenAI)
gTTS
FastAPI / Flask (ajuste conforme seu caso)
🔹 Frontend
JavaScript
Web API MediaDevices
🔹 IA
API do ChatGPT

---


⚙️ Funcionalidades
✅ Captura de áudio via navegador
✅ Transcrição automática de fala
✅ Processamento com IA
✅ Resposta inteligente em texto
✅ Conversão de texto para voz
✅ Experiência completa de assistente virtual

---


▶️ Como Executar o Projeto
1. Clone o repositório
git clone https://github.com/seu-usuario/seu-repo.git
2. Acesse o diretório
cd seu-repo
3. Instale as dependências
pip install -r requirements.txt
4. Execute o servidor
uvicorn main:app --reload

---


🧪 Como Testar
Abra o frontend no navegador
Permita acesso ao microfone
Grave sua voz
Aguarde o processamento
Ouça a resposta gerada

---


📊 Estrutura do Projeto
📁 project/
 ├── frontend/
 │   └── audio_capture.js
 ├── backend/
 │   ├── main.py
 │   ├── whisper_service.py
 │   ├── chatgpt_service.py
 │   └── tts_service.py
 ├── audio/
 ├── requirements.txt
 └── README.md
 
---


🔒 Segurança e Boas Práticas
Validação de entrada de dados
Separação de responsabilidades (services)
Estrutura modular escalável
Preparado para autenticação futura

---


👨‍💻 Autor

José Amaury
📧 amaury345.ja@gmail.com
🔗 https://www.linkedin.com/in/joseamaury
🐙 https://github.com/joseamaury
