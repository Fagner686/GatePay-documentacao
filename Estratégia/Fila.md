## 📌 Visão Geral

A tela de fila é o ponto de acompanhamento dos filtros que estão sendo processados no sistema. Ela permite visualizar o andamento de cada execução, identificar filtros em andamento e acessar ações específicas para gerenciar o processamento com mais controle.

![Fila de filtros](../img/estrategia/fila/fila-filtros.png)

## 🎯 Quando usar essa tela

Essa tela é indicada quando você precisa:

- acompanhar a execução de filtros em tempo real;
- verificar qual filtro está sendo processado e em que etapa está;
- identificar contratos concluídos, em andamento ou pendentes;
- ajustar o comportamento de um filtro já em execução.

## 🔎 Como a fila funciona

Após selecionar um grupo, o sistema exibe todos os filtros em execução para esse grupo no momento da consulta. Cada filtro possui uma barra de progresso que mostra o estado do processamento dos contratos.

As cores da barra representam diferentes situações:

- 🟢 Verde: contratos concluídos;
- 🟡 Amarelo: contratos em processamento;
- 🔵 Azul: contratos pendentes de processamento.

### 🔄 Ordem de processamento

Os filtros são executados de acordo com a ordem em que aparecem na fila. Quando o processamento do primeiro filtro é concluído ou interrompido, o próximo filtro da lista assume a primeira posição e inicia sua execução.

![Ordem da fila](../img/estrategia/fila/ordem-filtros.png)

## ⚙️ Ações disponíveis

Ao clicar no ícone de configurações, é exibido um menu com ações relacionadas ao filtro selecionado.

### 📄 Listar contratos

Exibe, em uma janela modal, todos os contratos pertencentes ao filtro selecionado.

![Lista contratos](../img/estrategia/fila/lista-contratos.png)

### ⚙️ Configurações

Permite acessar opções de gerenciamento do filtro.

As opções disponíveis são:

- **Atualizar filtro:** atualiza manualmente o filtro, sincronizando sua composição com a base de dados. Essa ação adiciona novos contratos que atendem aos critérios do filtro e remove aqueles que não fazem mais parte dele.
- **Filtro persistente:** mantém o filtro ativo na fila, mesmo após o término do processamento de todos os contratos. Essa opção é recomendada para filtros que precisam permanecer disponíveis para futuras atualizações.

![Configuração](../img/estrategia/fila/configuracao.png)

### ⏹️ Parar

Interrompe a execução do filtro e remove o item da fila de processamento.

## ✅ Regras importantes

- acompanhe a fila para identificar gargalos ou filtros demorados;
- use a opção de atualização quando houver mudanças na base de dados;
- considere o filtro persistente para cenários de atualização recorrente;
- verifique o status dos contratos antes de assumir que o processamento foi concluído.