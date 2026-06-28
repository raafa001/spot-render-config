## spot-render-config

- Centraliza documentação (blueprints, runbooks, onboarding).  
- Armazena diagramas, checklists de release e links para todos os repositórios.  
- Inclui `blueprint-spot-render.md` como referência principal.  
- Mantém referências a arquivos confidenciais (ex.: `render-list*.csv/xlsx`). Esses arquivos **não** ficam no Git: guardá-los localmente para testes e enviá-los através do campo opcional de render list na API/portal.

### Conteúdo
- `blueprint-spot-render.md`: arquitetura aprovada, divisão de repositórios e FinOps.  
- `issues-plan.md`: backlog cruzado (Dev, DevOps, QA, DBRE, SRE) com os pontos obrigatórios.  
- `backstage/catalog-info.yaml`: definição do `Group spot-render-team` e `System spot-render` para o Backstage.  
- Diretório `docs/` (TechDocs) descrevendo como consumir todo o ecossistema.

### TechDocs
- Use `mkdocs.yml` neste repositório como índice geral. Ele aponta para cada componente e descreve como publicar as TechDocs de cada serviço.
- Mantém referências a arquivos confidenciais (ex.: `render-list*.csv/xlsx`). Esses arquivos **não** ficam no Git: guardá-los localmente para testes e enviá-los através do campo opcional de render list na API/portal.
