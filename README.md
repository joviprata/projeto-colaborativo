# Projeto Colaborativo
### Realização de Atividade Prática da FGV - Fluxo Básico de Colaboração com Git
Este projeto tem como objetivo simular o fluxo básico de trabalho utilizando o Git e GitHub, utilizado em equipes de desenvolvimento.

## 1. Criação do repositório no GitHub, README.md e tarefas.txt:

<p align="center">
  <img src="https://github.com/user-attachments/assets/6dbca72e-4827-4bee-9b85-8e8d0bed58df">
</p>

O repositório foi criado com as configurações apresentadas no print.<br/>
Em seguida, foi criado o arquivo tarefas.txt com duas tarefas iniciais:

```
- Configurar ambiente
- Criar estrutura do projeto
```

## 2. Criação da branch feature-nova-tarefa:

<p align="center">
  <img src="https://github.com/user-attachments/assets/a84302fb-2432-4270-ab5e-bd51e654ada6">
</p>

O repositório foi clonado localmente usando ```git clone``` e ```git pull```. Em seguida, a pasta contendo o repositório foi aberta no VSCode, onde foi criado a nova branch feature-nova-tarefa usando o terminal.

## 3. Criação dos commits:

<p align="center">
  <img src="https://github.com/user-attachments/assets/50fc0a8b-3c5a-4d30-aecd-ca72881dfcbe">
</p>

Dois commits foram realizados na branch feature-nova-tarefa: "criação de helloworld.js" e "adicionadas duas novas tarefas ao arquivo tarefas.txt", de tal forma que o arquivo tarefas.txt ficou assim:

```
- Configurar ambiente
- Criar estrutura do projeto
- Criar arquivo helloworld.js
- Revisar código
```

### 4. Push da branch para o remoto:

<p align="center">
  <img src="https://github.com/user-attachments/assets/035ac9f9-3323-4064-8cf6-4359e8412302">
</p>

Uma tentativa inicial de executar o comando ```git push``` deu erro, como se pode observar no print. Isso se deve ao fato de a branch ter sido criada localmente, e não ter sido encontrada no GitHub.<br/>
Para resolver isso, foi executado o comando sugerido pelo Git:

```git push --set-upstream origin feature-nova-tarefa```

Que criou a branch remotamente e realizou o push dos commits a essa nova branch com sucesso.

### 5. Criação do Pull Request:

<p align="center">
  <img src="https://github.com/user-attachments/assets/4b9b3499-5970-4094-9b0f-fcd63669921a">
</p>

A criação do Pull Request foi feita usando a extensão GitHub Pull Requests no VSCode.<br/>
A edição deste README foi feito posteriormente no GitHub, e o commit foi incluído automaticamente no Pull Request.
