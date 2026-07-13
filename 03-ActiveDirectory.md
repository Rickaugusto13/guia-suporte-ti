# 🔑 Active Directory (AD) e Gestão de Identidades (IAM)

Administração de diretórios focada em segurança da informação, governança de acessos e conformidade com requisitos regulatórios do mercado financeiro [4, 18].

## 🏗️ Estrutura e Governança
- **Unidades Organizacionais (OUs):** Organização lógica alinhada às áreas de negócio (Financeiro, TI, Riscos) para aplicação direcionada de políticas.
- **Grupos de Segurança:** Implementação do modelo de controle de acesso baseado em funções (RBAC), garantindo o princípio do menor privilégio.
- **GPOs (Group Policy Objects):** Padronização de segurança em servidores e endpoints, incluindo políticas de auditoria de logon e restrições de software.

## 🛡️ Conformidade e Auditoria
- **Ciclo de Vida do Usuário:** Processos de provisionamento e desativação imediata (offboarding) para evitar riscos de segurança [15].
- **Auditoria de Acessos:** Revisão periódica de permissões em pastas de rede e sistemas corporativos para atendimento a auditorias externas.
- **Ambiente Híbrido:** Gestão integrada entre AD local e **Microsoft Entra ID (Azure AD)** para Single Sign-On (SSO) [14, 16].

## 📑 Automação de Gestão
Uso de scripts PowerShell para auditoria de contas inativas, reset de senhas em massa e identificação de bloqueios recorrentes de contas de serviço.
