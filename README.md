# StudyAI Universal

Site baseado no StudyAI Espanhol, com escolha de 17 matérias, conteúdo e históricos separados por matéria, chat, resumos, flashcards, prática oral, tutor IA, simulados e plano de estudos com Gemini.

## Publicar em projeto NOVO no GitHub e Railway
1. Crie um repositório **novo** chamado `StudyAI-Universal` para não alterar o StudyAI Espanhol que já funciona.
2. Extraia o ZIP e envie os **arquivos separados** para a raiz do repositório (não envie só o ZIP).
3. Railway: New Project → Deploy from GitHub repo → `StudyAI-Universal`.
4. Build Command: `npm install`. Start Command: `npm start`. Node 20+.
5. Variables: `GEMINI_API_KEY` = chave secreta (nunca no GitHub); `GEMINI_MODEL` = modelo que já funciona no StudyAI Espanhol (opcional se o padrão funcionar).
6. Generate Domain, abra e teste cada ferramenta.

## Observações
- A escolha de matéria e os conteúdos/históricos ficam apenas no armazenamento local do navegador; não há contas nem sincronização.
- O botão Sabin Digital abre uma aba do portal; o StudyAI **não** lê o portal automaticamente nem pede login.
- Resumos, flashcards, simulados, chat, tutor e plano usam Gemini e podem estar sujeitos a cota, indisponibilidade ou erro de formato da IA.
- Reconhecimento de voz depende de permissão e compatibilidade do navegador.
- Questões e respostas geradas por IA precisam de revisão humana; especialmente em matérias exatas.
- Mantenha a chave apenas nas variáveis privadas do Railway e use o projeto com acompanhamento de um adulto responsável.

## Modo claro e escuro
Use o botão de tema na tela de matérias ou no topo do site. A preferência é salva no navegador e vale para todas as matérias.
