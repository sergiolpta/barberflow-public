# BarberFlow

**Plataforma moderna de gestão para barbearias**, focada em organização, automação e escalabilidade.

O BarberFlow foi desenvolvido para centralizar as principais operações de uma barbearia em um único sistema, reduzindo trabalho manual, erros operacionais e dependência de múltiplas ferramentas desconectadas.

---

## 🧠 Visão do Produto

Barbearias modernas precisam de mais do que uma agenda online.  
Elas precisam de **controle**, **visibilidade** e **processos claros**.

O BarberFlow nasce com essa proposta:  
> organizar o negócio antes de tentar escalá-lo.

A plataforma foi pensada desde o início para suportar crescimento, múltiplos profissionais, diferentes serviços e integrações futuras com sistemas externos.

---

## 🚀 Principais Capacidades

- 📅 **Agendamento inteligente**
- 👥 **Gestão de profissionais**
- ✂️ **Serviços e pacotes configuráveis**
- 🏪 **Estrutura multi-barbearia (multi-tenant)**
- 🔐 **Autenticação e controle de acesso**
- ⚙️ **API REST pronta para integrações**
- 🤖 **Automação de processos (via n8n)**

---

## 🧩 Arquitetura (Visão Geral)

O BarberFlow utiliza uma arquitetura moderna, modular e orientada a serviços.

- **Backend**: Node.js + Express  
- **Banco de Dados**: PostgreSQL (Supabase)  
- **Infraestrutura**: Docker + Traefik  
- **Automação**: n8n  
- **Deploy**: VPS com proxy reverso e isolamento por containers  

Essa abordagem garante:
- Facilidade de manutenção
- Isolamento de responsabilidades
- Evolução sem reescrever o sistema

---

## 🔐 Segurança e Boas Práticas

- Uso de variáveis de ambiente
- Separação clara entre ambientes (local / produção)
- Tokens e credenciais nunca versionados
- Controle de acesso por contexto (barbearia)

O repositório público **não contém dados sensíveis**.

---

## 📈 Escalabilidade

O projeto foi construído para crescer de forma controlada:

- Novas barbearias sem duplicar código
- Integração futura com pagamentos, relatórios e BI
- Possibilidade de novos frontends consumindo a mesma API
- Automatizações personalizadas por negócio

---

## 🧑‍💼 Público-Alvo

- Barbearias que desejam profissionalizar a gestão
- Estúdios que operam com múltiplos profissionais
- Negócios que precisam de controle operacional real
- Projetos que exigem integração com sistemas externos

---

## 📄 Material Institucional

Uma apresentação executiva com visão de produto, arquitetura e proposta de valor está disponível em formato PDF.

📄 **BarberFlow — Apresentação Executiva**

---

## 📌 Status do Projeto

O BarberFlow encontra-se em **fase funcional**, com backend estável, infraestrutura validada e fluxos reais de operação já testados.

Evoluções futuras incluem:
- Expansão do módulo financeiro
- Dashboards gerenciais
- Integração com pagamentos
- Relatórios avançados

---

## 📬 Contato

Para demonstrações, parcerias ou informações adicionais:

**Sérgio Braz**  
Projeto BarberFlow
