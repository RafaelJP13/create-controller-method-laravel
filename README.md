# Laravel Make Method

Um comando Artisan personalizado para criar métodos dentro de controllers existentes no Laravel, mesmo já existindo diversas outras formas de fazer isso, essa ideia nasceu e resolvi compartilhar por que gostei.

## 💡 Sobre o projeto

O Laravel oferece diversos comandos Artisan para acelerar o desenvolvimento, como `make:controller`, `make:model` e `make:request`.

Porém, não possui um comando nativo específico para adicionar novos métodos a controllers já existentes.

O **Laravel Make Method** surgiu como uma proposta experimental para explorar essa possibilidade, permitindo criar métodos diretamente pelo terminal.

### 📚 Motivação

Este projeto começou como um exercício de estudo e aprendizado sobre a criação de comandos personalizados no Artisan e a manipulação de arquivos PHP.

A implementação inicial é propositalmente simples. Existem diversas maneiras de desenvolver essa funcionalidade, com diferentes abordagens, bibliotecas e níveis de complexidade.

A intenção não é apresentar uma solução definitiva ou substituir ferramentas existentes, mas experimentar uma ideia, entender melhor o funcionamento do Laravel e explorar possibilidades de personalização do Artisan.

## 🎯 Objetivo

Simplificar tarefas repetitivas durante o desenvolvimento Laravel, permitindo adicionar métodos a controllers existentes sem precisar editar manualmente seus arquivos.

## ⚙️ Como utilizar

### Sintaxe

```bash
php artisan make:method {controller} {method}
