# Evidências do Projeto – Diagnóstico de Pipeline CI/CD

Este diretório reúne as **evidências visuais e documentais** coletadas durante a execução do projeto **“Diagnóstico e Auditoria do Pipeline de Integração Contínua do Projeto Crawl4AI”**, desenvolvido na disciplina **Engenharia de Software II** (UFS).

As evidências aqui armazenadas sustentam as análises realizadas sobre o uso de **GitHub Actions**, workflows em **YAML**, e o nível de maturidade do processo de Integração Contínua e Entrega Contínua (CI/CD) do projeto analisado.

---

## 👥 Contribuintes

- **Carlos Daniel Lima de Gois**
- **Felipe Osni Santos Moura**
- **João Pedro Cardoso Arruda**
- **Nicolas Matheus Ferreira de Jesus**
- **Samuel Bastos Borges Pinho**
- **Vinícius Vasconi Villas Boas Micska**
- **Vitor Leonardo Sena de Lima**
- **David Silva Santana**

---

## 📁 Estrutura do Diretório

O diretório contém capturas de tela e diagramas que documentam o funcionamento real do pipeline do projeto Crawl4AI:

- **CurrentWorkflow.png**  
  Representa o workflow atual do projeto, evidenciando a ausência de etapas obrigatórias de validação automática em Pull Requests.

- **ProjectWorkflow.png**  
  Diagrama geral do fluxo de desenvolvimento, desde a criação de Pull Requests até o processo de release.

- **ReleasePipeline.png**  
  Evidência do pipeline responsável pela publicação de releases no PyPI, acionado por tags no repositório.

- **TestReleasePipeline.png**  
  Workflow configurado para testes de release, atualmente desativado, indicando tentativas anteriores de validação automatizada.

- **ReleasesChart.png**  
  Histórico visual das releases do projeto, utilizado para análise de frequência e maturidade do processo de entrega.

- **WorkflowExecutions.png**  
  Captura da aba *Actions* do GitHub, mostrando milhares de execuções de workflows ao longo do tempo.

- **YamlFiles.png**  
  Evidência da presença de múltiplos arquivos `.yml` no diretório `.github/workflows`, confirmando o uso de GitHub Actions como ferramenta de automação.

---

## 📊 Principais Resultados Obtidos

A análise das evidências permitiu identificar que:

- O projeto Crawl4AI possui **automação voltada principalmente para release (CD)**, mas **não adota práticas completas de Integração Contínua (CI)**.
- Não há execução obrigatória de **testes automatizados, lint ou análise estática** em Pull Requests.
- O merge de código depende majoritariamente de **revisão manual**, aumentando o risco de regressões.
- Existem workflows desativados ou backups, indicando **evolução incompleta** do pipeline ao longo do tempo.
- A separação entre pipelines de release Python e Docker demonstra uma arquitetura otimizada para tempo de entrega, porém sem validação de qualidade prévia.

Esses achados fundamentam a conclusão de que o projeto apresenta **baixa maturidade em CI**, apesar de possuir um ecossistema robusto de automações para entrega e notificações.

---

## 🎯 Finalidade das Evidências

As evidências aqui reunidas servem para:

- Sustentar o diagnóstico técnico apresentado no relatório final;
- Comprovar visualmente os fluxos descritos na metodologia e no mapeamento do processo;
- Apoiar a identificação de riscos, gargalos e oportunidades de melhoria no pipeline CI/CD.

---

📌 **Observação:**  
Todos os arquivos apresentados neste diretório foram coletados diretamente do repositório oficial do projeto Crawl4AI e da interface do GitHub, garantindo fidelidade ao estado real do sistema analisado.

