# Beat Challenge — Telegram

Jogo social para beatmakers em um Telegram Web App.

## Recursos
- desafios aleatórios de BPM, gênero, tonalidade, elemento obrigatório/proibido e tempo;
- submissão de beats por `file_id` do Telegram;
- votação entre participantes;
- XP e níveis;
- ranking;
- perfil do beatmaker;
- SQLite.

## Instalação
1. Instale Node.js 20+.
2. `npm install`
3. copie `.env.example` para `.env`;
4. coloque o token do @BotFather em `BOT_TOKEN`;
5. publique com HTTPS e coloque a URL em `WEBAPP_URL`;
6. `npm start`;
7. envie `/start` ao bot.

## Observação
A interface usa o Telegram Web App. Para produção, valide criptograficamente `initData` no backend, aplique autenticação, rate limiting, moderação de áudio e armazenamento apropriado.

O projeto não implementa apostas, depósitos, saques ou prêmios em dinheiro.