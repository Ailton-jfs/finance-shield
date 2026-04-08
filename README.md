FinanceShield — Simulação Antifraude em Tempo Real

O FinanceShield é uma simulação interativa de um pipeline de detecção de fraude financeira em tempo real, projetado para demonstrar como sistemas modernos analisam, classificam e bloqueiam transações suspeitas em menos de 200ms.

A aplicação executa todo o processamento em memória (sem I/O em disco), permitindo visualizar de forma clara o fluxo completo de decisão antifraude, desde a recepção da transação até a notificação ao cliente.

Visão Geral

O sistema simula um pipeline antifraude composto por cinco estágios principais:

Receber → Análise → Pontuação → Decisão → Notificação

Cada etapa é representada visualmente com tempos de execução realistas, oferecendo uma visão prática de como soluções de alto desempenho operam no setor financeiro.

Funcionalidades
Pipeline em Memória
Execução de transações sem uso de disco
Cinco estágios com animação e tempos de resposta realistas
Foco em baixa latência e alta performance
Precisão vs Falsos Positivos
Gráfico interativo atualizado em tempo real
Ajuste dinâmico do limiar de bloqueio
Visualização do impacto nas decisões do sistema
Simulação de Transações
Geração contínua ou manual de transações
Cálculo automático de score de risco
Decisão instantânea (aprovada ou bloqueada)
Histórico das transações em tabela
Notificação ao Cliente
Painel de alertas em tempo real
Modal simulando comunicação com o cliente
Feedback visual imediato para transações bloqueadas
Controles Ajustáveis
Parâmetro	Intervalo	Padrão
Limiar de Bloqueio	0.30 – 0.95	0.65
Volume (transações/s)	1 – 20	5
Taxa de Fraude	2% – 40%	12%
Métricas em Tempo Real
Taxa de transferência (transações por segundo)
Latência média de resposta
Taxa de bloqueio
Contagem de falsos positivos
Tecnologias Utilizadas
HTML5
CSS3
JavaScript (Vanilla)
Renderização de gráficos customizada
Arquitetura 100% client-side, sem dependências externas
Como Executar

Você pode rodar o projeto de forma simples:

# Opção 1: Abrir diretamente
Abra o arquivo index.html no navegador

# Opção 2: Usar Live Server (recomendado)
Utilize a extensão do VS Code para hot-reload
Deploy

O projeto pode ser publicado facilmente como site estático:

Upload direto no Netlify
Integração com GitHub para deploy automático
Objetivo do Projeto

Este projeto tem finalidade educacional e demonstrativa, sendo adequado para:

Apresentações acadêmicas
Portfólio de projetos
Demonstração de conceitos de antifraude em tempo real
Estudos de pipelines de decisão e sistemas de baixa latência
Licença

Livre para uso educacional e demonstração.
