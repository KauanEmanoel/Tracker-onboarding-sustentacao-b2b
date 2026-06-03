# Tracker-onboarding-sustentacao-b2b
Dashboard em Excel para monitorar o ciclo de vida de implantações e reduzir o volume de chamados no suporte pós-entrega.
O Problema
Em empresas de software B2B, existe um padrão silencioso que custa caro: o cliente assina o contrato, passa pela implantação, e logo depois o time de suporte começa a receber um volume alto de chamados — muitos deles sobre funcionalidades que já foram "entregues".
Foi exatamente esse cenário que motivou este projeto.
A operação apresentava dois sintomas claros:

Prazos de implantação estourando com frequência, sem visibilidade sobre onde o atraso estava ocorrendo
Alto índice de chamados na Sustentação logo após a entrega, concentrados nos primeiros 60 dias de uso do cliente

O problema não era falta de esforço. Era falta de dados organizados num lugar só.

A Hipótese

Clientes com menor nível de treinamento abrem mais chamados no pós-implantação.

Antes deste projeto, essa hipótese existia como percepção da equipe — mas nunca havia sido validada com dados. Não havia cruzamento entre o status do treinamento e o volume de chamados por cliente.

A Solução
Desenvolvimento de um Dashboard de Monitoramento no Excel, com foco em três camadas:
1. Acompanhamento do Ciclo de Implantação

Status por etapa (Kickoff → Configuração → Treinamento → Go-live → Sustentação)
Prazo previsto vs. prazo realizado por fase
Indicador de desvio de prazo por cliente

2. Cruzamento: Treinamento × Chamados

Nível de conclusão do treinamento por usuário-chave do cliente
Volume de chamados abertos nos primeiros 30, 60 e 90 dias pós go-live
Correlação visual entre as duas variáveis

3. Alertas de Risco

Sinalização automática de clientes com implantação atrasada
Destaque para clientes com baixo nível de treinamento e alta taxa de chamados
Indicadores de saúde por conta (semáforo: Verde / Amarelo / Vermelho)


Ferramentas Utilizadas
RecursoAplicaçãoExcel (Tabelas Dinâmicas)Consolidação e segmentação dos dadosFormatação CondicionalAlertas visuais de risco e desvioGráficos de dispersãoCorrelação treinamento × chamadosFórmulas (SE, CONT.SES, DATADIF)Cálculo de prazos, desvios e classificações

O que Este Projeto Demonstra

Capacidade de transformar um problema operacional em estrutura analítica
Pensamento orientado a métricas e indicadores (KPIs de prazo, volume e qualidade)
Uso do Excel além do básico: modelagem de dados, dashboards e lógica condicional
Visão de causa e efeito — conectar treinamento com suporte não é óbvio até que os dados mostrem


Contexto
Este é um projeto fictício desenvolvido para fins de portfólio, baseado em um cenário realista do mercado de software B2B. Os dados utilizados foram gerados artificialmente para simular uma operação de implantação com 20 clientes ativos.
