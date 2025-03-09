# Introdução ao Java

## Sumário

- [1. Introdução ao Java](#1-introdução-ao-java)
- [2. Estrutura Básica de um Programa Java](#2-estrutura-básica-de-um-programa-java)
- [3. Plataforma Java](#3-plataforma-java)
- [4. Conceitos de Orientação a Objetos](#4-conceitos-de-orientação-a-objetos)
  - [Objeto](#objeto)
  - [Classe](#classe)
  - [Abstração, Encapsulamento e Polimorfismo](#abstração-encapsulamento-e-polimorfismo)
- [5. Exemplo Prático](#5-exemplo-prático)
- [6. Resumo de Conceitos](#6-resumo-de-conceitos)

<p align="center">
  <img src="https://cdn.thedevconf.com.br/photos/James+gosling.png" width="300">
</p>

## 1. Introdução ao Java
O Java é uma linguagem de programação que opera na Java Virtual Machine (JVM), que converte bytecode em instruções compreensíveis pelo sistema operacional. O conceito "Write Once, Run Anywhere" permite que programas Java sejam escritos uma única vez e executados em diferentes plataformas, garantindo portabilidade.

## 2. Estrutura Básica de um Programa Java
Um programa em Java é formado por classes e métodos, sendo as classes a principal unidade de encapsulamento. Elas podem conter variáveis de instância e métodos que definem o comportamento dos objetos criados.

## 3. Plataforma Java
O Java é suportado por um compilador e uma máquina virtual que funcionam em diversos sistemas operacionais.

| Tecnologia | Descrição |
|------------|---------------------------------|
| Java SE   | Plataforma Java Standard Edition |
| Java EE   | Plataforma Java Enterprise Edition |
| Spring    | Framework para desenvolvimento web |


## 4. Conceitos de Orientação a Objetos

### Objeto
Unidade básica de orientação a objetos com atributos e comportamento.

### Classe
Descrição de um conjunto de objetos que compartilham atributos e comportamento em comum.

### Abstração, Encapsulamento e Polimorfismo
Conceitos fundamentais da programação orientada a objetos, onde:
- **Abstração** simplifica a representação de objetos complexos.
- **Encapsulamento** esconde questões internas de implementação.
- **Polimorfismo** permite que diferentes classes implementem métodos comuns de maneiras diversas.

## 5. Exemplo Prático
A aplicação prática é demonstrada com um sistema de pagamento onde uma classe base `Pagamento` é criada, permitindo a implementação de diferentes formas de pagamento sem modificar o código principal.
```java
abstract class Pagamento {
    abstract void processarPagamento();
}

class Cartao extends Pagamento {
    @Override
    void processarPagamento() {
        System.out.println("Pagamento via cartão processado.");
    }
}

class Pix extends Pagamento {
    @Override
    void processarPagamento() {
        System.out.println("Pagamento via Pix processado.");
    }
}
```

## 6. Resumo de Conceitos

- **Método**: Operações executadas sobre objetos.
- **Estado**: Valores atuais dos atributos de um objeto, resultado de seu comportamento ao longo do tempo.
- **Atributo**: Usado para armazenar o estado de um objeto.

Este resumo sintetiza os princípios básicos da programação em Java e a estrutura da programação orientada a objetos, fundamentais para o aprendizado e aplicação da linguagem.

Próximas etapas, código Java:
```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Olá, Mundo!");
    }
}
```

### 📌 Tarefas Pendentes  
- [x] Criar README  
- [x] Adicionar Sumário  
- [ ] Implementar novos recursos  
- [ ] Melhorar documentação
- [ ] Acrescentar Filas, Pilhas e Deques 

## Conecte-se comigo

<div align="center">
  <a href="https://www.youtube.com/c/marcelojtelles" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/42/YouTube_icon_%282013-2017%29.png" alt="YouTube" width="40" style="margin: 0 15px;"/>
  </a>
  <a href="https://github.com/Macelot" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Octicons-mark-github.svg/1024px-Octicons-mark-github.svg.png" alt="GitHub" width="40" style="margin: 0 15px;"/>
  </a>
  <a href="https://www.instagram.com/marcelojtelles/" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram" width="40" style="margin: 0 15px;"/>
  </a>
</div>

