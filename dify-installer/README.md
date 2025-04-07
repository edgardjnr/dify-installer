# 🚀 Dify Installer – Setup Automático com Docker

Bem-vindo ao instalador oficial do **DifyAI**!  
Esse script foi feito para você que quer subir sua stack Dify de forma rápida, segura e 100% automatizada, direto em uma VPS (Ubuntu).

---

## 📦 O que esse script faz?

Este instalador realiza todo o processo de forma **não-interativa**, incluindo:

1. ✅ Verificação e instalação do `git` e `curl`
2. ✅ Instalação automatizada do Docker via script oficial
3. ✅ Clonagem do repositório do Dify
4. ✅ Geração e configuração do arquivo `.env` com seus domínios
5. ✅ Subida dos containers com `docker compose`
6. ✅ Exibição final com acesso aos endpoints web e API

---

## ⚙️ Pré-requisitos

- Uma máquina com **Ubuntu (20.04 ou superior)**
- Acesso `root` ou permissão com `sudo`
- Domínios válidos e apontados para a VPS (WEB e API)

---

## 💻 Como usar

### 🧠 Método 1 – Clonando o repositório

```bash
git clone https://github.com/edgardjnr/dify-installer.git
cd dify-installer
chmod +x install-dify.sh
./install-dify.sh
```

### 🧠 Método 2 – Direto por ssh na sua vps

```bash
bash <(curl -s https://raw.githubusercontent.com/edgardjnr/dify-installer/main/install-dify.sh)
