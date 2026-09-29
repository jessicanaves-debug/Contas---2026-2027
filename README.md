# Contas 2026–2027

Acompanhamento das contas da casa (Jessica & Pedro), de out/2026 a dez/2027.

| Arquivo | O que é |
|---|---|
| `Contas_2026_2027.xlsx` | A planilha. É aqui que você alimenta tudo. |
| `index.html` | O dashboard. Lê a planilha sozinho. |

## Como alimentar a planilha

Células **amarelas com texto azul** são as que você edita. O resto é fórmula.

- **Receitas**: salários, bônus recebido e quanto do bônus vai para as contas.
- **Contas Fixas**: casa, TIM, DAS, internet, água, luz, moto, Renner, roupinha. Se um valor mudar (ex.: DAS em 2027), edite daquele mês em diante. Há linhas em branco para contas novas.
- **Cartão**: parcelas que já existiam (Jessica e Pedro).
- **Compras Cartão**: cada compra nova no cartão (valor, nº de parcelas, mês da 1ª fatura). As parcelas se distribuem sozinhas nos meses.
- **Mercado & Alelo**: orçamento de mercado e valor do Alelo. O Alelo abate primeiro do mercado.
- **Provisões**: IPTU, IPVA e outros gastos anuais. A planilha separa um pouco por mês até o vencimento.
- **Metas**: valor que querem juntar, prazo, e quanto guardaram de verdade a cada mês.
- **Config**: a divisão da sobra (padrão: 30% guardar · 20% reserva para novas coisas · 50% livre).

**Resumo** e **Dashboard** (dentro do Excel) são automáticos.

## Como o dashboard atualiza

A planilha oficial fica no **Google Sheets**:
https://docs.google.com/spreadsheets/d/1OQJjkpmbjfMfUSEHpQCG0ciSFLo_9DL7vxVV5VmzIWg/edit

O `index.html` já lê essa planilha sozinho: edite o Sheets e recarregue o dashboard.
Para funcionar, o compartilhamento do Sheets precisa continuar como **"Qualquer pessoa com o link"**.

O arquivo `Contas_2026_2027.xlsx` deste repositório é só a versão inicial (backup). Também dá para carregar um .xlsx no botão **Carregar arquivo**.

**GitHub Pages:** em *Settings → Pages*, escolha a branch `main` e a pasta `/ (root)`. O dashboard fica em `https://jessicanaves-debug.github.io/Contas---2026-2027/`. Atenção: o repositório é público, então os valores ficam visíveis para quem tiver o link.
