## 📌 Visão Geral

A tela **Login** é a porta de entrada para o sistema, permitindo que usuários autenticados acessem as funcionalidades de acordo com suas permissões.

Para realizar o acesso, o usuário deve informar suas credenciais de autenticação (usuário e senha). Após a validação dos dados, o sistema libera o acesso aos módulos e funcionalidades autorizados para o perfil do usuário.

![Tela de Login](../img/login/login.png)

## 📝 Campos

### 👤 Usuário

**Descrição:** Campo utilizado para informar o usuário cadastrado no sistema.

**Obrigatório:** Sim.

### 🔒 Senha

**Descrição:** Campo destinado à senha de acesso do usuário.

**Obrigatório:** Sim.

**Observação:** O ícone 👁️ permite exibir ou ocultar a senha digitada.

## ⚙️ Ações Disponíveis

### 🔓 Logar

Realiza a autenticação do usuário e, caso as credenciais sejam válidas, concede acesso ao sistema.

## 💡 Regras de Negócio

### ⏳ Tempo de Inatividade

Por motivos de segurança, o sistema encerra automaticamente a sessão do usuário após **20 minutos de inatividade**. Para continuar utilizando o sistema, será necessário realizar um novo login.

### 👤 Sessão Única

Um mesmo usuário pode manter apenas **uma sessão ativa** por vez. Caso seja realizado um novo login com as mesmas credenciais em outro dispositivo ou navegador, a sessão anterior será encerrada automaticamente.

## 🚫 Possíveis Mensagens

Se o sistema exibir mensagens de erro no login, eu documentaria também.

Por exemplo:

### Usuário ou senha inválidos

Exibida quando as credenciais informadas não correspondem a um usuário válido.

### Sessão já iniciada

Exibida quando o usuário já possui uma sessão ativa, caso o sistema bloqueie um segundo acesso em vez de substituir a sessão existente.