# Desafio de Projeto: Abstraindo um Celular com POO em .NET

Este projeto foi desenvolvido como parte do desafio de Programação Orientada a Objetos (POO) da trilha .NET da [Digital Innovation One (DIO)](https://www.dio.me/).

O objetivo principal foi aplicar os pilares da POO (Abstração, Encapsulamento, Herança e Polimorfismo) para criar um sistema que modela o comportamento de diferentes smartphones.

## 🚀 Tecnologias Utilizadas
*   **C#**: Linguagem de programação principal.
*   **.NET**: Plataforma de desenvolvimento.

## 💻 Sobre o Projeto

A aplicação simula a representação de dois modelos de celular, um Nokia e um iPhone, a partir de uma classe abstrata `Smartphone`.

### Estrutura das Classes

*   `Smartphone` (Classe Abstrata):
    *   Serve como modelo base para todos os celulares.
    *   Contém propriedades comuns como `Numero`, `Modelo`, `IMEI` e `Memoria`.
    *   Possui métodos concretos como `Ligar()` e `ReceberLigacao()`.
    *   Define um método abstrato `InstalarAplicativo(string nomeApp)`, que deve ser implementado pelas classes filhas.

*   `Nokia` e `Iphone` (Classes Concretas):
    *   Heram da classe `Smartphone`.
    *   Implementam (sobrescrevem) o método `InstalarAplicativo(string nomeApp)` com um comportamento específico para cada marca, demonstrando o polimorfismo.

O diagrama de classes que guiou o desenvolvimento foi o seguinte:

!Diagrama de Classes

## ▶️ Como Executar

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/Rs134-sa/trilha-net-poo-desafio.git
    ```

2.  **Navegue até o diretório do projeto:**
    ```bash
    cd trilha-net-poo-desafio
    ```

3.  **Execute a aplicação:**
    ```bash
    dotnet run
    ```

## ✨ Agradecimentos

Agradeço à DIO pela oportunidade de aprendizado e pelo desafio proposto, que foi fundamental para consolidar os conhecimentos em Programação Orientada a Objetos com .NET.


## 👨‍💻 Autoria

Feito por [Raiane de Sá](https://github.com/Raiane-S) - Conecte-se comigo no [LinkedIn](https://www.linkedin.com/in/raiane-s/)!
