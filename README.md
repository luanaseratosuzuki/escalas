# Escalas

Site simples para divulgar escalas (louvor, mídia, recepção, kids…). Sem login: quem tem o link vê as escalas.

- Site: https://luanaseratosuzuki.github.io/escalas/
- Montar escalas: https://luanaseratosuzuki.github.io/escalas/montar.html

## Arquivos

- `index.html` — página pública. As pessoas filtram por ministério e digitam o nome para ver só as próprias escalas.
- `montar.html` — onde você monta as escalas e baixa o arquivo atualizado.
- `escalas.json` — os dados das escalas (é o único arquivo que muda no dia a dia).
- `style.css` — visual.

## Atualizar as escalas

1. Abra a página de montar escalas.
2. Edite, adicione cultos (o botão **Duplicar (+7 dias)** ajuda a repetir a semana).
3. Clique em **Baixar escalas.json**.
4. Aqui no GitHub: **Add file → Upload files** → arraste o `escalas.json` → **Commit changes**.
5. Em 1–2 minutos o site mostra a escala nova.

Dica: dá para mandar o link já filtrado para alguém: `https://luanaseratosuzuki.github.io/escalas/?nome=Ana`.

> A página de montar não tem senha, mas ela não altera nada sozinha. Só quem tem acesso a esta conta do GitHub consegue publicar mudanças.
