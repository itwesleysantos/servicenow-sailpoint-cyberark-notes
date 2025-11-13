# 🔑 Autenticação Multifator (MFA)

A Autenticação Multifator (MFA) é uma disciplina de segurança cibernética que **verifica a identidade de um usuário** exigindo **pelo menos duas formas distintas de comprovação (fatores)**. O MFA adiciona camadas de proteção além da senha, que é o fator mais vulnerável e a causa mais comum de violações de dados.

O MFA faz parte essencial das estratégias de Gerenciamento de Identidade e Acesso (IAM). Mesmo que um hacker roube uma senha, ele não terá o segundo fator, que é muito mais difícil de ser comprometido.

---

## 🛠️ Tipos de Fatores de Autenticação

Para ser considerada MFA "verdadeira", a autenticação deve usar **pelo menos dois tipos diferentes** de fatores, pois isso exige métodos de ataque separados para cada evidência:

| Tipo de Fator | O que é (Exemplo) | Vulnerabilidade |
| :--- | :--- | :--- |
| **Conhecimento** | Algo que o usuário *sabe* (Senha, PIN, Resposta de segurança). | Mais vulnerável; obtido por phishing, malware ou força bruta. |
| **Posse** | Algo que o usuário *possui* (Smartphone, Token de Hardware, Chave de segurança). Gera tokens de uso único (OTP) ou exige notificação push. | Suscetível a roubo físico ou golpes como clonagem de SIM e ataques de fadiga. |
| **Inerente (Biometria)** | Algo *único ao usuário* (Impressão digital, Reconhecimento facial, Varredura de retina). | Mais difícil de decifrar, mas se comprometido, não pode ser alterado facilmente. |
| **Comportamental** | Algo que o usuário *faz* (Localização, Faixa de IP, Velocidade de digitação). | Pode ser copiado ou falsificado (ex: uso de VPN ou dispositivo confiável roubado). |

---

## 🔬 Conceitos Avançados e Diferenciação

* **MFA Adaptativa (Baseada em Risco):** Utiliza **Inteligência Artificial (IA) e Machine Learning (ML)** para avaliar o risco da tentativa de login em tempo real. Quanto mais arriscada a situação (ex: login de um local incomum), **mais fatores** o usuário deve fornecer. Isso melhora a experiência, exigindo múltiplos fatores apenas em situações confidenciais.
* **MFA Sem Senha:** Elimina o fator "Conhecimento" por ser o mais vulnerável, exigindo apenas fatores de Posse, Inerentes e Comportamentais (ex: Chaves de Acesso FIDO + Biometria).
* **MFA vs. 2FA:** A **Autenticação de Dois Fatores (2FA)** é um **subconjunto da MFA** que usa exatamente dois fatores. A MFA pode usar dois, três ou mais fatores.
* **MFA vs. SSO:** O **Logon Único (SSO)** foca na **conveniência** (usar um login para várias aplicações), enquanto o MFA foca na **segurança**. Eles são complementares, e sistemas SSO modernos geralmente exigem MFA.

---

## 🔗 Source

As informações contidas neste resumo foram compiladas a partir do artigo publicado por **Mattew Kosinski** e **Jim Holdsworth** no **IBM Think**.

* **O que é MFA (autenticação multifator)?:** https://www.ibm.com/br-pt/think/topics/multi-factor-authentication
