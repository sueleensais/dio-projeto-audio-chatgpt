# Projeto Bootcamp Bradesco – GenAI & Dados

Este repositório contém o código desenvolvido durante o Bootcamp **"Bradesco - GenAI & Dados"**, baseado no material do professor, mas com algumas adaptações feitas por mim.

---

## 📌 Descrição

Este projeto demonstra como integrar **Speech-to-Text (voz para texto)** e **Text-to-Speech (texto para voz)** em uma conversa multi-idiomas com o ChatGPT, utilizando o **Whisper** da OpenAI para transcrição e o **Google Text-to-Speech (gTTS)** para síntese de voz.

O **Whisper** é um modelo de Reconhecimento Automático de Fala (ASR) treinado com 680.000 horas de dados multilíngues, robusto contra sotaques, ruídos e linguagem técnica. Em conjunto com o **ChatGPT**, ele permite transcrever e traduzir perguntas feitas por voz e gerar respostas inteligentes. Para fechar o ciclo, o **gTTS** transforma a resposta em áudio.

---

## 🔧 Alterações realizadas

Em relação ao código original do professor:
- Atualização da versão do modelo do ChatGPT (`gpt-4o-mini` ou `gpt-3.5-turbo` em vez de `gpt-4`).  
- Ajuste na forma de acessar a chave da OpenAI via **Secrets** do Google Colab (`OPENAI_API_KEY`).  
- Inclusão de **placeholders** nas Seções 3 e 4 para evitar erros quando não há créditos disponíveis na OpenAI.  

---

## 🚀 Tecnologias utilizadas

- **Google Colab** (ambiente de execução)  
- **Whisper** (Speech-to-Text)  
- **OpenAI API** (ChatGPT – com placeholders se sem créditos)  
- **gTTS** (Text-to-Speech)  

---

## ▶️ Como executar

1. Clone este repositório ou abra o arquivo `.py` no Google Colab.  
2. Configure sua chave da OpenAI nos **Secrets** do Colab com o nome `OPENAI_API_KEY`.  
3. Instale as dependências necessárias:
   ```bash

   !pip install openai openai-whisper gTTS
