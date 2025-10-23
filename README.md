# OOP-RPG-Game
RPG de texto em Java desenvolvido com orientação a objetos. Inclui classes para personagens (Guerreiro, Mago, Arqueiro) e inimigos, sistema de combate baseado em rolagem de dados, inventário com múltiplos itens, clonagem de objetos e navegação por uma história interativa.

O projeto simula batalhas entre personagens e inimigos, utiliza rolagem de dados para definir ataques e defesas, e permite o uso de itens com múltiplas unidades em um sistema de inventário dinâmico.

**Funcionalidades Principais**
Personagens Jogáveis: Guerreiro, Mago e Arqueiro.
Sistema de Combate: baseado em rolagem de dados, comparando ataque e defesa.
Inventário Inteligente: armazena múltiplas unidades de um mesmo item e evita duplicatas.
Itens Interativos: poções de cura, aumentos de ataque e defesa, entre outros.
Clonagem de Inventário: permite simular o saque de inimigos derrotados.
História e Navegação: o jogador pode explorar, lutar, usar itens ou fugir de batalhas.

**Estrutura de Classes**
Personagem (abstrata): define atributos e comportamentos base.
Guerreiro, Mago e Arqueiro: subclasses especializadas.
Inimigo: herda de Personagem, representando adversários.
Item: contém nome, descrição, efeito e quantidade.
Inventario: gerencia adição, remoção e listagem de itens.
Jogo: contém o loop principal e as interações com o jogador.

**Conceitos Aplicados**
Herança e polimorfismo
Encapsulamento
Sobrescrita de métodos (hashCode, equals, compareTo, clone)
Construtores padrão e de cópia
Estrutura de controle e manipulação de objetos

**Integrantes**
Pedro de Mello Porto Daou — RA 21010698
Yuri Cardoso Balieiro — RA 24011525
