# 💈 Chatbot Will Black

Chatbot interativo desenvolvido com base em **Modelos de Linguagem (LLMs)** para simular o atendimento de uma barbearia. O projeto utiliza a API do Google Gemini para criar uma experiência conversacional natural, permitindo que clientes consultem serviços, preços e horários de forma automatizada.

---

## 🧠 Sobre o Projeto

O **Will Black** é um chatbot especialista em domínio fechado, projetado para responder apenas com base em informações previamente definidas, evitando respostas imprecisas (alucinações).

O sistema conduz o usuário por um fluxo controlado de interação, coletando informações essenciais para um atendimento simulado em uma barbearia.

---

## 🎯 Objetivo

* Simular um atendimento real de barbearia
* Responder dúvidas sobre:

  * Tipos de corte
  * Preços
  * Horários disponíveis
* Coletar informações do usuário durante a conversa
* Gerar um resumo estruturado ao final da interação

---

## ⚙️ Funcionalidades

* 💬 Conversa interativa via terminal
* 🧠 Uso de LLM (Google Gemini)
* 🔒 Domínio fechado (sem alucinações)
* 🔄 Controle de fluxo (3 interações)
* 📊 Geração de resumo final em formato JSON

---

## 🏗️ Tecnologias Utilizadas

* Python
* Google Gemini API (`google.genai`)
* Prompt Engineering

---

## 🔁 Fluxo de Funcionamento

1. O chatbot inicia o atendimento
2. O usuário realiza até 3 interações
3. O sistema responde com base no contexto definido
4. Ao final:

   * Um resumo da conversa é gerado
   * Os dados são estruturados em JSON

---

## 📦 Exemplo de Saída

```json
{
  "haircut": "Degradê",
  "price": "R$ 30",
  "schedule": "Sexta-feira à tarde"
}
```

---

## 🚀 Como Executar

1. Configure sua API Key do Gemini no ambiente (Google Colab ou local)
2. Execute o script Python
3. Interaja com o chatbot via terminal

---

## 📌 Observações

Este projeto foi desenvolvido como atividade acadêmica com foco em:

* Aplicação de conceitos de Inteligência Artificial
* Uso de Prompt Engineering
* Desenvolvimento de chatbots com controle de fluxo
