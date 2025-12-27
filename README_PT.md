# GitHub Playbook

> Uma coleção centralizada de configurações, padrões e ativos reutilizáveis específicos para o GitHub.

## Visão Geral

Este repositório serve como a fonte única da verdade para governança do GitHub dentro da organização. Ele fornece configurações curadas para GitHub Actions, Templates de Issues, fluxos de trabalho de Pull Request e padrões gerais de repositório para garantir consistência em todos os projetos.

## 📂 Estrutura do Repositório

O repositório é organizado nos seguintes diretórios:

- `.github/`: A pasta padrão de configuração do GitHub.
  - `ISSUE_TEMPLATE/`: Templates pré-definidos para relatar bugs e solicitar funcionalidades.
  - `PULL_REQUEST_TEMPLATE.md`: Template padronizado para pull requests, garantindo qualidade de código e prontidão para revisão.
  - `workflows/`: Fluxos de trabalho reutilizáveis e padrão do GitHub Actions (CI/CD, linting, testes).
- `docs/`: Documentação sobre diretrizes de contribuição, padrões de codificação e registros de decisões arquiteturais (ADRs).
- `templates/`: Código base ou kits de inicialização de repositórios.

## 🚀 Começando

Para aplicar esses padrões a um repositório novo ou existente:

1. **Clone os arquivos de configuração**: Copie os arquivos relevantes deste repositório para a pasta `.github` do seu repositório de destino.
2. **Personalize**: Ajuste os workflows e templates para atender às necessidades específicas do seu projeto.
3. **Revise**: Certifique-se de que todos os segredos (secrets) e variáveis de ambiente estão configurados corretamente nas configurações do seu repositório.

## 🤝 Contribuindo

Contribuições são o que tornam a comunidade open-source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fornecer será **greatly appreciated** (altamente apreciada).

1. Fork o Projeto
2. Crie sua Branch de Funcionalidade (`git checkout -b feature/FuncionalidadeIncrivél`)
3. Commit suas Alterações (`git commit -m 'Adicionando FuncionalidadeIncrivél'`)
4. Push para a Branch (`git push origin feature/FuncionalidadeIncrivél`)
5. Abra um Pull Request

## 📜 Licença

Distribuído sob a Licença MIT. Veja `LICENSE` para mais informações.

## 📞 Contato

Link do Projeto: [https://github.com/your-organization/.github](https://github.com/your-organization/.github)
