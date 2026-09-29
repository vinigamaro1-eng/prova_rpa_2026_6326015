# Ficha de Avaliação de Processo (PDD) — Questão 5

> MOLDE. Copie para `entregas/SEU_RA/` e preencha. Escolha **um** cenário (A ou B).

**Cenário escolhido:** <A ou B>

1. **Nome do processo e descrição resumida:**
   Conciliação Bancária Diária. Comparar as transações do extrato bancário em CSV com as baixas registradas no ERP, usando CNPJ e valor.
2. **Volume / frequência estimados:**
   Diariamente, em dias úteis, com aproximadamente 200 a 500 linhas para conferir.

3. **As entradas são estruturadas?** (sim/não + justificativa)
   Sim. O extrato possui colunas definidas, como data, CNPJ e valor, e os registros do ERP podem ser consultados em formato tabular.

4. **As regras são claras e determinísticas?** (sim/não + justificativa)
   Sim. Uma transação é conciliada quando há um registro correspondente no ERP com o mesmo CNPJ e valor. Divergências ou correspondências duplicadas são encaminhadas para revisão humana.

5. **Veredito — o processo é elegível a RPA?** (justifique com base em regras
   claras, dados estruturados e repetibilidade)
   Sim. O processo é repetitivo, trabalha com dados estruturados e segue regras objetivas, sem depender de julgamento subjetivo. O volume diário também torna a automação útil. casos ambíguos podem ser separados para análise humana
