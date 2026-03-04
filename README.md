# Calculadora de IR Cripto Brasil 2026 – Open Source

**Planilha gratuita e 100% local para calcular imposto de criptomoedas no Brasil.**

Feita para holders que querem declarar o IRPF sem erro, sem pagar ferramentas caras e sem enviar dados para a nuvem.

### Por que isso existe?
Todo mundo que tem cripto no Brasil sofre com a mesma dor:
- Vendas acima de R$ 35 mil no mês → tem que pagar DARF mensal (código 4600)
- Ganho de capital precisa ser calculado pelo método FIFO (primeiro que entra, primeiro que sai)
- Staking, recompensas DeFi, airdrops e NFTs também são tributados
- No final do ano, tem que preencher o GCAP e importar pro programa da Receita
- Ferramentas como Koinly, CoinTracker ou Accointing são boas, mas pagas e mandam seus dados pra fora

Essa calculadora resolve isso de forma simples:  
Você cola suas transações numa planilha → ela calcula tudo automático → você copia o resultado pro GCAP e pro IRPF.  
Tudo roda no seu computador ou celular, sem internet depois de baixar.

### O que a calculadora faz (versão atual)
- Calcula **ganho de capital** usando o método FIFO (o mais aceito pela Receita)
- Verifica se você passou dos R$ 35 mil em vendas no mês e simula o DARF
- Separa compras, vendas, staking e outros rendimentos
- Gera resumo mensal e anual pronto para copiar no programa GCAP
- Suporta múltiplas criptos (BTC, ETH, SOL, etc.) e exchanges BR (Mercado Bitcoin, Binance, Novadax, etc.)
- Totalmente offline após download – privacidade total

### Como usar (passo a passo simples)
1. Baixe a planilha:  
   → [Calculadora_IR_Cripto_Brasil_2026.xlsx] (clique para baixar)

2. Abra no Google Sheets ou Excel (recomendo fazer uma cópia para não perder sua versão)

3. Vá na aba **Transações** e cole seus dados:
   - Colunas: Data | Tipo (Compra / Venda / Staking / etc.) | Cripto | Quantidade | Preço Unitário BRL | Taxas BRL | Exchange/Wallet
   - Pode importar CSV direto da exchange e ajustar as colunas

4. A planilha calcula automático nas abas:
   - **Apuração FIFO** → mostra custo de aquisição e ganho por venda
   - **Resumo e DARF** → diz se tem imposto a pagar, quanto e código do DARF

5. Copie os valores para o programa GCAP da Receita e declare no IRPF normalmente

### Regras importantes 2026 (baseadas na Receita Federal)
- Isenção: vendas totais ≤ R$ 35.000 por mês (soma de todas as criptos)
- Acima disso: paga DARF mensal sobre o ganho (alíquota 15% a 22,5%)
- Método: FIFO é o padrão na prática (primeira compra é a primeira vendida)
- Staking e rendimentos DeFi: tributados como rendimento (Carnê-Leão ou tabela progressiva)
- Bens e Direitos: declare no IRPF se valor de aquisição ≥ R$ 5.000
- DeCripto (nova declaração obrigatória): a planilha já prepara os totais para ajudar

**Aviso importante:**  
Essa é uma ferramenta de apoio open source. Não substitui contador ou advogado tributário. Verifique sempre com a Receita ou profissional, pois regras podem mudar.

### Limitações atuais
- Ainda manual para colar transações (futuro: importação automática de CSV)
- Fórmulas FIFO básicas (funciona bem para maioria, mas casos muito complexos podem precisar de ajuste)
- Preços em BRL precisam ser inseridos ou atualizados manualmente

### Como contribuir
- Encontrou erro? Abra uma issue
- Quer melhorar fórmula? Faça pull request
- Tem ideia (ex: suporte a mais tipos de operação, gráficos, export PDF)? Sugira!
- Quer transformar em app (Python + Streamlit, por exemplo)? Forke e vá em frente

Licença: **MIT** – livre para usar, modificar e distribuir.

Feito por **Burguessemdinheiro** com carinho para a comunidade brasileira de cripto que cuida da própria chave.

Se te ajudou a não tomar multa boba no IR, dá uma estrela ⭐ no repo e compartilha com quem precisa!




APOIA-SE 
⚡ Bitcoin (BTC) – Lightning Network
solarclose35@walletofsatoshi.com

💵 USDT (Tether) rede Ethereum (ERC-20)
0x326c06B312A455b3c961746cB4c13ff7218Da616
