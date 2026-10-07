# 🔄 03 — Visão Geral e Especificação dos Casos de Uso

Esta pasta armazena o detalhamento dos casos de uso da aplicação **Canto do Sabor**, fornecendo a especificação passo a passo da interação entre os atores e o sistema.

## 📁 Conteúdo do Diretório

* `Visao_Geral_Casos_De_Uso.xlsx`: Planilha unificada contendo o detalhamento do *Core Business*, Fluxo Principal, Fluxos Alternativos e Exceções, e a especificação dos demais casos de uso.

## 📌 Estrutura da Especificação

### 1. Core Business — UC01: Registrar Venda
Representa o processo central de negócio da pizzaria. Define os atores principais (Atendente e Proprietário), pré-condições (caixa aberto, usuário autenticado) e pós-condições (venda registrada no banco de dados e recibo emitido).

### 2. Fluxo Principal ("Caminho Feliz")
Descreve a sequência ideal de etapas para a conclusão de uma venda:
1. Atendente inicia nova venda no PWA.
2. Sistema carrega o cardápio atualizado.
3. Atendente adiciona os itens solicitados.
4. Sistema calcula subtotal, taxas e valor final.
5. Seleção e processamento da forma de pagamento.
6. Confirmação do pedido e gravação na nuvem.

### 3. Fluxos Alternativos e de Exceção
Mapeiam cenários secundários e tratamento de erros durante a operação:
* **Fluxos Alternativos:** Aplicação de cupons/descontos e modalidades de pagamento misto (ex: Dinheiro + Pix).
* **Fluxos de Exceção:** Tratamento de quedas na conexão com a internet (armazenamento offline local), produto sem estoque e emissão de alerta de inconsistência ao gestor (**UC-EXT**).

### 4. Demais Casos de Uso (UC02 a UC10)
Cobre as funcionalidades administrativas e operacionais de retaguarda:
* **UC02:** Manutenção de Cardápio e Preços.
* **UC03:** Gestão e Autenticação de Usuários.
* **UC04 a UC10:** Emissão de relatórios gerenciais, fechamento diário de caixa, conciliação financeira e backups automáticos agendados.
