## 📌 Visão Geral

A tela de filtros é utilizada para criar regras de seleção que podem ser reutilizadas em diferentes processos do sistema. Ela é especialmente útil quando você precisa segmentar contratos, organizar cadastros ou trabalhar com listas maiores de forma mais objetiva.

Com os filtros, é possível definir critérios claros e aplicar essas regras sempre que necessário, sem precisar montar a lógica novamente a cada vez.

## 🎯 Quando usar os filtros

Os filtros são indicados quando você deseja:

- localizar registros com base em critérios específicos;
- reutilizar a mesma regra em diferentes telas ou operações;
- segmentar dados por grupo, cliente, carteira ou tipo de informação;
- facilitar a execução de ações em massa com maior precisão.

## 🚀 Como começar

Para trabalhar com filtros, siga este fluxo básico:

1. Acesse a tela de filtros.
2. Crie um novo filtro definindo nome, grupo, cliente e carteira.
3. Informe a regra de comparação utilizando operador e tipo do filtro.
4. Salve o filtro e utilize-o nas funcionalidades compatíveis.

## 📝 Cadastro de filtro

![Criação de filtros](../img/estrategia/filtros/create.png)

Ao criar um filtro, alguns campos são fundamentais para que a regra funcione corretamente.

### 🏷️ Nome do filtro

Define o nome que identificará o filtro dentro do sistema. Esse campo é importante para facilitar a localização e a reutilização posterior do filtro.

**Obrigatório:** Sim.

### 👥 Grupo

Define o grupo de usuários que poderá visualizar e utilizar o filtro.

**Obrigatório:** Sim.

> É possível vincular o filtro a um ou mais grupos, conforme a necessidade da operação.

### 🏢 Cliente

Define o cliente ao qual o filtro será vinculado, como Santander, Banestes e outros.

**Obrigatório:** Sim.

### 💼 Carteira

Define a carteira que será considerada na aplicação do filtro. Esse campo permite restringir a regra a uma carteira específica ou a todas as carteiras disponíveis.

**Obrigatório:** Sim.

### ⚙️ Operador

Define a condição lógica utilizada na regra do filtro. O operador determina como o sistema compara o valor informado com os dados da base.

**Operadores disponíveis:**

- É
- Não é
- Contém
- Maior que
- Menor que
- Entre

### 📋 Tipo do filtro

Define qual campo da base será utilizado como critério da regra. Esse campo determina a informação que será analisada durante a execução do filtro.

**Exemplos:**

- Status do Agendamento
- Faixa de Atraso
- Cidade
- Estado
- Valor da Dívida

## 🔎 Listagem de filtros

![Listagem de filtros](../img/estrategia/filtros/listagem.png)

A tela de listagem permite consultar e gerenciar todos os filtros cadastrados no sistema. A busca pode ser realizada por nome, usuário, grupo, tipo, cliente e carteira, o que facilita a localização de filtros específicos.

### Parâmetros da listagem

#### 🏷️ Nome do filtro

Pesquisa filtros pelo nome ou por parte do nome.

#### 👤 Usuário

Filtra os registros pelo usuário responsável pela criação ou vinculação do filtro.

#### 👥 Grupo

Exibe apenas os filtros vinculados ao grupo selecionado.

#### 📋 Tipo

Filtra os filtros conforme a categoria utilizada, como cobrança ou jurídico.

#### 🏢 Cliente

Restringe a listagem aos filtros pertencentes ao cliente selecionado.

#### 💼 Carteira

Exibe apenas os filtros relacionados à carteira escolhida.

#### ❌ Limpar

Remove todos os filtros aplicados e restaura a listagem completa.

## 📊 Colunas da listagem

![Colunas de filtros](../img/estrategia/filtros/listagem1.png)

As colunas principais da lista ajudam a compreender rapidamente cada filtro cadastrado:

- **Nome do Filtro**: nome do filtro cadastrado.
- **Quantidade de Contratos**: quantidade de contratos retornados pela regra.
- **Executando em**: indica onde o filtro está sendo utilizado, quando aplicável.
- **Grupo Vinculado**: grupo ao qual o filtro pertence.
- **Última Atualização**: data e hora da última alteração realizada.

### 💡 Ordenação

As colunas com o ícone de ordenação permitem classificar os registros em ordem crescente ou decrescente. Para alterar a ordem, clique na seta ao lado do nome da coluna.

## ⚙️ Ações disponíveis

![Ações de filtros](../img/estrategia/filtros/acao.png)

### ✏️ Editar filtro

Permite alterar as informações e as regras de um filtro já cadastrado.

### 📄 Carregar contratos do filtro

Exibe todos os contratos retornados pelo filtro selecionado, permitindo visualizar os registros que atendem aos critérios definidos.

### 🔄 Atualizar filtro(s)

Atualiza manualmente os filtros selecionados. Como os filtros não são atualizados automaticamente quando há alterações na base, essa ação é importante para refletir as informações mais recentes.

### 🗑️ Excluir filtro

Remove permanentemente o filtro selecionado do sistema. Após a exclusão, ele não poderá mais ser utilizado.

### 🔍 Exibir ou ocultar filtros

Mostra ou esconde a área de pesquisa da listagem, permitindo visualizar ou ocultar os campos usados para filtrar os registros.

### ➕ Criar filtro

Abre a tela de criação de um novo filtro, permitindo definir parâmetros, regras e demais configurações.

## ✅ Regras importantes

- revise os critérios antes de salvar o filtro;
- verifique se o grupo, cliente e carteira estão corretos;
- use nomes claros para facilitar a identificação futura;
- atualize os filtros quando houver mudanças na base de dados para manter os resultados consistentes.