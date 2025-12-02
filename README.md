# 🛡️ Gestão de Comunidade Técnica (Fernandes Lab)

Este repositório documenta a administração e estruturação lógica de um servidor de comunidade técnica, aplicando conceitos de segurança da informação e automação.

## ⚙️ Competências Técnicas Aplicadas
A administração deste servidor simula um ambiente corporativo de TI, utilizando:

- **Gestão de Identidade e Acesso (RBAC):** - Criação de hierarquia de cargos (Admin, Mod, Member).
  - Segregação de funções e permissões granulares (quem pode ver/editar o quê).
  - *Conceito similar ao Active Directory (Security Groups).*

- **Automação e ChatOps:**
  - Implementação de bots (MEE6, Dyno, Carl-bot) para tarefas repetitivas.
  - Automação de boas-vindas (Onboarding) e moderação preventiva (Anti-spam).

- **Arquitetura da Informação:**
  - Organização lógica de canais por categorias e tópicos (Redes, Segurança, Off-topic).
  - Gestão de logs de auditoria (quem baniu, quem apagou mensagem).

## 📸 Evidências do Projeto

### Configuração de Cargos e Permissões (RBAC)
<img width="800" alt="Print mostrando a organização dos canais e categorias no Discord" src="https://github.com/user-attachments/assets/22c92c37-3ab6-4746-8e3e-ce43e3c27ca8" />

### Automação com Bots
<img width="800" alt="Print mostrando a tela de logs de auditoria do servidor" src="https://github.com/user-attachments/assets/93616dd4-d6c0-460f-9a76-ac88e7c50138" />

### 🤖 Automação de Rotinas (Cron Jobs & Notificações)
Implementação de sistema automatizado para distribuição de informações em tempo real (Notícias e Atualizações de Ativos do GTA V).

- **O Desafio:** Necessidade de notificar a base de usuários diariamente às 03:00 AM (BRT) sem intervenção humana.
- **A Solução:**
  - Configuração de **Tasks Agendadas** (lógica *Cron Job*) com *offset* de segurança de 5 minutos.
  - Estruturação de dados via **JSON (Rich Embeds)** para padronização visual.
  - Integração com links dinâmicos, garantindo operação **100% Zero-Touch** (manutenção zero).
    
<img width="800" alt="Print da automação de notícias GTA V" src="https://github.com/user-attachments/assets/bbc1be1b-b525-4604-8996-b9718156bd03" />


