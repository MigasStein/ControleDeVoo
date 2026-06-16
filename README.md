# Controle De Voo

#  Simulador de Torre de Comando Aéreo

Um sistema de simulação de terminal para controle de tráfego aéreo desenvolvido em Java. O projeto simula a interação entre uma torre de controle e múltiplas aeronaves, validando permissões de voo, pouso e decolagem em tempo real.

O principal objetivo deste repositório é demonstrar a aplicação prática dos conceitos fundamentais da **Programação Orientada a Objetos (POO)** de forma limpa e legível.

---

##  Conceitos de POO Aplicados

* **Abstração & Encapsulamento:** A classe `Aviao` esconde seu estado interno (`status`) usando o modificador `private`. Mudanças de estado só podem ser solicitadas através de métodos específicos, impedindo alterações inconsistentes por fora da classe.
* **Associação de Objetos:** A classe `TorreComando` interage diretamente com uma coleção dinâmica (`List<Aviao>`) de objetos do tipo `Aviao`, demonstrando como entidades distintas se comunicam em um sistema.
* **Responsabilidade Única:** Cada classe possui um papel bem definido. O avião gerencia suas próprias informações, enquanto a torre gerencia a coordenação e as regras de tráfego.

---

##  Estrutura do Projeto

O código está organizado em três arquivos principais:

1. `Aviao.java`: Define os atributos da aeronave (código, companhia e status) e seus comportamentos individuais.
2. `TorreComando.java`: Centraliza a lógica de controle de tráfego e interações com os aviões.
3. `Main.java`: Ponto de entrada (`main`) que inicializa os objetos e executa o cenário de simulação.

---
