# 📐 Explorando a Função Quadrática

[![Licença](https://img.shields.io/badge/license-MIT-green)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Flask-3.0%2B-lightgrey)](https://flask.palletsprojects.com/)
[![Render Deployment](https://img.shields.io/badge/Render-Live-brightgreen)](https://matematica-quadratica.onrender.com)

Um simulador interativo desenvolvido como projeto multidisciplinar focado em solucionar dificuldades no aprendizado de matemática abstrata no Ensino Médio. A aplicação permite que alunos e professores manipulem os coeficientes de uma função de segundo grau e visualizem o comportamento da parábola em tempo real no navegador.

🚀 **Link para acesso rápido:** [matematica-quadratica.onrender.com](https://matematica-quadratica.onrender.com)

---

## 🎯 Contexto e Objetivo

Este projeto foi desenhado sob medida para atender a uma demanda real de ensino, servindo como ferramenta pedagógica de apoio para turmas de Ensino Médio (como na E. E. Pastor Alberto Augusto), onde o ensino de álgebra frequentemente esbarra na falta de recursos visuais dinâmicos.

Com este simulador, o aluno pode:
*   Alterar o coeficiente **a** e observar a mudança de concavidade e abertura da parábola.
*   Modificar os coeficientes **b** e **c** para entender deslocamentos nos eixos coordenados.
*   Romper a barreira da abstraction teórica por meio da experimentação prática.

---

## 🛠️ Tecnologias Utilizadas

A aplicação utiliza uma arquitetura **Cliente-Servidor (Full Stack)** simples e extremamente performática:

*   **Backend:** Python com o micro-framework **Flask** para roteamento e gerenciamento da aplicação.
*   **Frontend:** HTML5 estruturado e JavaScript para calcular os pontos da equação $f(x) = ax^2 + bx + c$ de forma instantânea diretamente no navegador do usuário.
*   **Deploy / Hospedagem:** **Render** (conectado via pipeline contínua a este repositório).

---

🚀 Como Rodar o Projeto Localmente

Se quiser clonar e executar este projeto na sua máquina:

    Clone o repositório:
    
   git clone [https://github.com/larissa-nicanor/matematica-quadratica.git](https://github.com/larissa-nicanor/matematica-quadratica.git)
   cd matematica-quadratica

    Instale as dependências:

   pip install -r requirements.txt

    Execute a aplicação:

   python app.py
   
    Acesse no navegador:
    
   http://127.0.0.1:5000

📱 Validação em Ambiente Real

A aplicação foi validada com sucesso em ambiente externo, recebendo acessos simultâneos de usuários através de desktops e dispositivos móveis (redes 4G/Wi-Fi), cumprindo perfeitamente os requisitos de portabilidade para atividades extraclasse e tarefas de casa.

## 📁 Estrutura do Projeto

```text
├── templates/
│   └── index.html      # Interface gráfica e lógica de renderização do gráfico
├── app.py              # Servidor backend Flask e mapeamento de rotas
├── Procfile            # Instruções de inicialização para o ambiente de produção (Gunicorn)
├── requirements.txt    # Dependências do projeto (Flask, etc.)
└── README.md           # Documentação do repositório

##Desenvolvido como parte do Projeto Multidisciplinar III
