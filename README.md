
# ChatBot CrossFit - WOD Wizard

Um chatbot baseado no modelo **Google Gemini**, focado em responder perguntas e gerar treinos (WODs) relacionados exclusivamente ao universo do **CrossFit**.

---

## Descrição do Projeto

Este projeto é um assistente virtual criado em um Jupyter Notebook, usando a API Gemini da Google para processar linguagem natural. O chatbot, chamado **WOD Wizard** ("Mago do WOD"), interage com o usuário, respondendo apenas questões relativas a CrossFit e auxiliando na criação de treinos.

O sistema rejeita qualquer pergunta fora do contexto do CrossFit para manter o foco e a qualidade das respostas.

---

## Tecnologias Utilizadas

- Python  
- Google Colab  
- Biblioteca `google.generativeai` (API Gemini)  
- Biblioteca `markdown` para formatação de respostas  
- Regex e manipulação básica de texto  

---

## Como usar

1. Configure sua chave da API Gemini como variável secreta no Google Colab (`SECRET_KEY`).  
2. Instale as dependências necessárias:
   ```bash
   !pip install gemini-api markdown
   ```  
3. Execute o notebook.  
4. Interaja com o chatbot via input no console do notebook:  
   - Faça perguntas relacionadas a CrossFit ou peça para montar treinos.  
   - Para encerrar a conversa, digite qualquer uma das palavras: `tchau`, `adeus`, `terminar`, `sair`, `finalizar`, `fechar`.  

---

## O que eu aprendi

- Como integrar a API Gemini em Python via `google.generativeai`.  
- Configuração e uso de variáveis secretas no Google Colab.  
- Criação de prompt contextualizado para controle do modelo de linguagem.  
- Manipulação de entrada e saída no ambiente de notebook.  
- Importância do controle de contexto para chatbots especializados.  

---

## Possíveis melhorias futuras

- Criar interface gráfica (web ou desktop) para interação mais amigável.  
- Adicionar memória de contexto para conversas mais naturais.  
- Suportar múltiplos usuários.  
- Expandir funcionalidades para incluir mais detalhes sobre treinos e dicas personalizadas.  

---

## Contribuindo

Pull requests e sugestões são bem-vindas! Abra uma issue para discutir novas funcionalidades ou bugs antes de grandes mudanças.

---

*Projeto pessoal para explorar IA conversacional aplicada ao universo CrossFit.*
