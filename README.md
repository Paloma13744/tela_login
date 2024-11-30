# Tela de Login - Atividade de Programação para Dispositivos Móveis

## Descrição

Esta aplicação Android implementa uma tela de login, onde o usuário pode inserir seu e-mail e senha para acessar o sistema. A tela é composta por diversos elementos interativos, incluindo campos de texto para o e-mail e senha, botões para login e opções de login social (Facebook e Google).

A interface é construída utilizando `ConstraintLayout` para garantir uma disposição flexível e responsiva dos elementos na tela. A tela também contém imagens de fundo, logotipo e um ícone, além de exibir alguns textos informativos e instruções para o usuário.

## Funcionalidades

- **Campo de E-mail:** O usuário pode digitar seu e-mail no campo de texto.
- **Campo de Senha:** O usuário pode digitar sua senha, com a opção de exibir/ocultar a senha.
- **Lembrar-me:** Uma opção de checkbox para o usuário escolher se deseja ser lembrado no próximo acesso.
- **Botão de Login:** Um botão para submeter as credenciais inseridas e realizar o login.
- **Login Social:** Opções para login via Facebook e Google, com botões estilizados.
- **Navegação:** A tela de login está preparada para futuras integrações, onde o login bem-sucedido pode redirecionar o usuário para outra tela do aplicativo.
- **Ícone de Aplicativo:** O ícone do aplicativo será exibido na barra de título e também na tela inicial do dispositivo.

## Estrutura da Interface

A interface é composta por:

1. **Imagem de fundo:** Usada para estilizar a tela de login, com uma imagem fixa na parte superior.
2. **Logo:** Exibe o logotipo do aplicativo no centro da tela.
3. **Campos de entrada:**
   - **E-mail:** Para inserir o endereço de e-mail.
   - **Senha:** Para inserir a senha, com uma opção de toggle para mostrar/ocultar a senha.
4. **Checkbox "Lembrar-me":** Para lembrar o usuário nas próximas vezes.
5. **Botões:** 
   - **Login:** Envia as informações de login.
   - **Login com Facebook e Google:** Para login social com ícones representativos.
6. **Links e Texto adicional:** Como "Acessar com" e "Criar conta" com links para integração futura.

## Tecnologias Utilizadas

- **Android Studio:** Ambiente de desenvolvimento para a criação da aplicação.
- **Kotlin:** Linguagem de programação para desenvolvimento Android.
- **ConstraintLayout:** Layout utilizado para organizar os elementos de forma flexível.
- **Material Design:** Para botões e campos de texto estilizados.
- **Fonts personalizadas:** Uso da fonte "Poppins" para uma aparência moderna.

## Como Executar

1. **Clonar o repositório**:

   ```bash
   git clone https://github.com/Paloma13744/tela_login.git
