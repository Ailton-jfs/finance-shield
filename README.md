FinanceShield — Simulação Antifraude em Tempo Real
Simulação interativa de pipeline de detecção de fraude financeira com bloqueio em menos de 200ms. O sistema processa transações transmitidas em memória, sem I/O em disco, demonstrando um fluxo completo de análise de risco.

Funcionalidades
Pipeline em Memória — 5 estágios animados (Receber → Análise → Pontuação → Decisão → Notificar) com tempos de execução reais
Precisão vs Falso Positivo — Gráfico interativo que responde ao ajuste dos limites de bloqueio em tempo real
Simulação de Bloqueio — Geração contínua ou individual de transações com pontuação de risco, decisão automática e tabela de resultados
Notificação ao Cliente — Painel de alertas + pop-up modal simulando a mensagem recebida pelo cliente quando uma transação está bloqueada
Controles Ajustáveis
Parâmetro	Não.	padrão
Limiar de Bloqueio	0,30 – 0,95	0,65
Volume (transações/s)	1 – 20	5
Taxa de Fraude	2% – 40%	12%
Métricas em Tempo Real
Taxa de transferência (transações por segundo)
Latência média de resposta
Taxa de bloqueio
Contagem de falsos positivos
Órgãos transversais
HTML5, CSS3, JavaScript puro
Tela para gráficos
Sem dependências externas de construção
Implantação estática (Netlify)
Como Rodar
Basta abrir ou não index.htmlno navegador. Ou use o Live Server no VS Code para hot-reload.

Implantar
Arraste o arquivo para oNetlifyou conecte o repositório GitHub para implantação automática.

licença
Livre para uso educacional e demonstração.
