# Relatório de Análise de Dados – Academia

## Introdução

Este relatório tem como objetivo analisar os dados de uma academia fictícia, utilizando **SQLite** para armazenamento e **Python com Pandas, Matplotlib e Seaborn** para análise e visualização. Os dados foram inspirados no livro *"Fundamentos da Linguagem SQL"* de Thomas Nield, e a proposta é simular um cenário real para demonstrar habilidades com **SQL, ETL, análise exploratória e storytelling com dados**.

A base contém informações de alunos como nome, idade, sexo, plano contratado, status de pagamento, aulas realizadas, objetivo com a academia e classe de avaliação.

#### 🔗Link para o Notebook: https://jeferson-paz.github.io/academia-sql/alunos_academia.html
---

## Análise dos Dados

### 1. Quantidade Total de Alunos

- A base possui **100 alunos cadastrados**.

---

### 2. Distribuição por Plano de Academia

- A maioria dos alunos está no plano **Básico**, seguido pelos planos **Premium** e **VIP**.
  
![Gráfico - Alunos por Plano](imagens/quantidade_de_alunos_por_plano.png)

---

### 3. Objetivos dos Alunos

- Os objetivos mais comuns são:
  - **Emagrecimento**
  - **Ganho Muscular**
  - **Melhora da Saúde**
  - **Condicionamento Físico**

- A diversidade de objetivos mostra que a academia atende perfis variados.

![Gráfico - Objetivos](imagens/distribuição_dos_objetivos_dos_alunos.png)

---

### 4. Status de Pagamento

- Um número significativo de alunos está com pagamento **atrasado** ou **pendente**.
- Isso pode representar risco de evasão ou problemas financeiros para a academia.

![Gráfico - Pagamento](imagens/status_de_pagamento_dos_alunos.png)

---

- **Avaliação Geral da Academia:**
  - A maioria dos alunos avalia a academia como **"Regular"**, indicando insatisfação.
  - Existem também avaliações **"Excelente"** e **"Insatisfeito"**, que merecem atenção especial.

![Gráfico - Avaliação](imagens/distribuição_das_classes_de_avaliação.png)

---

### 6. Aulas Realizadas

- A maior parte dos alunos realizou entre **40 e 90 aulas**, indicando uma boa taxa de frequência.
- Alunos com maior participação tendem a estar nos planos VIP ou Basico.

![Gráfico - Aulas Realizadas](imagens/distribuição_de_aulas_realizadas_por_tipo_de_lano.png)

---

## Conclusões

1. **Engajamento**: A quantidade de aulas realizadas mostra que os alunos estão relativamente engajados.  
2. **Satisfação**: A maioria avalia positivamente a academia, mas há sinais de alerta com avaliações ruins.
3. **Risco de Churn**: Pagamentos atrasados ou pendentes podem indicar risco de **cancelamentos**.
4. **Planos mais atrativos**: O plano Básico domina, talvez por custo. Estratégias podem ser criadas para migrar alunos aos planos mais rentáveis.

---

## Recomendações Estratégicas

- **Campanhas de Reativação** para alunos com pagamento pendente.
- **Programa de Fidelidade** para os que realizam mais aulas (bonificação).
- **Pesquisas de Satisfação Detalhadas** para quem avaliou como “Regular” ou “Insatisfeito”.
- **Acompanhamento de Objetivos** com sugestões personalizadas de treino, dieta ou plano.
- **Oferta de Upgrade** de plano com desconto baseado em engajamento.

---

## Próximos Passos Técnicos

- Criar painéis interativos com **Power BI** ou **Tableau** conectando ao SQLite.
- Desenvolver alertas automáticos para inadimplência ou baixa frequência com Python.
- Realizar análise preditiva: **quais alunos têm maior risco de cancelar?**
- Enriquecer os dados com histórico de presença mensal ou uso de equipamentos.
