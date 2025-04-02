# Azure DevOps Lab

Este repositório foi criado para testar e configurar um **Pipeline no Azure DevOps** utilizando um agente self-hosted.

## 📌 Objetivo
O objetivo deste projeto é configurar um **pipeline de CI/CD** no Azure DevOps, utilizando um agente próprio para execução das tarefas. Este repositório contém os scripts e configurações necessários para rodar os testes e validar a execução do pipeline.

## 🛠️ Configuração do Agente

Para executar o pipeline corretamente, foi configurado um **Agente Self-Hosted** seguindo os seguintes passos:

1. Criar e registrar o agente no **Azure DevOps**.
2. Configurar as permissões adequadas para permitir a execução das pipelines.
3. Clonar o repositório e executar os scripts de build.

### 📜 Logs e Validação

Após a execução do pipeline, o log exibiu as seguintes informações:

- O agente foi identificado corretamente (`Agente teste` rodando na máquina `RATECH`).
- O código do repositório foi baixado com sucesso.
- O pipeline foi executado com sucesso e exibiu a mensagem:
  
  ```sh
  Pipeline funcionando!
  ```

## 🚀 Executando o Pipeline

Para rodar o pipeline manualmente:

1. Vá até o **Azure DevOps > Pipelines**.
2. Selecione o pipeline deste repositório.
3. Clique em **Run Pipeline** para executar a versão mais recente.

## 📝 Estrutura do Repositório

- `.azure-pipelines.yml` - Arquivo de configuração do pipeline (a ser adicionado futuramente).
- `scripts/` - Diretório para armazenar scripts auxiliares.
- `README.md` - Este arquivo, que contém a documentação inicial.

## 🤝 Contribuindo

1. Faça um **fork** do projeto.
2. Crie uma nova **branch** com a sua feature (`git checkout -b minha-feature`).
3. Commit suas mudanças (`git commit -m 'Adicionando nova feature'`).
4. Faça um **push** para a branch (`git push origin minha-feature`).
5. Abra um **Pull Request**.

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para contribuir e modificar conforme necessário.

---

✉️ **Dúvidas ou sugestões?** Entre em contato!
