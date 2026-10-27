# Catálogo de referências

## 1. Agency Agents
**Origem:** https://github.com/msitarzewski/agency-agents  
**Categorias:** equipes de agentes, engenharia, design, marketing, vendas, produto, QA e suporte.  
**Possível uso:** planejar divisão de tarefas e responsabilidades em projetos com múltiplos agentes.

## 2. Wshobson Agents
**Origem:** https://github.com/wshobson/agents  
**Categorias:** agentes, skills, comandos, plugins, programação, depuração, segurança e infraestrutura.  
**Possível uso:** selecionar ferramentas especializadas por tarefa, sem instalar um conjunto inteiro.

## 3. Anthropic Knowledge Work Plugins
**Origem:** https://github.com/anthropics/knowledge-work-plugins  
**Categorias:** vendas, atendimento, produto, marketing, jurídico, finanças e análise de dados.  
**Possível uso:** prototipar fluxos de trabalho administrativos e empresariais.

## 4. Claude Quickstarts
**Origem:** https://github.com/anthropics/claude-quickstarts  
**Categorias:** exemplos de aplicações e agentes.  
**Possível uso:** estudar implementações de referência, adaptar integrações e validar arquitetura.

## 5. Addy Osmani Agent Skills
**Origem:** https://github.com/addyosmani/agent-skills  
**Categorias:** especificação, desenvolvimento guiado por testes, revisão, segurança e implantação.  
**Possível uso:** padronizar o ciclo de desenvolvimento.

## 6. PixelRAG
**Origem:** https://github.com/StarTrail-org/PixelRAG  
**Pesquisa:** https://arxiv.org/abs/2606.28344  
**Licença do repositório:** Apache-2.0 (arquivo `LICENSE` do projeto oficial; verificar novamente ao adotar uma versão).  
**Categorias:** recuperação multimodal, pesquisa visual, páginas web, PDFs, screenshots, tabelas e gráficos.  
**Como funciona:** renderiza documentos em blocos de imagens (`pixelshot`), utiliza embeddings de visão/linguagem para indexação visual e recupera imagens relevantes para interpretação por um modelo. Não é uma substituição universal de scraping ou de leitura estruturada.  
**Possível uso:** complementar agentes que precisam consultar documentos cujo layout é essencial, incluindo relatórios técnicos, tabelas de peças, catálogos e telas de sistemas.  
**Avaliação:** referência catalogada; **não instalado, não testado e não integrado** ao Context Mode, FuuDelivery ou VPS.  
**Atenção:** a indexação local completa pode exigir GPU e recursos consideráveis. Avaliar consumo de memória, licenças dos modelos, dados sensíveis, URLs não confiáveis, precisão e custo antes de experimentar. Não enviar documentos privados para APIs externas sem autorização.

## Aplicações que vale priorizar
| Projeto futuro | Referências iniciais | Objetivo |
|---|---|---|
| Gestão de frotas e manutenção | Agency Agents; Wshobson Agents | Automação de conferências, cadastros e relatórios |
| Estoque e compras de filtros | Knowledge Work Plugins; Wshobson Agents | Apoio a pesquisa, revisão e processos de compras |
| Aplicativos e sistemas web | Claude Quickstarts; Agent Skills | Protótipos, testes, qualidade e implantação |
| Suporte e atendimento | Agency Agents; Knowledge Work Plugins | Triagem e organização de solicitações |
| Documentos visuais e catálogos técnicos | PixelRAG | Investigar recuperação de tabelas, esquemas, PDFs e layouts com validação humana |

**Nota:** descrições são orientativas; funcionalidades, números de agentes e compatibilidade podem mudar. Consultar a documentação atual dos autores antes da adoção.
