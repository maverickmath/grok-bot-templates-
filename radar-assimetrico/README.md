# Radar Assimétrico

Um assistente que procura oportunidades assimétricas de renda e projetos (bounties de produto, conteúdo e dados, desafios, pesquisa paga, programas de early adopter, avaliação e red teaming de IA, marketplaces novos) e ordena por:

`score = ganho × probabilidade × (1 / tempo) × (1 / barreira) × fit com o seu perfil`

Cada fator vai de 1 a 5. O resumo semanal destaca o que dá para tentar em 30 a 60 minutos e o que pode se repetir.

## Como usar

1. Crie um assistente em qualquer plataforma que aceite instruções persistentes e acesso à web (o texto dos arquivos é independente de ferramenta).
2. Use `agent.json` para nome e descrição.
3. Cole `skills/primeira-conversa.md` como instrução de primeiro uso e `skills/radar-de-oportunidades.md` como a skill principal.
4. Agende a rotina descrita em `routine.md`.

## Regras que importam

- Nunca inventar valores, prazos ou status de abertura. Se não estiver claro, dizer isso e baixar a probabilidade.
- Preferir fontes primárias a agregadores.
- Pular bug bounty puramente de segurança, a não ser que você peça.
- Se não houver nada acionável, dizer em uma frase.
- Nunca enviar candidaturas ou mensagens em seu nome sem confirmação.
