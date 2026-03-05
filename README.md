# 🎈 Jogo - Estoure o Balão
### Estudo de Interatividade Real-time sobre manipulação JS/HTML/CSS e ecossistema Laravel

<p align="left">
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>

---

## 📝 Sobre o Projeto
Este projeto é um laboratório prático focado em entender como o JavaScript interage com o HTML em cenários de alta dinamicidade. O objetivo foi explorar a manipulação de elementos em tempo real, animações fluidas e o comportamento do motor do JS ao lidar com múltiplos eventos simultâneos.

---

## 🎯 Objetivos do Estudo
* **DOM em Movimento**: Entender o comportamento do navegador ao renderizar, mover e remover elementos dinamicamente.
* **Lógica de Game Loop**: Implementação de sistemas de dificuldade progressiva baseados em gatilhos de pontuação.
* **Event Handling**: Captura e processamento de interações do usuário em elementos gerados de forma assíncrona.

## 🛠️ O que foi explorado
* **Animações e Movimentação**: Controle de CSS e transições via JS para simular o movimento de subida dos balões.
* **Gerenciamento de Estado Simples**: Controle de score e níveis de dificuldade para ditar a velocidade e o spawn de novos objetos.
* **Integração com Laravel**: O projeto utiliza o Laravel como estrutura base para servir a aplicação e organizar os assets de forma profissional.

## 🧠 Desafios Técnicos Resolvidos
1. **Ciclo de Vida de Elementos**: Garantia de que cada balão estourado (ou que saísse da tela) fosse corretamente removido do DOM para evitar memory leaks.
2. **Escalonamento de Dificuldade**: Criação de uma lógica onde a velocidade e a frequência aumentam a cada **X estouros**, testando a performance da renderização sob carga.

---

## 🚀 Como testar
1. Clone o repositório.
2. Execute `composer install` para configurar a base do Laravel.
3. `php artisan serve`.
4. Estoure o máximo de balões que conseguir e veja a dificuldade subir!

---
<p align="center">
  Desenvolvido por <b>André Araújo Silva</b>.
</p>
