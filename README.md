# medcontrol-bot
# Bot Especialista - MedControl

## Descrição do Projeto
Este projeto consiste no desenvolvimento de um assistente virtual especialista (chatbot) para o aplicativo **MedControl** (sistema de organização e lembrete de medicamentos). 

O bot utiliza a API do **Google Gemini** para responder dúvidas frequentes sobre as funcionalidades do aplicativo, planos e regras de privacidade. Além disso, possui uma regra de negócio implementada onde responde a até 3 perguntas do usuário e, na terceira interação, apresenta um resumo consolidado do atendimento e encerra a conversa.

---

##  Tecnologias Utilizadas
- **Python 3**
- **Google Gemini API** (`google-genai`)
- **Panel** (Interface gráfica interativa de chat)
- **Google Colab** (Ambiente de execução)

---

##  Como Executar o Projeto

1. **Abrir o Notebook:**
   - Baixe o arquivo `.ipynb` deste repositório e abra-o no [Google Colab](https://colab.research.google.com/).

2. **Configurar a Chave da API (Variável de Ambiente):**
   - Obtenha uma chave no [Google AI Studio](https://aistudio.google.com/).
   - No Google Colab, acesse o menu lateral esquerdo de **Segredos** (ícone de chave ).
   - Adicione um novo segredo com o nome `GOOGLE_API_KEY` e cole o valor da sua chave.
   - Ative a opção **Acesso ao notebook**.
   - *(O arquivo `env.example` na raiz do repositório serve como referência para os parâmetros de ambiente necessários)*.

3. **Execução:**
   - Execute as células em ordem sequencial.
   - Interaja com o chat gerado na última célula realizando até 3 perguntas para testar a regra de negócio e a consolidação do resumo final.
