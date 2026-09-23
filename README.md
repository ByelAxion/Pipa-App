# Pipa — Controle de Gastos v2

Projeto React com Vite, React e CSS puro. O app possui exatamente três telas controladas por estado interno: Dashboard, Adicionar movimentação e Resumo.

## Instalação e execução

Requer Node.js 18 ou superior.

```bash
npm install
npm run dev
```

Depois, abra o endereço local informado pelo Vite. Para produção, use `npm run build`.

## Funcionalidades

- Estado inicial vazio, sem lançamentos demonstrativos.
- Salário mensal, cor de destaque e dados persistidos no localStorage.
- Movimentações de Gasto/Despesa ou Entrada/Aumento, com descrição, valor, categoria e cor.
- Entradas aumentam o saldo; gastos reduzem o saldo.
- Validação de valores positivos e descrição obrigatória.
- Exclusão de movimentações com confirmação.
- Ciclo de 30 dias com início persistido em data ISO.
- Arquivamento automático ao completar o ciclo, sem duplicação após recarregar.
- Novo ciclo manual com confirmação e histórico contendo período, entradas, gastos e saldo restante.
- Gráfico de rosca e totais atualizados conforme as movimentações.
