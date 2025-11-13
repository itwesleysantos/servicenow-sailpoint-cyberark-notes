![alt text](https://img.icons8.com/?size=32&id=0raNoKwBezGl&format=png ) 

# 🆔 Gerenciamento de Identidade e Acesso (IAM)

O Gerenciamento de Identidade e Acesso (IAM) é uma disciplina de cibersegurança crucial que lida com a **proteção de identidades digitais** e o controle das permissões de acesso dos usuários em um sistema de TI. O objetivo é garantir que apenas as **pessoas (ou máquinas) certas** acessem os recursos certos, no momento correto.

Com o aumento do trabalho remoto, da computação em nuvem e da Inteligência Artificial (IA), a superfície de ataque cresceu, e o IAM se tornou essencial: 30% dos ataques cibernéticos envolvem roubo de contas válidas.

---

## 🔑 Quatro Pilares Essenciais do IAM

As implementações eficazes de IAM se apoiam em quatro componentes interligados:

1.  **Administração (Ciclo de Vida):** Processo de **criar, manter, e descartar** identidades digitais (usuários humanos e não humanos) em um banco de dados central. Define quem e o que está no sistema e seus direitos básicos.
2.  **Autenticação:** Processo que **verifica a identidade do usuário** ao fazer login. Métodos avançados como a **Autenticação Multifactor (MFA)** são cruciais para aumentar a segurança, exigindo mais de uma credencial (ex: senha + código do celular).
3.  **Autorização:** Após a autenticação, este processo **concede o nível apropriado de acesso** ao recurso. É geralmente baseado no princípio do **privilégio mínimo**, onde o usuário só recebe as permissões estritamente necessárias para o trabalho (ex: Controle de Acesso Baseado em Função - RBAC).
4.  **Auditoria:** O monitoramento contínuo das atividades dos usuários para **garantir a conformidade regulatória** e identificar se invasores ou usuários autorizados estão abusando de seus privilégios.

---

## 🛠️ Soluções e Tecnologias-Chave

As ferramentas de IAM buscam simplificar e automatizar o controle de acesso por meio de diversas soluções:

* **Logon Único (SSO):** Permite que o usuário acesse múltiplos aplicativos com **apenas um conjunto de credenciais**.
* **Autenticação Adaptativa (Baseada em Risco):** Usa **IA e Machine Learning (ML)** para analisar o contexto do login (local, dispositivo) e exigir mais fatores de autenticação se o risco for maior.
* **Controle de Acesso (Diferentes Frameworks):** Além do RBAC, existem o **MAC** (obrigatório, baseado em níveis de confiança) e o **ABAC** (baseado em atributos de usuário, objeto e ação).
* **Gerenciamento de Acesso Privilegiado (PAM):** Ferramentas específicas para proteger as **contas de maior risco** (administradores), utilizando cofres e protocolos de acesso just-in-time.
* **Federação de Identidade:** Permite que sistemas diferentes compartilhem informações de identidade (ex: usar login do Google em um novo aplicativo).
* **IDaaS (Identity as a Service):** Soluções de IAM baseadas em nuvem (SaaS), ideais para redes complexas e distribuídas.

---

## 🔬 IAM e o Cenário Futuro

* **Malha de Identidade (Identity Fabric):** Organizações estão investindo em arquiteturas que **unificam todos os sistemas de identidade** em uma rede integrada, usando ferramentas holísticas de IAM para simplificar a gestão e fortalecer a segurança.
* **IAM e IA:** A IA (especialmente a IA generativa) aumenta o número de **identidades não humanas** na rede (Agentes de IA), tornando o PAM essencial para proteger essas novas contas. Por outro lado, a IA é usada positivamente em ferramentas IAM para análise de risco, controle de conformidade e verificação de usuários.
  
---

## 🔗 Source

As informações contidas neste resumo foram compiladas a partir do artigo publicado por **Mattew Kosinski** e **Amber Forrest** no **IBM Think**.

* **O que é IAM (Identity and Acess Management)?:** https://www.ibm.com/br-pt/think/topics/identity-access-management

---

![alt text](https://img.icons8.com/?size=32&id=NvYRxC2UBsLO&format=png ) 

# 🆔 Identity and Access Management (IAM)

Identity and Access Management (IAM) is a critical cybersecurity discipline that deals with the **protection of digital identities** and the control of user access permissions within an IT system. The goal is to ensure that only the **right people (or machines)** access the right resources, at the right time.

With the rise of remote work, cloud computing, and Artificial Intelligence (AI), the attack surface has expanded, and IAM has become essential: 30% of cyberattacks involve the theft of valid accounts.

---

## 🔑 Four Essential Pillars of IAM

Effective IAM implementations rest on four interconnected components:

1.  **Administration (Lifecycle):** The process of **securely creating, maintaining, and retiring** digital identities (human and non-human users) in a central database. It defines who and what is in the system and their basic rights.
2.  **Authentication:** The process that **verifies the user's identity** upon login. Advanced methods like **Multi-Factor Authentication (MFA)** are crucial for increasing security, requiring more than one credential (e.g., password + phone code).
3.  **Authorization:** After authentication, this process **grants the appropriate level of access** to a resource. It is typically based on the **principle of least privilege**, where the user only receives the permissions strictly necessary to perform their job (e.g., Role-Based Access Control - RBAC).
4.  **Auditing:** The continuous monitoring of user activities to **ensure regulatory compliance** and identify whether attackers or authorized users are abusing their privileges.

---

## 🛠️ Key Solutions and Technologies

IAM tools seek to simplify and automate access control through various solutions:

* **Single Sign-On (SSO):** Allows the user to access multiple applications with **only one set of login credentials**.
* **Adaptive Authentication (Risk-Based):** Uses **AI and Machine Learning (ML)** to analyze the context of a login (location, device) and require more authentication factors if the risk is higher.
* **Control of Access (Different Frameworks):** In addition to RBAC, there is **MAC** (mandatory, based on clearance levels) and **ABAC** (based on user, object, and action attributes).
* **Privileged Access Management (PAM):** Specific tools to protect **highest-risk accounts** (system administrators), using vaults and just-in-time access protocols.
* **Identity Federation:** Allows disparate systems to share identity information (e.g., using a Google login for a new application).
* **IDaaS (Identity as a Service):** Cloud-based IAM solutions (SaaS), ideal for complex and distributed networks.

---

## 🔬 IAM and the Future Landscape

* **Identity Fabric:** Organizations are investing in architectures that **unify all identity systems** into an integrated network, using holistic IAM tools to simplify management and strengthen security.
* **IAM and AI:** AI (especially generative AI) increases the number of **non-human identities** on the network (AI Agents), making PAM essential for protecting these new accounts. Conversely, AI is used positively in IAM tools for risk analysis, compliance control, and user verification.

---

## 🔗 Source

The information contained in this summary was compiled from article published by **Matthew Kosinski** and **Amber Forrest** on **IBM Think**.

* **What is IAM (Identity and Access Management)?:** https://www.ibm.com/br-pt/think/topics/identity-access-management
