# Guia de adoção segura

## Antes de usar
- [ ] Confirmar URL e mantenedor do repositório original.
- [ ] Conferir licença de cada projeto e dos arquivos específicos.
- [ ] Fixar tag ou commit de uma versão revisada.
- [ ] Inspecionar prompts, skills, scripts de instalação e dependências.
- [ ] Verificar se há comandos destrutivos, acesso à rede, leitura de segredos ou execução automática.
- [ ] Conceder apenas as permissões mínimas necessárias.
- [ ] Rodar primeiro em ambiente de teste isolado.
- [ ] Registrar responsável, versão, finalidade e resultado da avaliação.

## Avaliação de recuperação visual (PixelRAG)
- [ ] Validar licença Apache-2.0 e fixar commit/tag de [StarTrail-org/PixelRAG](https://github.com/StarTrail-org/PixelRAG).
- [ ] Começar com documentos públicos e sem segredos; verificar tratamento de dados por qualquer API externa.
- [ ] Testar `pixelshot` em ambiente isolado, com URLs permitidas, limites de tempo e tamanho e sem acesso a serviços internos.
- [ ] Comparar resultados com extração textual convencional em tabelas, gráficos e PDFs conhecidos; medir acurácia e alucinações.
- [ ] Avaliar CPU, RAM, GPU e armazenamento antes de propor indexação local; não assumir compatibilidade com uma VPS de 4 GB.
- [ ] Manter a ferramenta como opção de leitura e pesquisa, sem permissões de escrita ou alterações de produção, até homologação.

## Critérios para integração
**Aprovar:** benefício claro, licença compatível, dependências auditadas, testes satisfatórios.  
**Revisar:** documentação incompleta, permissões excessivas, comportamento inesperado.  
**Rejeitar:** origem não confiável, execução opaca, exposição de credenciais ou incompatibilidade de licença.

## Modelo de registro
| Campo | Preencher |
|---|---|
| Projeto de destino | |
| Recurso selecionado | |
| URL e commit/tag | |
| Licença verificada | |
| Dependências e permissões | |
| Testes realizados | |
| Decisão e responsável | |

Este diretório é documental: nenhuma instalação ou integração automática é realizada.
