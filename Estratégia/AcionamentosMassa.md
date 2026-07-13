## 📌 Visão Geral

Os acionamentos em massa permitem aplicar um mesmo acionamento a diversos contratos ao mesmo tempo. Essa funcionalidade é útil quando uma ação precisa ser registrada em um grande volume de contratos sem a necessidade de repetir o procedimento individualmente.

![Listagem](../img/estrategia/acionamentos-massa/image.png)

## 🎯 Quando usar essa funcionalidade

Essa funcionalidade é indicada quando você precisa:

- registrar a mesma ação em vários contratos de uma só vez;
- padronizar o tratamento de um grupo de registros;
- economizar tempo em operações com alto volume;
- garantir consistência na aplicação de um acionamento específico.

## 📋 Listagem de acionamentos em massa

A tela de listagem exibe todos os acionamentos em massa cadastrados, permitindo localizar registros, acompanhar seu status e realizar ações administrativas.

### Ações disponíveis

- **🔎 Filtro:** exibe ou oculta a área de filtros para facilitar a busca dos registros.
- **➕ Adicionar:** abre a tela para criação de um novo acionamento em massa.
- **↕ Ordenação:** as colunas Criação e Reversão permitem ordenar os registros em ordem crescente ou decrescente.
- **✏️ Editar:** disponibiliza as ações referentes ao acionamento selecionado:
  - **Editar:** altera as configurações do acionamento em massa.
  - **Reverter:** remove o acionamento aplicado aos contratos vinculados ao registro.
- **📄 Paginação:** permite navegar entre as páginas da listagem quando há muitos registros.

### Filtros disponíveis

Os registros podem ser localizados utilizando um ou mais dos filtros abaixo:

- **Palavra procurada:** pesquisa pelo comentário ou por outras informações do registro.
- **Cliente:** exibe apenas os acionamentos em massa de um cliente específico.
- **Status:** filtra os registros conforme sua situação.
- **Data de criação:** restringe os resultados pelo período de criação do acionamento.
- **Data de reversão:** restringe os resultados pelo período em que ocorreu a reversão do acionamento.
- **Limpar:** remove todos os filtros aplicados e retorna à listagem completa.

### Informações exibidas

Para cada registro, são apresentadas as seguintes informações:

- **Cliente**
- **Comentário**
- **Número de contratos afetados**
- **Sistema**
- **Data de criação**
- **Data de reversão**, quando houver

> A reversão remove o acionamento aplicado aos contratos vinculados ao registro, restaurando o estado anterior desses contratos. Essa operação deve ser usada apenas quando houver necessidade de desfazer um acionamento realizado em massa.

![Criar acionamento](../img/estrategia/acionamentos-massa/image-1.png)

## ➕ Criação e edição

A criação e a edição de um acionamento em massa são realizadas na mesma tela. Nela, é possível definir quais contratos serão afetados, qual acionamento será aplicado e registrar um comentário que será gravado em todos os contratos selecionados.

### Campos disponíveis

- **Sistema:** define em qual módulo o acionamento será aplicado, como Cobrança ou Jurídico.
- **Filtro:** seleciona o filtro previamente cadastrado que contém os contratos que receberão o acionamento.
- **Tipo de acionamento:** agrupa os acionamentos por categoria, facilitando a localização.
- **Acionamento:** define qual acionamento será aplicado aos contratos retornados pelo filtro selecionado.
- **Comentário:** permite informar uma observação que será registrada junto com o acionamento em todos os contratos processados.

### Fluxo de utilização

Para criar um acionamento em massa:

1. Selecione o **Sistema**.
2. Escolha o **Filtro** que contém os contratos desejados.
3. Selecione o **Tipo de acionamento**.
4. Escolha o **Acionamento** que será aplicado.
5. Informe um **Comentário**, se necessário.
6. Clique em **Enviar Acionamentos em Massa** para iniciar o processamento.

## ⚠️ Regras importantes

- valide o filtro antes de confirmar a operação, pois a ação pode impactar um grande volume de contratos;
- revise o comentário antes de enviar, já que ele será registrado em todos os contratos afetados;
- use a reversão somente quando for realmente necessário desfazer a ação aplicada em massa.
>