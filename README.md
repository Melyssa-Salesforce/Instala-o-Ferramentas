# Pré-tarefa: Instalação de Ferramentas para uso de APEX fora do Developer Console

Para utilizar o APEX fora do “Developer Console” da org, é recomendável instalar algumas ferramentas. Essas ferramentas facilitam a edição e manutenção do código. Abaixo estão os passos para instalação, na ordem correta:

---

## Passo 1: Instalar o Salesforce CLI

1. Acesse o link para baixar o Salesforce CLI adequado ao seu MacBook:  
   https://developer.salesforce.com/tools/salesforcecli?_ga=2.86353818.362057426.1745156262-2099966469.1744858743

2. Após instalar, abra o terminal e verifique a instalação com:

   ```bash
   sf --version
   ```

   Você deverá ver uma saída parecida com:

   ```
   @salesforce/cli/2.84.6 darwin-x64 node-v22.14.0
   ```

3. Atualize o CLI para a versão mais recente:

   ```bash
   sf update
   ```

   **Nota:** Pode demorar, é normal.

---

## Passo 2: Instalar o Git e criar conta no GitHub

1. Instale o Homebrew (gerenciador de pacotes) com o comando abaixo no terminal do notebook:

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. Verifique a instalação com:

   ```bash
   brew --version
   ```

   Exemplo de saída esperada:

   ```
   Homebrew 4.4.31
   ```

3. Instale o Git com:

   ```bash
   brew install git
   ```

4. Verifique se o Git foi instalado:

   ```bash
   git --version
   ```

   Exemplo de saída:

   ```
   git version 2.49.0
   ```

5. Crie uma conta no GitHub acessando:  
   https://github.com/signup?source=login

---

## Passo 3: Instalar Node.js e npm

1. Acesse o link abaixo e instale o Node.js (use as configurações padrão):  
   https://nodejs.org/en

2. Verifique a instalação do Node.js com:

   ```bash
   node --version
   ```

   Exemplo de saída:

   ```
   v23.10.0
   ```

3. Verifique a instalação do npm com:

   ```bash
   npm --version
   ```

   Exemplo de saída:

   ```
   10.9.2
   ```

---

## Passo 4: Instalar o Visual Studio Code e Salesforce Extension Pack

1. Baixe o VSCode no link:  
   https://code.visualstudio.com/

2. Abra o VSCode e vá até a aba de extensões (ícone de quadrado na lateral esquerda).

3. Pesquise por `Salesforce Extension Pack` e instale a primeira extensão que aparecer clicando em **Install**.

---

### Observação:
Para conectar com uma org, será necessário **criar uma senha** para sua org na aba **"Get Your Credentials"**.
