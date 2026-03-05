# 🎈 Jogo - Estoure o balão: Estudo sobre manipulação JS/HTML/CSS
### Estudo de Interatividade Real-time e Lógica de Jogos com JavaScript Puro

Este projeto é um laboratório prático focado em entender como o JavaScript interage com o HTML em cenários de alta dinamicidade. [cite_start]O objetivo foi explorar a manipulação de elementos em tempo real, animações fluidas e o comportamento do motor do JS ao lidar com múltiplos eventos simultâneos[cite: 365, 383].

---

## 🎯 Objetivos do Estudo
* [cite_start]**DOM em Movimento**: Entender o comportamento do navegador ao renderizar, mover e remover elementos dinamicamente[cite: 345].
* **Lógica de Game Loop**: Implementação de sistemas de dificuldade progressiva baseados em gatilhos de pontuação.
* **Event Handling**: Captura e processamento de interações do usuário em elementos gerados de forma assíncrona.

## 🛠️ O que foi explorado
* **Animações e Movimentação**: Controle de CSS e transições via JS para simular o movimento de subida dos balões.
* **Gerenciamento de Estado Simples**: Controle de score e níveis de dificuldade para ditar a velocidade e o spawn de novos objetos.
* [cite_start]**Integração com Laravel**: O projeto utiliza o Laravel como estrutura base para servir a aplicação e organizar os assets de forma profissional[cite: 336].

## 🧠 Desafios Técnicos Resolvidos
1. [cite_start]**Ciclo de Vida de Elementos**: Garanti que cada balão estourado (ou que saísse da tela) fosse corretamente removido do DOM para evitar memory leaks[cite: 342].
2. **Esconamento de Dificuldade**: Criação de uma lógica onde a velocidade e a frequência aumentam a cada **X estouros**, testando a performance da renderização sob carga.

---

## 🚀 Como testar
1. Clone o repositório.
2. [cite_start]Execute `composer install` para configurar a base do Laravel[cite: 336].
3. `php artisan serve`.
4. Estoure o máximo de balões que conseguir e veja a dificuldade subir!

---
<p align="center">
  Feito por <b>André Araújo Silva</b>.
</p>
