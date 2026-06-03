# Tracker-onboarding-sustentacao-b2b
Dashboard em Excel para monitorar o ciclo de vida de implantações e reduzir o volume de chamados no suporte pós-entrega.
O Problema

---

## 🚩 O Problema
Em empresas de **software B2B**, existe um padrão silencioso que custa caro para a operação:  
O cliente assina o contrato, passa pela implantação e, logo nas primeiras semanas, o time de suporte começa a receber um **volume altíssimo de chamados básicos**.

**Sintomas principais:**
- **Prazos de implantação estourando** frequentemente  
- **Alto índice de chamados na Sustentação (N1/N2)** nos primeiros **60 dias de uso**  
- **Falta de visibilidade** sobre a adesão real do cliente ao produto  

---

## 💡 A Solução e Arquitetura do Projeto
Desenvolvimento de uma solução de monitoramento focada em **cruzar dados de implantação com o comportamento pós-entrega**.  
O projeto foi estruturado utilizando boas práticas de modelagem de dados, dividindo a lógica em camadas:

1. **Cálculo Individual (Granular):**  
   Base detalhada por ID de Cliente para acompanhamento de desvios de prazo e geração de alertas automáticos (*"Notificar para conclusão"*) para clientes em **Risco Alto**.

2. **Cálculo de Grupos (Agregado):**  
   Isolamento das métricas globais de performance para alimentar o **painel gerencial**.

---

## 📈 Principais Insights e Resultados (Data Storytelling)
A partir dos dados analisados, foi possível estabelecer as seguintes métricas globais da operação:

| **Indicador** | **Resultado** |
|---------------|---------------|
| **Prazo Médio de Implantação** | 49 dias |
| **Taxa Média de Conclusão de Treinamento** | 71,3% |
| **Volume Médio de Chamados (60 dias)** | 11 chamados por cliente |

**Correlação Crítica:**  
A análise visual através do **gráfico de dispersão** confirmou a hipótese central do negócio:  
Existe uma **forte correlação negativa** entre a taxa de treinamento e o volume de suporte.

- Clientes com **maior taxa de conclusão de treinamento** → **queda drástica** no volume de chamados pós-entrega  
- Clientes com **baixa adesão ao treinamento** → **maiores ofensores** da fila de sustentação  

---

## 🛠️ Ferramentas e Técnicas Utilizadas
- **Google Sheets:** Estruturação de dados e criação das lógicas de negócio  
- **Arquitetura de Dados:** Separação clara entre tabelas de fatos (cálculos individuais) e agregações (médias de grupo)  
- **Fórmulas Lógicas e Condicionais (SE, E, OU):** Classificação automatizada de **Alerta de Risco** e regras de notificação  
- **Visualização de Dados (Gráfico de Dispersão):** Comprovação estatística e visual da correlação entre engajamento no treinamento e impacto no suporte operacional  

---

---

## 🛠️ Ferramentas Utilizadas
- **Excel (Tabelas Dinâmicas)** → Consolidação e segmentação dos dados  
- **Formatação Condicional** → Alertas visuais de risco e desvio  
- **Gráficos de dispersão** → Correlação treinamento × chamados  
- **Fórmulas (SE, CONT.SES, DATADIF)** → Cálculo de prazos e classificações
