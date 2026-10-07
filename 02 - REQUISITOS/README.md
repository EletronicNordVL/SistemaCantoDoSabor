# 📋 02 — Engenharia de Requisitos e Regras de Negócio

Esta pasta contém a especificação formal dos requisitos funcionais, não funcionais e regras de negócio que orientam a arquitetura e o desenvolvimento do sistema **Canto do Sabor**.

## 📁 Conteúdo do Diretório

* `Requisitos_E_Regras_De_Negocio.xlsx`: Matriz unificada contendo as abas de Requisitos Funcionais (RF), Requisitos Não Funcionais (RNF) e Regras de Negócio (RN).

## 📌 Estrutura da Documentação

### 1. Requisitos Funcionais (RF01 a RF11)
Mapeiam as funcionalidades diretas oferecidas pela aplicação aos usuários:
* **RF01 - Registrar Venda:** Permite ao atendente selecionar produtos, aplicar descontos e registrar pagamentos.
* **RF02 a RF11:** Abrangem autenticação de usuários, gestão de cardápio, controle de perfil de acesso, emissão de relatórios financeiros e disparo de alertas automáticos.

### 2. Requisitos Não Funcionais (RNF01 a RNF11)
Estabelecem os critérios de qualidade, desempenho, segurança e arquitetura do sistema:
* **Arquitetura PWA:** Suporte a funcionamento offline temporário com sincronização posterior.
* **Segurança:** Criptografia de dados sensíveis e autenticação baseada em perfis.
* **Resiliência e Desempenho:** Tempo de resposta reduzido para operações de caixa e tolerância a falhas de conexão de rede.

### 3. Regras de Negócio (RN01 a RN08)
Definem as restrições operacionais e diretrizes do estabelecimento:
* **RN01 - Descontos e Alçadas:** Necessidade de aprovação de perfil gestor para descontos superiores ao limite padrão.
* **RN02 a RN08:** Regras para fechamento de caixa, vinculação obrigatória de itens a vendas e auditoria de divergências.

## 🎯 Metodologia de Priorização (MoSCoW)

Todos os requisitos e regras foram categorizados quanto à sua relevância para o negócio:
* **Must Have (Obrigatório):** Funcionalidades essenciais para a operação do PDV.
* **Should Have (Desejável):** Recursos importantes que agregam valor significativo.
* **Could Have (Opcional):** Melhorias secundárias para fases futuras.
