# 🚀 Flutter Getting Started - Passo 3: Estado em Aplicativos Flutter

Este repositório contém o projeto prático desenvolvido como parte da trilha oficial de aprendizado do **Flutter**. O objetivo desta atividade foi colocar em prática os conceitos fundamentais de construção de interfaces, gerenciamento de estado e organização de componentes no Flutter.

---

## 📌 Sobre o Projeto

O projeto consiste na implementação prática do **Passo 3 da Trilha Oficial de Getting Started do Flutter**, focando em transformar telas estáticas em interfaces dinâmicas e reativas através do uso de estado.

* 📖 **Tutorial de Referência:** [Flutter Getting Started Tutorial](https://docs.flutter.dev/learn/pathway/tutorial)

---

## 🛠️ Conceitos Aplicados

Durante o desenvolvimento deste projeto, foram trabalhados os seguintes pontos chave:

* **Construção da Árvore de Widgets:** Estruturação da interface utilizando widgets fundamentais de layout como `Scaffold`, `Row`, `Column` e `Container`.
* **Interatividade e Estado:** Aplicação de `StatefulWidget` e manipulação do método `setState()` para redefinir a interface em tempo de execução conforme as interações do usuário.
* **Organização e Modularização:** Separação limpa do código em componentes reutilizáveis, aplicando boas práticas de arquitetura em Flutter.

---

## 📑 Respostas Teóricas

### 1. Diferença de Arquiteturas: Nativo vs. Cross-Platform (Flutter)
A principal diferença de arquitetura entre o desenvolvimento nativo e o cross-platform está na forma como o código interage com o sistema operacional e na quantidade de bases de código mantidas. No desenvolvimento nativo para Android ou iOS, criam-se dois aplicativos completamente independentes em linguagens específicas que conversam diretamente com as APIs e componentes visuais de cada sistema, enquanto no modelo cross-platform com o Flutter, utiliza-se uma única base de código em Dart capaz de desenhar a interface inteira na tela por meio de um motor gráfico próprio, garantindo o mesmo comportamento e visual em ambas as plataformas sem a necessidade de duplicar o trabalho de desenvolvimento.

### 2. Ciclo de Vida e Widgets: StatelessWidget vs. StatefulWidget
A diferença entre um StatelessWidget e um StatefulWidget reside na capacidade do componente de alterar visualmente seus dados internos ao longo do tempo. O StatelessWidget é totalmente imutável e ideal para partes estáticas da interface que não sofrem alterações após serem desenhadas, como um texto explicativo ou uma logo, enquanto o StatefulWidget mantém um objeto de estado associado que permite redefinir informações na tela em resposta a interações do usuário, sendo a escolha adequada para componentes dinâmicos, como um campo de texto de formulário ou uma chave de ligar e desligar.

### 3. Gerenciamento de Estado: O uso do setState()
Ao executar o método setState dentro de um StatefulWidget, o Flutter atualiza os valores das variáveis internas contidas no seu bloco de código e notifica o framework de que o estado daquele componente mudou. Isso faz com que o Flutter invoque novamente o método build do widget, comparando a nova estrutura de interface com a anterior para redesenhar na tela apenas os elementos afetados pela alteração de dados, refletindo a nova informação para o usuário de forma praticamente instantânea.

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos
* [Flutter SDK](https://docs.flutter.dev/get-started/install) instalado.
* Editor de código (VS Code ou Android Studio).
* Emulador Android/iOS ou dispositivo físico conectado.


