# OOP-RPG-Game

RPG de texto em Java desenvolvido com **orientação a objetos**, oferecendo uma experiência interativa de combate, exploração e gerenciamento de inventário. O jogo permite ao jogador escolher entre **Guerreiro, Mago e Arqueiro**, enfrentar inimigos e navegar por uma história dinâmica.

## Funcionalidades Principais

* **Personagens Jogáveis:** Guerreiro, Mago e Arqueiro, cada um com habilidades únicas.
* **Sistema de Combate:** baseado em rolagem de dados, determinando ataques, defesas e efeitos de habilidades.
* **Inventário Inteligente:** armazena múltiplas unidades de um mesmo item, evitando duplicatas.
* **Itens Interativos:** poções de cura, aumentos de ataque e defesa, entre outros efeitos estratégicos.
* **Clonagem de Inventário:** permite simular saques de inimigos derrotados.
* **História e Exploração:** o jogador pode lutar, usar itens ou fugir de batalhas, explorando diferentes caminhos da narrativa.

## Estrutura de Classes

* **Personagem (abstrata):** define atributos e comportamentos base.
* **Guerreiro, Mago e Arqueiro:** subclasses especializadas com habilidades próprias.
* **Inimigo:** herda de `Personagem`, representando adversários.
* **Item:** contém nome, descrição, efeito e quantidade.
* **Inventario:** gerencia adição, remoção e listagem de itens.
* **Jogo:** responsável pelo loop principal e interações com o jogador.

## Conceitos de Programação Aplicados

* Herança e polimorfismo
* Encapsulamento
* Sobrescrita de métodos (`hashCode`, `equals`, `compareTo`, `clone`)
* Construtores padrão e de cópia
* Estruturas de controle e manipulação avançada de objetos

## Integrantes

* Pedro de Mello Porto Daou — RA 21010698
* Yuri Cardoso Balieiro — RA 24011525
