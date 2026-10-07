# 📐 01 — Diagramas da Arquitetura e Comportamento

Esta pasta reúne a modelagem visual e arquitetural do sistema de uma pizzaria **Canto do Sabor**. Todos os diagramas foram desenvolvidos utilizando código **HTML + CSS**, permitindo que sejam visualizados diretamente no navegador web sem a necessidade de softwares específicos de modelagem.

## 📁 Estrutura de Subpastas

A pasta está dividida em subpastas dedicadas a cada perspectiva de modelagem UML:

```text
01 - DIAGRAMAS/
├── Diagrama_de_Estados/
│   └── diagrama-estados-branco-v3.html
│   └── DIAGRAMA DE ESTADOS - FINAL.html
├── Diagrama_de_Casos_de_Uso/
│   └── diagrama-casos-de-uso-pizzaria-v5.html
│   └── DIAGRAMA DE CASO DE USO - FINAL
├── Diagrama_de_Atividades/
│   └── diagrama-atividades-pizzaria-v7.html
│   └── DIAGRAMA DE ATIVIDADE - FINAL
├── Diagrama_de_Implementacao/
│   └── DIAGRAMA DE IMPLEMENTAÇÃO - FINAL
└── Diagrama_de_Pacotes/
    └── Diagrama de Pacotes (Pizzaria) V6.html
```

## 🔍 Descrição dos Diagramas

### 1. Diagrama de Estados (`Diagrama_de_Estados/`)
Mapeia o ciclo de vida completo de uma transação de venda dentro do sistema.
* **Estados contemplados:** *Em Registro*, *Aguardando Confirmação*, *Validando*, *Confirmada*, *Com Alerta*, *Cancelada*.
* **Objetivo:** Garantir que o sistema trate transações interrompidas, falhas de validação e emissão de alertas de inconsistência antes da finalização da venda.

### 2. Diagrama de Casos de Uso (`Diagrama_de_Casos_de_Uso/`)
Mapeia os limites funcionais da aplicação e as permissões dos diferentes atores do sistema.
* **Atores:** Atendente/Caixa, Proprietário (Carlos), Contador e Agendador do Sistema (*System Scheduler*).
* **Escopo:** Desde operações cotidianas (*Registrar Venda*, *Gerenciar Cardápio*) até rotinas de retaguarda (*Relatórios Financeiros*, *Backups Automatizados*).

### 3. Diagrama de Atividades (`Diagrama_de_Atividades/`)
Representa o fluxo operacional e de controle do processo de registro de venda através de **raias de responsabilidade** (*swimlanes*).
* **Raias:** Atendente, Sistema PWA e Proprietário.
* **Foco:** Demonstrar a autenticação de credenciais, inserção de itens, seleção da forma de pagamento e validações automáticas de segurança.

### 4. Diagrama de Implementação (`Diagrama_de_Implementacao/`)
Apresenta a visão física e arquitetural do sistema em **3 camadas**:
* **Dispositivo Local (Client):** PWA executado em desktops/smartphones.
* **Servidor de Aplicação (Nuvem):** Backend Spring Boot + Frontend Angular.
* **Servidor de Banco de Dados:** PostgreSQL (relacional) e Neo4j (grafo).

### 5. Diagrama de Pacotes (`Diagrama_de_Pacotes/`)
Organiza a estrutura lógica do sistema em módulos independentes, destacando a separação de responsabilidades entre interface de usuário, regras de negócio, serviços de integração e persistência de dados.

## 💻 Como Visualizar os Diagramas

1. Navegue até a subpasta do diagrama desejado.
2. Abra o arquivo `.html` em qualquer navegador web moderno (Google Chrome, Firefox, Edge, Safari).
3. O diagrama será renderizado de forma interativa com a estilização CSS inclusa.
