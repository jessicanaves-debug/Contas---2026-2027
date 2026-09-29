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

**Com Google Sheets (automático):**
1. Suba `Contas_2026_2027.xlsx` no Google Drive → abrir com Planilhas Google → *Arquivo → Salvar como Planilhas Google*.
2. No Sheets: *Arquivo → Compartilhar → Publicar na Web* → Documento inteiro → **Microsoft Excel (.xlsx)** → Publicar. Copie o link.
3. No dashboard, clique em **Google Sheets**, cole o link e clique em **Conectar**.

A partir daí é só editar o Sheets e recarregar o dashboard (o Google leva alguns minutos para atualizar a versão publicada).

**Com o arquivo .xlsx:** clique em **Carregar arquivo** (ou arraste o arquivo para a página).

**GitHub Pages:** em *Settings → Pages*, escolha a branch `main` e a pasta `/ (root)`. O dashboard fica em `https://jessicanaves-debug.github.io/Contas---2026-2027/`. Atenção: o repositório é público, então os valores ficam visíveis para quem tiver o link.
