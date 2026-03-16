## dio-notebooklm ##
Repositório destinado ao projeto de Caderno Temático desenvolvido no NotebookLM para o desafio da plataforma DIO.

## Contexto ##
Este repositório apresenta um Caderno Temático Digital focado em Segurança da Informação, desenvolvido como parte de um desafio prático na plataforma DIO. A proposta central é utilizar o NotebookLM para processar e sintetizar grandes volumes de dados técnicos, frameworks e normativas, transformando fontes brutas em uma base de conhecimento estruturada e de fácil consulta.

## Objetivos ##
Sintetização de Conhecimento: Centralizar e organizar conceitos fundamentais de segurança (como a Tríade CIA, tipos de ataques e vetores de vulnerabilidade);
Curadoria Inteligente: Utilizar IA para identificar padrões em documentações técnicas e facilitar o aprendizado de protocolos de defesa e resposta a incidentes;
Documentação Técnica: Servir como um guia de referência rápida para consultas sobre melhores práticas e ferramentas de proteção de dados;
Exploração de Ferramentas: Validar a eficácia do uso de assistentes baseados em documentos (LLMs focados em fontes específicas) na rotina de um profissional de segurança.

## Metodologia ##
Para a construção deste caderno, foi adotado um fluxo de curadoria digital em três etapas:

Coleta de Fontes: Seleção de materiais técnicos sobre Segurança da Informação (Frameworks, artigos e glossários);
Processamento via NotebookLM: Utilização da IA para extrair insights e gerar resumos estruturados baseados estritamente nas fontes fornecidas;
Organização Temática: Os dados foram categorizados seguindo os pilares da segurança (Confidencialidade, Integridade e Disponibilidade), facilitando a revisão e consulta rápida.

## Fontes de Estudo e Curadoria ##
O caderno temático foi alimentado com 12 fontes bibliográficas e técnicas selecionadas, incluindo:

Frameworks Internacionais: Comparativos detalhados entre ISO/IEC 27001, NIST Cybersecurity Framework (CSF) e CIS Controls;
Legislação: Documentação sobre a Lei Geral de Proteção de Dados (LGPD) e normativas governamentais brasileiras;
Glossários Técnicos: Bases de terminologia em Segurança Cibernética para padronização de conceitos;
Materiais Multimídia: Análises de especialistas e vídeos técnicos convertidos em insights de texto pelo NotebookLM.

## Ferramentas Utilizadas ##
NotebookLM (Google): Para análise semântica e síntese dos documentos de segurança;
GitHub: Para hospedagem, versionamento e exposição do portfólio técnico;
Markdown: Linguagem de marcação utilizada para a documentação técnica.

## Engenharia de Prompts e Troubleshooting ##
Nesta etapa, explorei diferentes abordagens para extrair informações precisas das 12 fontes de segurança e privacidade.

1. Prompt de Síntese Comparativa (NIST vs. ISO):
Prompt inicial: "Qual a diferença entre NIST e ISO?";
Prompt refinado: "Com base estrita nas fontes fornecidas, crie uma tabela comparativa entre o NIST CSF e a ISO 27001, focando em: Público-alvo, Custo de implementação e Flexibilidade.";
Resultado: Consegui uma distinção clara de que a ISO é voltada para certificação, enquanto o NIST é um framework de melhoria contínua.

2. Troubleshooting:
Desafio: A IA estava misturando conceitos da LGPD com o GDPR europeu;
Solução: Ajustei o contexto do prompt para: "Responda utilizando apenas a fonte 'Lei Geral de Proteção de Dados - LGPD'.";
Lição aprendida: Delimitar a fonte específica no NotebookLM foi essencial para a acurácia jurídica.

## Miniguia de Estudo ##
Este guia consolida o conhecimento gerado através da interação entre as fontes técnicas e a IA.

1. Resumo Estruturado: O Ecossistema de Segurança:
Governança e Conformidade: Foco em ISO 27001 para estabelecer um SGSI;
Operação e Defesa: Uso do NIST CSF para identificar, proteger, detectar, responder e recuperar incidentes;
Privacidade: Implementação dos pilares da LGPD, garantindo os direitos dos titulares e o tratamento lícito de dados.

2. Glossário de Conceitos-Chave:
Tríade CIA: Confidencialidade, Integridade e Disponibilidade;
Vetor de Ataque: O caminho ou meio pelo qual um atacante obtém acesso a um computador ou servidor de rede;
Controlador vs. Operador (LGPD): Distinção de responsabilidades no tratamento de dados pessoais.

3. Biblioteca de Prompts Reutilizáveis:
Estes prompts podem ser aplicados em futuras revisões de segurança:
"Aja como um auditor de ISO 27001 e analise o documento X em busca de lacunas de conformidade.";
"Explique o conceito de X para um stakeholder não técnico, mantendo a precisão da norma NIST."

