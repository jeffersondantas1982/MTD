# 📊 Simulador de Programação Linear - Pesquisa Operacional

Este projeto foi desenvolvido como uma ferramenta prática para a disciplina de **Pesquisa Operacional**, focada na modelagem matemática para auxílio na tomada de decisão gerencial. O simulador permite testar diferentes cenários de produção, validando automaticamente se a estratégia é viável perante as restrições de recursos.

---

## 🎓 Contexto Acadêmico
* **Instituição:** Faculdade Anhanguera
* **Disciplina:** Pesquisa Operacional
* **Unidade:** U1_MODELAGEM NA TOMADA DE DECISÃO
* **Aula:** A4_APLICAÇÃO DE MODELOS EM PESQUISA OPERACIONAL
* **Aluno:** Jefferson Carvalho Dantas - 7º Período

---

## 🚀 Funcionalidades
O simulador apresenta dois modelos de Programação Linear lado a lado para análise comparativa em tempo real:

### 🔹 Modelo A: Fábrica de Móveis
Baseado em um cenário de produção de curto prazo com foco em limitações físicas de insumos.
* **Variáveis de Decisão:** Quantidade de cadeiras e mesas a serem produzidas.
* **Restrição de Madeira:** Disponibilidade máxima de 90 metros quadrados.
* **Restrição de Tempo:** Capacidade de montagem limitada a 600 minutos (10 horas).
* **Objetivo:** Maximizar o lucro diário (Lucro unitário: Cadeira R$ 40 | Mesa R$ 70).

### 🔹 Modelo B: Mix de Produtos P1 e P2
Baseado em um cenário de planejamento anual com foco em demanda de mercado.
* **Variáveis de Decisão:** Quantidade anual dos produtos P1 e P2.
* **Restrição de Capacidade:** Limite operacional de 1.200 horas anuais.
* **Restrição de Mercado:** Teto de demanda de 40 unidades para P1 e 30 unidades para P2.
* **Objetivo:** Maximizar o lucro anual (Lucro unitário: P1 1.000 | P2 1.800).

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica dos dados e do cabeçalho institucional.
* **CSS3:** Interface moderna com sistema de grids para comparação lado a lado e alertas visuais de status.
* **JavaScript (ES6):** Motor de cálculo responsável pelo processamento das inequações e validação instantânea de viabilidade.

---

## 📉 Como Utilizar
1. **Insira os valores** desejados nos campos de "Decisão de Produção" de cada modelo.
2. O sistema calculará o **Lucro Total (Z)** instantaneamente conforme os coeficientes de lucro.
3. A ferramenta realiza a validação das restrições:
   - ✅ **Verde (Viável):** A produção está dentro dos limites de recursos e demanda.
   - ❌ **Vermelho (Inviável):** A produção ultrapassa a capacidade disponível de matéria-prima, tempo ou mercado.

---

## ⚖️ Licença
Este projeto foi desenvolvido para fins acadêmicos. Sinta-se à vontade para clonar e utilizar como base para outros estudos de Pesquisa Operacional.
