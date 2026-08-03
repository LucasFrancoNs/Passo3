import os
from weasyprint import HTML

# Create clean Markdown content for the user
markdown_content = """# 🚀 Programação para Dispositivos Móveis (PPDM)
## Tópicos 01 & 02 - Conceito e Prática Flutter

Este repositório contém os **Exercícios Irineu** referentes aos Tópicos 01 & 02 da disciplina de Programação para Dispositivos Móveis. O projeto aborda os conceitos teóricos fundamentais e o desenvolvimento do **Passo 3 da Trilha Oficial do Flutter Getting Started Tutorial**.

---

## 📌 Sobre o Projeto

O objetivo principal desta atividade é compreender a arquitetura do Flutter, os tipos de Widgets e a manipulação de estados, além de implementar o guia prático oficial de construção de aplicativos.

* 📖 **Tutorial de Referência:** [Flutter Getting Started Tutorial](https://docs.flutter.dev/learn/pathway/tutorial)

### Conceitos Práticos Aplicados:
* **Construção da Árvore de Widgets:** Estruturação da interface utilizando widgets fundamentais de layout (`Scaffold`, `Row`, `Column`, `Container`).
* **Interatividade e Alteração de Estado:** Aplicação prática de `StatefulWidget` para tornar a interface reativa a ações do usuário.
* **Organização e Modularização:** Separação clara de responsabilidades e componentes reutilizáveis no projeto.

---

## 📑 Tópicos Teóricos (Respostas dos Exercícios)

### 1. Diferença de Arquiteturas (Nativo vs. Cross-Platform)
* **Desenvolvimento Nativo para Android e iOS:** É desenvolvido utilizando a linguagem e SDK específicos de cada plataforma (ex: Kotlin/Java para Android e Swift para iOS). Oferece acesso total às APIs nativas e melhor performance, mas exige a manutenção de dois códigos-fonte distintos.
* **Cross-Platform ou Híbrido (exemplo Flutter):** Permite escrever um único código-fonte no Dart, que é compilado para rodar tanto no Android quanto no iOS. O Flutter se destaca por não usar pontes ou componentes nativos de UI, mas sim um mecanismo próprio de renderização, garantindo alta performance com uma única base de código.

### 2. Ciclo de Vida e Widgets (StatelessWidget x StatefulWidget)
No Flutter, "tudo é um Widget". A principal diferença entre eles é o gerenciamento de dados que mudam com o tempo:
* **StatelessWidget:** É um widget imutável. Sua interface é desenhada uma única vez e não altera seu estado internamente após ser construída.
  * *Exemplo de uso:* Uma tela de "Sobre o App", um título de texto ou um ícone estático.
* **StatefulWidget:** É um widget mutável. Ele possui um objeto de estado (`State`) associado que pode ser alterado durante o ciclo de vida do aplicativo em resposta a ações do usuário ou dados externos.
  * *Exemplo de uso:* Um botão de "Curtir" (que muda de cor e incrementa o contador) ou um formulário de login.

### 3. setState() - Gerenciamento de Estado
Quando o método `setState()` é chamado dentro de um `StatefulWidget`, ele notifica a estrutura do Flutter de que o estado interno do widget mudou. Isso faz com que o Flutter agende uma nova execução do método `build()` daquele widget, atualizando e redesenhando a interface gráfica na tela para refletir os novos dados.

---

## ⚙️ Como Executar o Projeto

### Pré-requisitos
* [Flutter SDK](https://docs.flutter.dev/get-started/install) instalado.
* Editor de código (VS Code, Android Studio ou GitHub Codespaces).
* Emulador Android/iOS, navegador Web ou dispositivo físico conectado.

### Passo a Passo

1. **Clonar este repositório:**
   ```bash
   git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)
