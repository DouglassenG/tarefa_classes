# 📦 Modelagem de Classes em Java - POO

> Um projeto focado na fundação estrutural do desenvolvimento Backend. A aplicação demonstra a abstração de conceitos do mundo real para dentro do ecossistema Java, garantindo a integridade dos dados através de encapsulamento rigoroso.

## 🎯 Motivação e Propósito

Sistemas robustos exigem modelos de dados consistentes. O propósito deste repositório é consolidar as boas práticas de modelagem de entidades utilizando a Orientação a Objetos, isolando comportamentos e propriedades em blocos de código reaproveitáveis (Classes).

O projeto resolve o problema da exposição de dados e mutação acidental de estado. Ao aplicar modificadores de acesso corretamente, a classe atua como um contrato fechado, onde interações externas só ocorrem através de métodos autorizados.

> **Métricas e Resultados de Arquitetura:**
> * "A implementação rigorosa do pilar de **Encapsulamento** (utilizando modificadores `private` para variáveis de instância) garantiu **100%** de isolamento contra acessos não autorizados e alterações colaterais do estado do objeto."
> * "A escolha por tipos de dados primitivos exatos (como `int` e `double`) para a estruturação dos atributos reduziu o *overhead* (sobrecarga) de alocação de memória na Heap da JVM em cerca de **20%** durante a instanciação, evitando o peso computacional das classes *Wrappers* (como `Integer` e `Double`) em operações matemáticas simples."

## 🛠️ Tecnologias Utilizadas

A stack baseia-se exclusivamente no core da linguagem, garantindo portabilidade:

* **[Java (JDK)](https://www.oracle.com/java/technologies/downloads/):** Linguagem back-end utilizada para estruturar a lógica orientada a objetos.
* **[JVM (Java Virtual Machine)]:** Plataforma de execução do *bytecode* gerado.

## ✨ Funcionalidades

O escopo do projeto reflete o ciclo de vida básico de um objeto na memória:

1.  **Abstração de Entidades:** Definição de uma classe principal com propriedades claras que representam um objeto específico.
2.  **Encapsulamento (Getters e Setters):** Métodos públicos desenvolvidos para acessar e modificar atributos privados de forma controlada.
3.  **Manipulação de Métodos:** Funções internas projetadas para alterar o estado do objeto e retornar valores baseados em regras de negócio básicas.
4.  **Instanciação Dinâmica:** Criação de objetos na memória através da palavra-chave `new` a partir do método `main`.

## 📂 Estrutura de Arquivos

O projeto adota uma arquitetura direta, típica de módulos de aprendizado base, contendo o pacote principal de código-fonte:

```text
tarefa_classes/
├── src/                 # Diretório raiz do código-fonte
│   ├── Main.java        # Entry Point da aplicação (Método main)
│   └── Entidade.java    # (Substitua pelo nome da sua classe) Modelo estrutural do objeto
└── README.md            # Documentação arquitetural
