# 🚗 STATIOZENO — Sistema de Gestão de Estacionamento e Controle de Acessos

> **Protótipo de Alta Fidelidade** para o sistema de gerenciamento de vagas, validação de acessos de veículos, cadastro de motoristas e módulo de RH/Funcionários.

---

## 📌 Sobre o Projeto

O **STATIOZENO** é uma solução para controle, monitoramento e automação do fluxo de entrada/saída de veículos e cadastro de clientes e funcionários em estacionamentos corporativos e comerciais. 

Este repositório contém a documentação e as telas do **Protótipo de Alta Fidelidade**, cobrindo o fluxo do usuário (Cliente), o portal do Funcionário e as funcionalidades administrativas do Gerente.

---

## 🖥️ Módulos e Interface (Telas do Protótipo)

### 🔑 1. Autenticação e Entrada
* **Boas-vindas / Seleção de Perfil:** Escolha de acesso entre **Cliente** e **Funcionário**.
* **Login de Funcionários:** Tela de autenticação com dados de `Nome`, `Senha`, `Telefone`, `E-mail` e `RG`.

### 🚘 2. Portal do Motorista / Cliente
* **Cadastro de Clientes:** Registro rápido de `Nome`, `Placa`, `Telefone`, `E-mail` e `RG`.
* **Ficha do Motorista & Veículos:**
  * **Dados do Motorista:** Exibição de Nome Completo, CPF, CNH, Telefone e Status de Cadastro (Ex: *ATIVO*).
  * **Veículos Registrados:** Vínculo de placa, modelo/cor (ex: *Toyota Corolla, Prata*), fabricante e ano.
  * **Informações de Acesso:** Status de Acesso (*AUTORIZADO*), Destino Frequente (*Bloco B, Escritório Central*) e observações de restrição.

### 👥 3. Módulo de RH & Cadastro de Funcionários
* **Ficha de Cadastro de Funcionários:**
  * **Dados Pessoais:** Nome, Data de Nascimento, CPF, RG, Endereço, Telefone e E-mail.
  * **Dados Profissionais:** Cargo (Ex: *Analista de Sistemas Pleno*), Departamento (*Tecnologia da Informação*), Data de Admissão, CTPS, PIS e Horário de Trabalho.
  * **Informações Adicionais:** Grau de Instrução e Estado Civil.
  * **Status do Cadastro:** Acompanhamento do status atual (Ex: *ATIVO PENDENTE DE ASSINATURA FINAL*).

### 🛡️ 4. Painel do Gerente (Análise e Validação de Acessos)
* **Relatório de Validação de Acessos:**
  * **Dados de Operação:** Identificação do operador responsável (Ex: *André Almeida - ID: 001*), Ponto de Validação (*Guarita Central - Portão 2*) e Registro de Data/Hora.
  * **Validação em Tempo Real:** Conferência do ticket do motorista (Ex: `#STZ1001`), leitura da placa do veículo e status do pagamento (*Pagamento Confirmado*).
  * **Liberação de Portaria:** Ação de gerenciamento com liberação automática via ticket.

---

## 🎨 Principais Funcionalidades Modeladas

1. **Gestão de Vagas e Análise:** Monitoramento do fluxo de vagas em tempo real.
2. **Controle de Portaria & Guarita:** Liberação rápida por conferência de ticket e placa registrada.
3. **Multi-Perfil:** Telas distintas adaptadas às necessidades do Cliente, Funcionário da Operação e Gerente/Administrador.
4. **Registro Completo de Frota:** Associação de múltiplos veículos por motorista.

---

## 📅 Informações do Projeto

* **Ano de Desenvolvimento:** 2026
* **Tipo de Artefato:** Protótipo de Alta Fidelidade (UX/UI Design)
* **Status:** Concluído
