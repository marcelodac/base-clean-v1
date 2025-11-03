# Base vRPex Rework Clean – MG Roleplay

Bem-vindo à **Base vRPex Rework Clean**! Esta base é projetada para **FiveM**, compatível com **vRPex Rework**, **oxmysql**, e vem com scripts básicos de **login**, **spawn** e **HUD**.  

---

## 🧰 Pré-requisitos

- **txAdmin** instalado
- **MySQL/MariaDB** (usuário root sem senha)
- **FiveM artifacts** atualizados (build >= 2944)
- Conexão à internet para baixar os recursos automaticamente

---

## ⚡ Instalação via txAdmin

1. Abra o **txAdmin → Criar Servidor → Custom Recipe**
2. Cole o link raw do GitHub:
3. Clique em **Instalar**
4. O txAdmin fará automaticamente:
   - Download do **vRPex Rework**
   - Download do **oxmysql**
   - Download dos scripts básicos (**login, spawn, HUD**)
   - Criação do banco de dados `vrpex`
   - Configuração do `server.cfg`

---

## ⚙️ Configuração do servidor

- Abra o arquivo `server.cfg` após a instalação
- Substitua a license key:
- Garanta que o MySQL esteja ativo e com o usuário `root` sem senha
- O banco criado automaticamente será chamado: `vrpex`

---

## 🧩 Scripts básicos incluídos

1. **vrp_identity** → Sistema de login e registro automático de personagens
2. **vrp_spawn** → Sistema de spawn inicial
3. **vrp_hud** → HUD limpa, leve e responsiva
4. Todos os scripts já configurados para funcionar com vRPex Rework e OxMySQL

---

## 🛠 Como iniciar o servidor

1. Abra o **txAdmin**
2. Clique em **Start Server**
3. Aguarde os recursos carregarem
4. Teste entrando no servidor no FiveM com sua conta Steam

---

## ✅ Dicas de manutenção

- Sempre execute o **update dos scripts** via GitHub pull, nunca substitua manualmente  
- Evite scripts obfuscados ou antigos que dependem de `vrp_mysql` ou `mysql-async`  
- Adicione novos scripts em `/resources/[scripts]/` e `ensure` no `server.cfg`  
- Para backups do banco, use o **HeidiSQL** ou **phpMyAdmin**  

---

💡 **Sugestão:** personalize a base incluindo mapas, jobs, e menus NUI, mantendo sempre a compatibilidade com **vRPex Rework**.

---

**Desenvolvido por big-dev – Base Clean MG Roleplay**
