# Robô Seguidor de Linha (3 Rodas - Motores 5V)

## 📌 Sobre o Projeto
Este repositório contém a documentação e os detalhes de construção de um **Robô Seguidor de Linha** autônomo, projetado para identificar e seguir trajetórias marcadas no chão utilizando sensores ópticos. 

O projeto foi desenvolvido para demonstrar a aplicação prática de eletrônica básica, programação de microcontroladores e mecânica robótica.

---

## ⚙️ Especificações e Componentes

### **Estrutura Mecânica:**
* **Chassi:** Triciclo (3 rodas) com tração diferencial de duas rodas principais e uma roda boba (*caster wheel*) para estabilidade e giros suaves.

### **Componentes Eletrônicos:**
* **Motores:** 2x Motores DC com caixa de redução (Operação em 5V).
* **Sensores:** Sensores infravermelhos (TCRT5000) para leitura e detecção da linha de contraste.
* **Atuador/Driver:** Ponte H (L298N ou equivalente) para controle de direção e velocidade dos motores.
* **Controlador:** Placa microcontroladora (Arduino / microcontrolador compatível).
* **Alimentação:** Banco de baterias com regulador para entrega de 5V estáveis aos motores e lógica.

---

## 🎯 Funcionamento do Sistema
1. **Leitura:** Os sensores infravermelhos emitem luz e medem a reflexão na superfície.
2. **Processamento:** O microcontrolador analisa a diferença de refletância entre a superfície clara e a linha escura.
3. **Ação:** O algoritmo ajusta a velocidade individual de cada motor 5V via PWM, permitindo corrigir a trajetória e fazer curvas automaticamente.

---

## 📂 Estrutura do Repositório
* `/src` — Código-fonte do firmware gravado no robô.
* `/docs` — Esquema de ligação dos pinos e componentes.

---

## 👤 Autor
Projeto desenvolvido por mim como demonstração de aplicação prática em engenharia/eletrônica.
