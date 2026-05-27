# DONZELLAS PAY CALC

Sistema financeiro premium para cálculo de operações de maquininha, antecipação e controle operacional da Donzellas Pay.

---

## 📌 Sobre o Projeto

O **Donzellas Pay Calc** é um sistema desenvolvido para automatizar cálculos financeiros de operações com cartão, permitindo:

* cálculo reverso de taxas
* cálculo automático do valor bruto da maquininha
* margem operacional configurada
* conferência de parcelas
* dashboard financeiro
* histórico operacional
* simulador rápido
* exportação CSV
* relatórios operacionais

O sistema foi criado inicialmente como um aplicativo local em HTML + CSS + JavaScript puro, com foco em:

* velocidade
* simplicidade
* operação offline
* futura migração para nuvem

---

# ✨ Funcionalidades

## 🔐 Login Operacional

* autenticação local
* níveis de acesso
* avatar automático
* controle de sessão

---

## 📊 Dashboard Financeiro

* total movimentado
* lucro estimado
* taxa média
* operações do dia
* gráficos em tempo real
* últimas operações

---

## 💳 Nova Operação

* cadastro completo do cliente
* CPF e telefone
* bandeira e modalidade
* cálculo automático
* margem Donzellas integrada
* valor bruto da maquininha
* antecipação
* recebível futuro
* cópia rápida para WhatsApp

---

## ⚡ Simulador Rápido

* simulação instantânea
* sem salvar no histórico
* geração de comprovante
* resumo operacional

---

## 🧾 Histórico

* filtros avançados
* exportação CSV
* exclusão com confirmação
* persistência local

---

## 📈 Tabela de Taxas

* débito
* crédito à vista
* parcelado até 18x
* diferenciação entre:

  * Mastercard/Visa
  * Elo/Hipercard/Demais

---

## 📲 Conferência de Parcelas

* cálculo exato das parcelas
* comparação com valor informado pelo cliente
* validação operacional
* conferência visual

---

# 🧠 Lógica Financeira

O sistema trabalha com:

```javascript id="1"
valor bruto → desconto adquirente → margem Donzellas → valor líquido
```

A lógica principal calcula automaticamente:

```javascript id="2"
valorBruto = valorAposAdq / (1 - taxaAdq / 100)
```

Permitindo que o operador informe apenas:

```text id="3"
quanto o cliente deseja receber
```

E o sistema calcula automaticamente:

* valor da maquininha
* taxas
* lucro
* desconto
* parcela
* antecipação

---

# 🎨 Design

Tema:

* preto premium
* dourado fintech
* azul escuro corporativo

Características:

* responsivo
* mobile ready
* interface moderna
* UX premium
* animações suaves

---

# 🛠️ Tecnologias Utilizadas

* HTML5
* CSS3
* JavaScript Vanilla
* Chart.js
* Font Awesome
* LocalStorage

---

# 📂 Estrutura Recomendada

```text id="4"
DonzellasPay/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── app.js
├── assets/
├── backups/
└── README.md
```

---

# 🚀 Como Executar

## Método recomendado

Instale:

* Visual Studio Code
* extensão Live Server

Depois:

```text id="5"
Clique com botão direito em index.html
→ Open with Live Server
```

O sistema abrirá em:

```text id="6"
http://127.0.0.1:5500
```

---

# ☁️ Publicação Online

O sistema pode ser publicado gratuitamente em:

* GitHub Pages
* Vercel
* Netlify

---

# 🔒 Segurança

Atualmente o sistema utiliza:

* autenticação local
* armazenamento via localStorage

⚠️ Recomendado para:

* operação interna
* testes
* MVP

---

# 🔮 Próximas Evoluções

## Backend

* Supabase
* Firebase
* PostgreSQL

## Recursos futuros

* login real
* multiusuário
* backup em nuvem
* integração WhatsApp
* emissão PDF
* assinatura digital
* logs operacionais
* auditoria
* painel administrativo
* anti-fraude

---

# 📌 Observações

Este projeto foi desenvolvido como estrutura inicial para operação financeira e poderá evoluir para:

* sistema fintech
* ERP financeiro
* plataforma de antecipação
* sistema de cash-out
* controle operacional completo

---

# 👨‍💻 Desenvolvido por

**Donzellas Pay**

*"Liquidez inteligente com controle total."*
