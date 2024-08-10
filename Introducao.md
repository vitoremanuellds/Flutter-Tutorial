# Introdução

## Como instalar o Flutter no Windows

### Extensão do Flutter no VS Code

Primeiro, você irá precisar instalar o VS Code para instalar o flutter de forma automática.

Após instalar o VS Code, você irá precisar instalar a extensão do Flutter para o VS Code.

![VS Code Extension Page](assets/extension-page.png)

![Flutter extension](assets/flutter-extension.png)

### Instalando o SDK do Flutter

Depois de instalar a extensão,vamos instalar agora o Flutter no nosso computador. Para isso, precisamos precionar `ctrl + sifht + p` e digitar `flutter`. Selecione a opção `Flutter: Run Flutter Doctor`.

![VS Code Commands](assets/vs-commands.png)

![Flutter command](assets/flutter-doctor.png)

Assim, irá aparecer uma pequana janela no canto inferior direito, informando que não foi possível localizar o SDK do Flutter. Dessa forma, iremos selecionar a opção de `Download SDK`.

![Download SDK](assets/download-sdk.png)

Agora precisamos escolher o local de instalação do SDK do Flutter. Escolha uma pasta de sua escolha. Você pode escolher a pasta do seu usuário sem problemas.

![Choosing Local for installation](assets/choose-flutter-installation-local.png)

Agora, precisamos esperar a extensão baixar o Flutter.

![Installing](assets/installing.png)

![Finish Installing](assets/finish-installing.png)

A função Flutter Doctor verifica se a instalação do Flutter no nosso computador está funcionando da maneira correta.

### Adicionando o SDK do Flutter ao PATH

Após todo esse processo, precisamos adicionar também a pasta do SDK do Flutter em nosso PATH, para que possamos acessar o Flutter pelo terminal, além de fornecer o caminho para que a extensão do Flutter trabalhe corretamente.

Para isso, vamos precisar do caminho para a pasta do SDK do Flutter.

Vá até a pasta.

![Flutter local of installation](assets/local.png)

Entre nela e clique na barra superior onde aparece o caminho até a pasta.

![Flutter local of installation](assets/path-bar.png)

Copie o caminho da pasta.

![Flutter path](assets/path.png)

Abra o menu iniciar e pesquise por `Variáveis de ambiente`. Clique na primeira opção que aparecer.

![Environment Variables](assets/variables.png)

Clique em `Variáveis de ambiente`. 

![Environment Variables Window](assets/variables-2.png)

Selecione a variável `Path` e clique em `Editar`. 

![Edit Path](assets/edit-path.png)

Clique em `Novo` e cole o caminho que você copiou e adicione no final dele `\bin`.

![Add Flutter Path](assets/add-flutter-path.png)

Clique em `Ok` até sair da primeira janela que você abriu.

![Confirmation](assets/confirmation.png)

![Confirmation](assets/confirmation-2.png)

![Confirmation](assets/confirmation-3.png)

Agora, o Flutter já está instalado na sua máquina e o seu caminho já está no PATH.

## Criando um novo projeto

Para criar um novo projeto, precisamos executar o comando `Flutter: New Project` no VS Code. Para isso, precisamos precionar novamente `ctrl + shift + p` e digitarmos `flutter`. Agora, nós escolhemos o `Flutter: New Project`.

![](assets/new-project.png)

Podemos escolher várias opções de templates, mas vamos escolher o template `Application`. 

![](assets/templates.png)

Logo após, precisamos escolher o local do nosso projeto. Escolha a pasta de sua escolha.

![](assets/project-local.png)

Dê um nome a sua aplicação.

![](assets/new-project-name.png)

O VS Code irá automaticamente abrir a pasta do projeto.

![](assets/project.png)

### Rodando o projeto na versão Web

Para testarmos o projeto, vamos rodá-lo na versão WEB do projeto. Como o Edge já vem pré-instalado, podemos testá-lo através dele. Para isso, precisamos escolher o dispositivo em que o projeto irá executar. Para isso, vamos no canto inferior direito do VS Code, e vamos clicar no botão ao lado do botão de notificações e do lado do botão da linguagem do arquivo aberto.

![](assets/device.png)

Agora, vamos selecionar a opção do Edge.

![](assets/edge-device.png)

Assim, agora só precisamos executar a aplicação, clicando no botão de play no canto superior direito do VS Code.

![](assets/running.png)

Assim, a aplicação irá abrir no Edge, ou em qualquer device que você escolher.

![](assets/running-on-edge.png)