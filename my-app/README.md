# Pipeline - Projeto CI/CD com GitHub Actions

Este é um projeto de exemplo para aplicar os conceitos de **Integração Contínua (CI)** e **Entrega Contínua (CD)** utilizando **GitHub Actions** para automatizar o processo de build, testes, lint e deploy de uma aplicação front-end em **React**.

## Objetivo

O objetivo deste projeto é configurar uma pipeline de **CI/CD** para uma aplicação front-end utilizando **GitHub Actions**. A pipeline irá rodar:

- **Linting** com ESLint para garantir a qualidade do código.
- **Testes** automatizados (em breve, testes reais serão adicionados).
- **Build** da aplicação para garantir que o projeto compile corretamente.
- **Deploy automatizado** para **GitHub Pages** sempre que alterações forem feitas na branch `main`.

## Estrutura do Projeto

- **Frontend:** Aplicação feita com React e Vite.
- **Pipeline de CI/CD:** Configurado no GitHub Actions.

## Workflow de GitHub Actions

O arquivo `.github/workflows/main.yml` define o workflow com os seguintes passos:

1. **Instalação de dependências**: `npm ci`
2. **Rodando ESLint**: `npm run lint`
3. **Rodando testes**: `npm run test`
4. **Build da aplicação**: `npm run build`
5. **Deploy no GitHub Pages**.

## Site publicado

O site está disponível em: [https://LucasPaino.github.io/Pipeline/](https://LucasPaino.github.io/Pipeline/)

## Como rodar o projeto localmente

1. Clone o repositório:

   ```bash
   git clone https://github.com/LucasPaino/Pipeline.git

Navegue para a pasta do projeto:

cd Pipeline/my-app

Instale as dependências:

npm install

Inicie o servidor de desenvolvimento:

npm run dev

Abra o navegador e acesse http://localhost:5173 para ver a aplicação.

Contribuindo

Se você deseja contribuir com melhorias ou sugestões, sinta-se à vontade para abrir uma pull request ou issue.

Licença

Este projeto está licenciado sob a MIT License - veja o arquivo LICENSE
 para mais detalhes.

