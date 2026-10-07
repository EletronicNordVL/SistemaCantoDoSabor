# 🍕 Canto do Sabor — Sistema de Gestão e Análise de Vendas

Bem-vindo ao repositório do projeto e trabalho chamado **Pizzaria - Canto do Sabor**, desenvolvido para a disciplina de **Análise e Projeto de Sistemas (APS)**. Este projeto contempla a modelagem completa, engenharia de requisitos e especificação arquitetural de um sistema de Ponto de Venda (PDV) e gestão financeira para uma pizzaria, estruturado como uma aplicação **Progressive Web App (PWA)** com suporte a operações offline e sincronização em nuvem.

## 📌 Visão Geral do Projeto

O **Canto do Sabor** visa automatizar e auditar o fluxo de vendas e controle financeiro do estabelecimento. A aplicação substitui processos manuais por um fluxo digital auditável, garantindo a integridade dos dados, cálculo automatizado de valores e emissão de alertas em caso de inconsistências financeiras ou de estoque.

### 🛠️ Arquitetura e Tecnologias
* **Frontend / Client:** Progressive Web App (PWA) em Angular, focado em alta disponibilidade e operação offline local.
* **Backend:** Spring Boot hospedado em infraestrutura de nuvem.
* **Banco de Dados:**
  * **PostgreSQL:** Armazenamento relacional de transações, vendas e usuários.
  * **Neo4j:** Banco orientado a grafos para análise de conexões e padrões operacionais.

## 📁 Estrutura do Repositório

O repositório está organizado em três diretórios principais, cada um contendo a documentação técnica e os artefatos correspondentes:

```text
.
├── 01 - DIAGRAMAS/
│   ├── Diagrama_de_Estados/
│   ├── Diagrama_de_Casos_de_Uso/
│   ├── Diagrama_de_Atividades/
│   ├── Diagrama_de_Implementacao/
│   ├── Diagrama_de_Pacotes/
│   └── README.md
│
├── 02 - REQUISITOS/
│   ├── REQUISITOS E REGRA DE NEGÓCIO.xlsx
│   └── README.md
│
└── 03 - VISÃO GERAL DO CASO DE USO/
    ├── VISÃO GERAL DE CASOS DE USO - COMPLETO.xlsx
    └── README.md
```

### 🔹 Detalhes dos Diretórios

1. [**`01 - DIAGRAMAS/`**](./01%20-%20DIAGRAMAS/)
   Contém os modelos visuais e comportamentais do sistema implementados em código **HTML + CSS** para fácil inspeção em qualquer navegador web. Inclui os diagramas de Estados, Casos de Uso, Atividades, Implantação e Pacotes.

2. [**`02 - REQUISITOS/`**](./02%20-%20REQUISITOS/)
   Reúne a matriz completa de **Requisitos Funcionais (RF01 a RF11)**, **Requisitos Não Funcionais (RNF01 a RNF11)** e **Regras de Negócio (RN01 a RN08)**, organizados e priorizados via metodologia MoSCoW (*Must Have, Should Have, Could Have*).

3. [**`03 - VISÃO GERAL DO CASO DE USO/`**](./03%20-%20VIS%C3%83O%20GERAL%20DO%20CASO%20DE%20USO/)
   Documentação técnica detalhada dos fluxos de uso do sistema, abrangendo o *Core Business* (**UC01 - Registrar Venda**), o fluxo principal ("caminho feliz"), fluxos alternativos (pagamento misto, descontos), exceções (falha de rede, falta de estoque) e demais casos de uso (UC02 a UC10).

## 🚀 Como Navegar no Repositório

1. Para visualizar a especificação das regras de negócio e requisitos, acesse a pasta [`02 - REQUISITOS/`](./02%20-%20REQUISITOS/).
2. Para entender o detalhamento das etapas operacionais de venda, consulte a pasta [`03 - VISÃO GERAL DO CASO DE USO/`](./03%20-%20VIS%C3%83O%20GERAL%20DO%20CASO%20DE%20USO/).
3. Para inspecionar os diagramas interativos, navegue até a pasta [`01 - DIAGRAMAS/`](./01%20-%20DIAGRAMAS/) e abra os arquivos `.html` desejados no navegador.

## 📜 Licença e Observações

Este repositório tem fins estritamente acadêmicos, consolidando as melhores práticas de Engenharia de Software, Modelagem UML e Análise Orientada a Objetos.
