# 📊 Painéis Padrões Versionados - Time de Inteligência

![Badge Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)
![GitHub last commit](https://img.shields.io/github/last-commit/vhenriquean/Versionamento-Power-BI)
![GitHub repo size](https://img.shields.io/github/repo-size/vhenriquean/Versionamento-Power-BI)

Repositório central para versionamento e gestão de todos os painéis padrão da time de Inteligência.

## 📂 Estrutura do Projeto

```
paineis/
├── 📁 preço/
│   ├── 📄 painel_preco_padrao.pbip
│
├── 📁 produtividade/
│   ├── 📄 painel_produtividade_padrao.pbip
│
├── 📁 ruptura/
│   ├── 📄 painel_ruptura_padrao.pbip
│
├── 📁 share/
│   ├── 📄 painel_share_padrao.pbip
```


## 🔄 Fluxo de Versionamento
1. main - Versões estáveis (production)

2. staging - Pré-lançamento (homologação)

3. dev - Desenvolvimento ativo

## 📌 Regras de Commit

| Tipo          | Prefixo  | Exemplo                     |
|---------------|----------|-----------------------------|
| **Novo**      | `[ADD]`  | `[ADD] preço/novo-painel`   |
| **Atualização**| `[UPD]` | `[UPD] template v1.2`       |
| **Correção**  | `[FIX]`  | `[FIX] correcao-eixos`      |
| **Remoção**   | `[DEL]`  | `[DEL] painel-obsoleto`     |

## 🤝 Contribuição

- Crie uma branch: git checkout -b feature/nova-funcionalidade

- Commit suas mudanças: git commit -m "[ADD] novo painel fini"

- Push para a branch: git push origin feature/nova-funcionalidade


## Abra um Pull Request


✉️ Contato
Equipe de Inteligência de Dados - inteligencia@involves.com

Nota: Todos os painéis devem passar pelo processo de aprovação antes do merge para a branch main.


📝 Arquivos Adicionais para o Repositório (Exemplos):

1. CHANGELOG.md
   
# Histórico de Alterações

Este documento registra todas as mudanças significativas nos painéis padrões.

## [Unreleased]
### Added
- Novo painel de métricas de Sell-Out
  
### Changed
- Atualização do template gerencial para v5.1

### Fixed
- Correção de tabela no painel de dados de Loja Perfeita

## [1.0.0] - 2023-11-15
### Added
- Versão inicial do repositório
- Conjunto básico de painéis:
  - Performance de redes sociais
  - Analytics de produto
  - KPIs de equipes

2.  .gitignore

- **/.pbi/localSettings.json  
- **/.pbi/cache.abf

3. .github/PULL_REQUEST_TEMPLATE.md

# Descrição da Alteração

[Descreva claramente as mudanças realizadas e o motivo]

## Tipo de Mudança
- [ ] Novo painel
- [ ] Atualização de painel existente
- [ ] Correção de bugs
- [ ] Melhoria de performance
- [ ] Atualização de documentação

## Painéis Afetados
- [Liste os painéis que foram modificados]

## Checklist
- [ ] Meu código segue o estilo do projeto
- [ ] Documentação atualizada (se aplicável)
- [ ] Testes realizados
- [ ] Versão atualizada no CHANGELOG.md

## Screenshots (se aplicável)
[Adicione screenshots das mudanças visuais]

## Issues Relacionadas
Fixes # [número da issue]
