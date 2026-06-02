# 🌐 Script de Deploy de Servidor Web - Apache

Este script automatiza a configuração de um servidor web Apache em sistemas Linux, incluindo atualizações do sistema, instalação de pacotes e deploy de uma aplicação web a partir de um repositório GitHub.

## 📋 Funcionalidades

- ✅ Atualização automática do sistema (APT)
- ✅ Instalação do servidor web Apache2
- ✅ Instalação do utilitário unzip
- ✅ Download automático da aplicação via GitHub
- ✅ Deploy direto no diretório padrão do Apache (`/var/www/html/`)

## 🚀 Aplicação Deployada

O script faz o deploy do projeto **Linux Site DIO** disponível em:
- 🔗 [GitHub - denilsonbonatti/linux-site-dio](https://github.com/denilsonbonatti/linux-site-dio)

## 📦 Pacotes Instalados

| Pacote | Finalidade |
|--------|------------|
| `apache2` | Servidor web HTTP |
| `unzip` | Descompactação de arquivos ZIP |
| `update/upgrade` | Atualização do sistema |

## 🔧 Pré-requisitos

- Sistema operacional baseado em Debian/Ubuntu
- Acesso root ou permissão `sudo`
- Conexão com internet ativa
- Porta 80 liberada (para acesso ao servidor web)

## 💻 Como Executar

### 1. Clone o repositório
```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
cd nome-do-repo
