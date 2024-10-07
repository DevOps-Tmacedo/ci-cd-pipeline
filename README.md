## Pipeline CI/CD

Este repositório utiliza um pipeline CI/CD no GitLab com as seguintes etapas:

1. **Build**: Compila o projeto.
2. **Test**: Executa os testes automatizados.
3. **Deploy**: Permite implantações manuais para os ambientes `develop` e `main`.

### Como Executar o Pipeline

- Faça um commit no branch `develop` para acionar o job de deploy para o ambiente de desenvolvimento.
- Faça um commit no branch `main` para acionar o job de deploy para o ambiente de produção.
- Os jobs de deploy precisam ser acionados manualmente através da interface do GitLab.
