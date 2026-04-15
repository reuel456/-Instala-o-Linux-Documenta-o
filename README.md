# 🐧 Guia de Instalação: Linux no VirtualBox

![Status](https://img.shields.io/badge/Status-Conclu%C3%ADdo-brightgreen)
![OS](https://img.shields.io/badge/OS-Ubuntu%2024.04-orange)
![VirtualBox](https://img.shields.io/badge/VirtualBox-7.0-blue)

Este repositório contém a documentação completa para a instalação de uma distribuição Linux em ambiente virtualizado utilizando o Oracle VM VirtualBox. Ideal para estudantes e desenvolvedores que buscam um ambiente de testes seguro.

---

## 🛠️ Pré-requisitos

Antes de iniciar, certifique-se de ter instalado:
* [VirtualBox](https://www.virtualbox.org/) (Versão 7.0 ou superior recomendada).
* Imagem ISO da distribuição (Ex: [Ubuntu Desktop](https://ubuntu.com/download/desktop)).
* Pelo menos **25GB** de espaço em disco e **4GB** de RAM disponíveis.

---

## 🚀 Manual de Instalação

### 1. Criação da Máquina Virtual (VM)
1. Abra o VirtualBox e clique em **Novo**.
2. Defina o nome da VM, a pasta de destino e selecione a ISO baixada.
3. No hardware, reserve ao menos **2048 MB** de RAM e **2 CPUs**.
**<img width="955" height="539" alt="aaaaaaaaaaaaaaaaaaaaaaaaa" src="https://github.com/user-attachments/assets/70a9e251-8639-4c81-b2f2-715d38abf500" />**
> **<img width="773" height="559" alt="Captura de tela 2026-04-15 100049" src="https://github.com/user-attachments/assets/eb97ca9d-239b-4308-9b98-50a824678b41" />**
### 2. Configurações de Armazenamento
Para garantir que a VM inicie pelo "instalador":
1. Vá em `Configurações > Armazenamento`.
2. Verifique se o arquivo `.iso` está montado na unidade de CD/DVD.

> **<img width="1106" height="596" alt="ghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghghgh" src="https://github.com/user-attachments/assets/8fb6db9f-a6dc-4b91-82c3-efe2b4564514" />
**

### 3. O Processo de Instalação do OS
1. Clique em **Iniciar**.
2. Escolha o idioma e o layout do teclado.
3. Selecione **Instalação Normal** e a opção **"Apagar disco e instalar o Ubuntu"** (Lembrando que isso afeta apenas o disco virtual).
4. Defina seu fuso horário e crie seu usuário.

> **<img width="1918" height="1078" alt="eueueuueu" src="https://github.com/user-attachments/assets/5cb058ee-0209-4569-be1e-83e03d9790ad" />
**

### 4. Pós-Instalação: Guest Additions
Para habilitar tela cheia e área de transferência compartilhada:
1. No menu superior da janela da VM, vá em `Dispositivos > Inserir Imagem de CD dos Adicionais de Convidado`.
2. Siga as instruções no terminal e reinicie a máquina.

---

## 🖥️ Resultado Final
Após o reboot, o sistema estará pronto para uso.

> **<img width="1276" height="802" alt="davidavidavidavidavidavidavidavidavidavidavi" src="https://github.com/user-attachments/assets/6f36e091-f55b-4e47-87a4-308ee595650a" />
**

---

## 🛠️ Comandos Úteis (Pós-Instalação)
Abra o terminal (`Ctrl+Alt+T`) e execute:

```bash
# Atualizar a lista de repositórios
sudo apt update

# Instalar as atualizações do sistema
sudo apt upgrade -y


---
