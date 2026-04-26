# 🛡️ Home Lab: CyberSecurity & IT Operations
**Projeto prático simulando um ecossistema corporativo completo: da administração de sistemas à detecção de ameaças.**

---

## 📅 Demonstração Técnica

### 1. Windows Server: Active Directory & Hardening
Implementação de um Controlador de Domínio para gestão centralizada de identidades e aplicação de políticas de segurança (GPO).
* **Configuração:** Instalação do AD DS e implementação de GPO de restrição.
* **Controle:** Bloqueio de acesso ao Painel de Controle para usuários comuns.

![Configuração GPO](./imgs/AD_DS_adm.png)
*Interface de Gerenciamento de Política de Grupo (GPMC).*

![Bloqueio na Prática](./imgs/AD_DS_block.png)
*Validação do bloqueio com o usuário "lucas.raraujo".*

---

### 2. Jira: Gestão de Incidentes (Framework ITIL)
Simulação do ciclo de vida de um chamado técnico utilizando o Jira Service Management.
* **Fluxo:** Registro de incidente através do portal do cliente.
* **Resolução:** Atendimento técnico com documentação de causa raiz no encerramento do ticket.

![Portal do Cliente](./imgs/Jira_client.png)
*Chamado aberto pelo usuário relatando a restrição.*

![Resolução Técnica](./imgs/Jira_response.png)
*Ticket concluído com nota técnica interna explicando a GPO.*

---

### 3. MITRE ATT&CK: Inteligência de Ameaças
Uso do framework global para validar as táticas de defesa aplicadas no laboratório.

![Mapeamento Mitre](./imgs/MITRE_ATT&CK.png)
*Estudo das técnicas de mitigação baseada no MITRE.*

---

### 4. Splunk: Monitoramento e SIEM
Operação em ambiente de SIEM para análise de logs e criação de visualizações de segurança.

![Dashboards Splunk](./imgs/splunk_chart.png)
*Visualização gráfica comparando tráfego de rede.*

![Logs Brutos](./imgs/splunk_logs.png)
*Resultado da query estatística no Splunk.*

![Certificado THM](./imgs/THM.png)
*Conclusão do treinamento prático "Splunk Basics" no TryHackMe.*
