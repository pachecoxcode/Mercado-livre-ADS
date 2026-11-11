---
name: Mercado-livre-ADS
description: >-
  Use ao analisar, diagnosticar ou propor melhorias em anúncios, campanhas de
  Mercado Ads (Product Ads), experiência de compra, preço, margem ou logística
  no Mercado Livre — base de conhecimento de 6 canais do YouTube + regras
  oficiais do ML.
---
# Mercado-livre-ADS (anúncios, Ads, experiência, margem)

Base destilada de ~300 vídeos de @gabrielcazonato (GC), @market-facil (MF), @roderjansvolinski (RV), @onicanal (ON), @ecommercepuro (EP), @zedoecom (ZE) e das páginas oficiais do Mercado Ads/Central de Vendedores (estudo de nov/2026). Fontes completas com URL de cada vídeo:
- `/workspace/estudo-youtube-ml/base-conhecimento-ml.md` (conhecimento geral, por tema)
- `/workspace/estudo-mercado-ads/relatorio-estudo-mercado-ads.md` (Ads, regras oficiais R1–R16)
- Transcrições: `/workspace/estudo-youtube-ml/<canal>/transcricoes/` e `/workspace/estudo-mercado-ads/transcricoes/`

## Regras de uso
- Este playbook gera **diagnóstico e propostas**. Nunca alterar anúncio, preço, campanha, foto ou título sem aprovação expressa do dono da conta, nas palavras dele.
- Separe sempre: REGRA OFICIAL (com link) · DADO DO PAINEL · CÁLCULO · HIPÓTESE (opinião de canal) · NÃO CONFIRMADO.
- Quando canal e regra oficial divergem, **prevalece a oficial**.
- Números de criadores ("MC mínima 20%", "R$ 0,40/dia") são prática deles, não regra do ML.

## 1. Algoritmo e ranqueamento
- **Conversão é a métrica nº 1.** Anúncio exibido que não vende cai e dificilmente volta; os primeiros dias são críticos. +0,5 p.p. de conversão (1%→1,5%) = +50% vendas sem mais mídia.
- Medir posição pelo termo **mais genérico**, não pelo título.
- Anúncio parado 30+ dias sem estoque: avaliar anúncio novo em vez de reativar (GC).
- Não subir preço para segurar estoque (destrói posicionamento).
- **Tags ocultas** no código da página (F12, buscar): `res_limited_marketplace_visibility`, `incomplete_technical_specs`, `moderation_penalty`, `pending_documentation` (MF).
- **Checklist de queda de vendas (MF):** visitas caíram → exposição (palavras, fotos, condição comercial, experiência, medalha). Visitas normais e vendas caíram → conversão/condição comercial. Conferir: anúncio pausado com estoque, Full indisponível, frete simulado em vários CEPs (aba anônima), campanha criada pelo ML, preço/título/ficha/peso alterados, documentação pendente.

## 2. Título e SEO
- ML indexa **título + todos os campos da ficha técnica**; essas palavras também guiam o Ads.
- Título com **diferenciais** que o concorrente não tem, complementando a capa.
- **Não mexer no título de anúncio que vende** (MF: reseta orgânico e Ads — NÃO CONFIRMADO oficialmente; tratar com cautela). Para destravar, mexer em ficha.
- Divergência de tamanho: ~50–60 caracteres escolhidos (GC, MF) vs até 120 (ON). Limite varia por categoria.
- O ML às vezes corta títulos/apaga descrições por bug: revisar periodicamente.

## 3. Fotos e clips
- **Capa ganha o clique**: produto grande, contraste; cuidado com o **zoom automático** do ML. Conferir regra de capa da categoria.
- **Fotos 2–6 quebram objeções**: medidas, compatibilidade, o que vem na caixa, comparativo, infográfico. Responda nas fotos as perguntas repetidas — o comprador não lê descrição.
- Nada nas fotos que o produto não entregue (gera devolução por expectativa). Evitar marcas/IP de terceiros.
- **Clip vertical** gravado no celular, produto em uso, costuma vencer o de estúdio; testar vários.

## 4. Ficha técnica e descrição
- Preencher **todos** os campos; usar para termos que não estão no título (não repetir).
- Descrição **não entra na busca**, mas converte e é **prova em reclamação**. Deve ser honesta: compatibilidade, o que vem na caixa, como usar, limitações.
- Garantia preenchida ajuda o posicionamento.

## 5. Catálogo
- Mais exposição, porém briga de preço. **Catálogo fora do preço nem entra no leilão do Ads.**
- Evitar catálogo de marca registrada que não é sua (denúncia/risco de conta).
- Concorrentes ruins no catálogo derrubam a confiança → marca/catálogo próprio.
- Ganhar o catálogo não garante visibilidade (oficial).

## 6. Preço e promoções
- Entrar competitivo; **não** inflar preço cheio para dar desconto grande (ao sair da promo o algoritmo lê +100%).
- Depois de posicionado, subir aos poucos (GC: R$ 0,40–0,50/24h; até ~3% em ticket alto). RV: saltos conforme o mercado.
- Subir preço pode reduzir devoluções (melhor público) — ON.
- "Melhor baixar preço do que socar publicidade" (ZE).

## 7. Mercado Ads (Product Ads)
### Regras oficiais
- Cobrança **por clique**. Um anúncio só pode estar em **uma campanha por vez**. Uma campanha automática (pausável, não excluível).
- **Não há palavra-chave, negativação nem público** no Product Ads. Controles: quais anúncios entram, **ROAS objetivo (1x–35x)** e **orçamento médio diário (não cumulativo)**. Segmentação = estrutura de campanhas + qualidade/SEO do anúncio. Filtros de público só no Brand Ads.
- Leilão = ROAS objetivo (menor → mais flexibilidade de lance) × relevância (qualidade, vendas). ACOS = 100 ÷ ROAS (10x = 10%; 14x ≈ 7,1%; 16x = 6,25%).
- ROAS baixo → mais alcance e volume, menos margem por venda. ROAS alto → mais margem, menos volume.
- **Impressões: ganhas + perdidas por orçamento + perdidas por classificação = 100%.** Por orçamento → aumentar orçamento. Por classificação → **melhorar o anúncio ou baixar o ROAS**; orçamento não resolve. "Campanha não gasta" = ROAS alto demais ou anúncio fraco.
- Aprendizagem: evitar mexer/pausar campanha nos **primeiros 30 dias**; se um anúncio só gasta, pausar o anúncio, não a campanha. Atribuição: **janela de 14 dias**.
- Datas fortes (Black Friday, Cyber Monday, Natal): aumentar orçamento **com antecedência**.
- Estrutura: 15–30 anúncios com preço e margem semelhantes por campanha (oficial); 5–20 (GC); 10–15 (ON). Com poucos SKUs, campanha por produto é aceitável (GC).
- 40% das vendas atribuídas vêm de fora da busca.
### Diagnóstico prático
1. Abrir "Desempenho ao competir por impressões" antes de mexer. O selo "Excelente" não garante nada.
2. Ler o funil: **CTR baixo = problema visual** (capa, preço, promo invisível). **Clique sem venda = problema de oferta** (fotos, ficha, dúvidas, prazo). Julgar com 100–200 cliques. Conversão <1% ruim, >3% boa (varia por nicho).
3. Selo "Não se pode mostrar" (experiência, foto ruim, penalidade) = fora do leilão.
4. Analisar no **nível do anúncio** quando o total da campanha mistura histórico de anúncios removidos.
5. Não seguir sugestão automática do painel ("aumente para R$ X") sem conferir se o gasto real bate no teto. Preferir campanhas manuais; evitar automática "em alta" e orçamento compartilhado (MF, NÃO CONFIRMADO oficialmente).
6. Prefira **modificar a campanha existente** a criar outra (perde histórico/aprendizagem).
7. Acompanhar **TACOS** (Ads ÷ faturamento total) da conta; referência ~3%.
### Fases do produto (RV)
1. Lançamento: ROAS baixo, orçamento baixo, preço baixo, Full; objetivo vender e ganhar avaliações. 2. Crescimento: zero a zero já é bom. 3. Ranqueado: não desligar; testar semana a semana o ROAS mais alto sem perder lucro total.
### Divergências (prevalece oficial)
- Orçamento acumula? GC sim / oficial não.
- Perda por classificação: GC sobe ROAS / MF e oficial baixam ROAS ou melhoram anúncio.
- Perda por orçamento: ON sobe ROAS até parar / oficial aumenta orçamento.
- Prazo para julgar: MF minutos, GC 7d, ZE 28d / oficial 30d.
- Cobrança: RV "% do faturamento" / oficial por clique.
- Ads fora do Full: GC jamais / RV com Flex / MF desde o dia 1.

## 8. Experiência de compra e devoluções
- Faixas oficiais: **Boa 75–100 · Mediana 50–74** (perde exposição, risco de pausa) · **Ruim ≤30**. MF: abaixo de 30 o anúncio some e **não pode usar Ads**. Kits herdam a pior nota.
- Entram: reclamações, cancelamentos do vendedor, atrasos, demora em responder, perguntas/opiniões, título ou descrição inconsistentes. Com <100 vendas em 60 dias, usa-se 1 ano e a categoria.
- Em categoria com muita reclamação (eletrônico que exige configuração), uma reclamação derruba anúncio novo.
- **Pedir remoção de impacto injusto** via chamado (funcionou por telefone, MF), com argumento factual (pode redigir com IA).
- Disputas: primeira mensagem "matadora" com evidências — vídeo da embalagem sem cortes, peso antes/depois, print do anúncio e da ficha, perguntas pré-venda, NF.
- Atraso da coleta: chamado no mesmo dia + protocolo.
- Muitas devoluções são **por expectativa**: corrigir fotos 2–3, ficha e descrição.
- Fornecedor 10% mais barato pode custar 20% em devolução.
- Riscos de conta: produto falso, TV Box, produtos proibidos, compras de amigos para reputação.
### Roteiro para anúncio com experiência ruim
1. Abrir o detalhe das devoluções/reclamações e classificar: injustas (transporte, arrependimento, erro do comprador) × por expectativa × defeito.
2. Injustas → pedir remoção do impacto com evidências.
3. Expectativa → propor ajuste de fotos, ficha e descrição (sem mexer no título).
4. Defeito → revisar fornecedor/teste antes do envio.
5. Aplicar a mesma correção a anúncios do mesmo produto.
6. Só voltar a investir em Ads depois que a nota subir.

## 9. Full e logística
- Grandes vendedores fazem 80–97% das vendas no Full. Testar e ranquear produto novo direto no Full (GC).
- Não deixar Flex ligado em anúncio que está no Full (RV).
- Full indisponível por bug: tirar e recolocar. ML pode alterar peso/medidas e encarecer o frete.
- Desde 24/08/2026 o frete depende de peso × faixa de preço; acima de R$ 79, frete grátis pago pelo vendedor.

## 10. Margem e cálculo de lucro com Ads
- Lucro por venda = preço − custo − tarifa ML − frete − imposto − (preço ÷ ROAS).
- **ROAS de equilíbrio** = preço ÷ (margem antes do Ads).
- Ao comparar ROAS A (atual) vs B (mais alto): ROAS B só dá mais lucro total se mantiver pelo menos `lucro_A ÷ lucro_B` do volume de A. Testar em degraus (ex.: 10x → 12x → 14x), 14 dias cada, critério = **lucro total**, não visitas.
- Considerar ~10% de imposto (RV); no Simples a alíquota sobe com o faturamento (GC). Confirmar a alíquota real.
- Referências: margem livre 10–11% com ~3% de Ads (RV); margem pós-Ads >10% aceitável, >15% ideal (ON); MC ~20–22% mínima (GC); MC 28% com líquido ~10% excelente (EP).
- Usar o preço líquido **real dos pedidos** (promoções, cupons), não o preço de vitrine.

## 11. Atendimento
- Perguntas repetidas = informação faltando → responder nas fotos.
- Inconsistência entre título, ficha e fotos confunde e gera devolução.
- Tempo de resposta a perguntas/reclamações pesa no Ad Score e na experiência; responder também no fim de semana.
- Ter respostas padrão confirmadas para dúvidas recorrentes (evitar respostas contraditórias).

## Formato de entrega
- Diagnóstico curto com dados (marcando a origem de cada número) → causa provável → propostas numeradas (ex.: ANUNCIO-XXX / ADS-XXX) com ação exata, justificativa, risco, métrica de sucesso, reversão e prazo → aguardar APROVAR / REJEITAR / REVISAR.
