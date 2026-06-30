Proposta de Squads — Developer Portal Bradesco
Documento interativo de planejamento de programa para a evolução do Developer Portal Bradesco: organização em 5 squads (4 de Build + 1 de Run), fluxo de dependências entre elas, argumento de autonomia frente ao vendor atual (Axway), pré-requisitos de infraestrutura e os riscos transversais do programa.
Construído a partir das 37 funcionalidades já validadas no protótipo do portal — não é uma estrutura genérica de squad, é o desenho organizacional que sustenta o que já foi prototipado e testado.
O que tem aqui
	•	5 squads detalhadas — Plataforma & Identidade, Produtos Financeiros, BaaS + IA & Inovação, Developer Experience & Confiabilidade, e Run (Operação). Cada card é expansível e mostra capabilities, escopo já coberto no protótipo, perfis recomendados, riscos e premissas.
	•	Fluxo de dependências interativo — diagrama clicável mostrando quem fornece o quê para quem, com destaque visual por squad ao clicar em cada nó.
	•	Argumento de autonomia — comparação direta entre o modelo atual (dependente de vendor) e a proposta (arquitetura própria, sem limite de customização, com MCP/gRPC/IA nativos).
	•	Pré-requisitos de infraestrutura — cloud, AI Gateway, MCP Server, observabilidade e identidade, com a squad responsável por cada um.
	•	Riscos transversais — os que atravessam mais de uma squad e não pertencem a nenhuma isoladamente.
Como visualizar
Abra index.html diretamente no navegador, ou publique via GitHub Pages apontando para este repositório — o arquivo já está nomeado para ser servido automaticamente na raiz.
Stack
HTML/CSS/JS puro, sem dependências externas além de fontes do Google Fonts (Fraunces, Inter, JetBrains Mono). Nenhuma build necessária.
