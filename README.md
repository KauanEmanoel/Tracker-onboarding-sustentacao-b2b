# Tracker-onboarding-sustentacao-b2b
Dashboard em Excel para monitorar o ciclo de vida de implantações e reduzir o volume de chamados no suporte pós-entrega.
O Problema

O Problema
Em empresas de software B2B, existe um padrão silencioso que custa caro:
O cliente assina o contrato, passa pela implantação, e logo depois o time de suporte começa a receber um volume alto de chamados — muitos deles sobre funcionalidades que já foram entregues.

Sintomas principais:

Prazos de implantação estourando com frequência

Alto índice de chamados na Sustentação nos primeiros 60 dias de uso

A Hipótese
Clientes com menor nível de treinamento abrem mais chamados no pós-implantação.
Essa percepção nunca havia sido validada com dados até este projeto.

A Solução
Desenvolvimento de um Dashboard de Monitoramento no Excel, com foco em três camadas:

Acompanhamento do Ciclo de Implantação

Status por etapa (Kickoff → Configuração → Treinamento → Go-live → Sustentação)

Prazo previsto vs. prazo realizado

Indicador de desvio de prazo por cliente

Cruzamento: Treinamento × Chamados

Nível de conclusão do treinamento por usuário-chave

Volume de chamados nos primeiros 30, 60 e 90 dias

Correlação visual entre variáveis

Alertas de Risco

Clientes com implantação atrasada

Baixo treinamento + alta taxa de chamados

Indicadores de saúde (semáforo: Verde / Amarelo / Vermelho)

Tabela de KPIs
Indicador	Descrição	Meta
Prazo médio de implantação	Tempo médio entre Kickoff e Go-live	≤ 45 dias
Chamados pós-entrega (60 dias)	Volume de chamados por cliente	≤ 5
Taxa de conclusão de treinamento	% de usuários-chave treinados	≥ 80%
Desvio de prazo	Diferença entre prazo previsto e realizado	≤ 10%


Ferramentas Utilizadas
Excel (Tabelas Dinâmicas): Consolidação e segmentação dos dados

Formatação Condicional: Alertas visuais de risco e desvio

Gráficos de dispersão: Correlação treinamento × chamados

Fórmulas (SE, CONT.SES, DATADIF): Cálculo de prazos, desvios e classificações

Exemplo Visual do Dashboard
O que Este Projeto Demonstra
Transformação de problema operacional em estrutura analítica

Pensamento orientado a métricas e indicadores

Uso avançado do Excel para dashboards e lógica condicional

Visão de causa e efeito — dados revelando a conexão entre treinamento e suporte

Contexto
Este é um projeto fictício desenvolvido para fins de portfólio, baseado em um cenário realista do mercado de software B2B.
Os dados utilizados foram gerados artificialmente para simular uma operação de implantação com 20 clientes ativos.
