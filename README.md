# Encriptador de Texto

Este projeto foi desenvolvido como parte do desafio final do curso de Iniciante em Programação do Alura Challenge ONE-ORACLE. O objetivo é criar um encriptador de texto simples utilizando HTML, CSS e JavaScript, aplicando conhecimentos adquiridos ao longo do curso.

## Funcionalidades

- **Criptografia:** Transforma uma mensagem de texto em um formato encriptado usando substituições específicas para as letras `e`, `i`, `a`, `o`, e `u`.
- **Descriptografia:** Reverte o texto criptografado de volta ao seu formato original.
- **Copiar Texto:** Permite copiar o texto encriptado ou descriptografado com um clique em um botão.

## Tecnologias Utilizadas

- **HTML5:** Estrutura básica do projeto.
- **CSS3:** Estilização e layout do projeto, incluindo uso de Flexbox para posicionamento dos elementos na página.
- **JavaScript:** Implementação da lógica de criptografia e descriptografia, além de funcionalidades interativas, como o botão de copiar texto.

## Como Funciona

### Criptografia

A criptografia é realizada através de um algoritmo de substituição, onde as seguintes letras são transformadas:

- `e` → `enter`
- `i` → `imes`
- `a` → `ai`
- `o` → `ober`
- `u` → `ufat`

Por exemplo, a palavra "texto" seria criptografada como "tenterxtober".

### Descriptografia

O processo de descriptografia reverte as substituições feitas na criptografia, convertendo o texto criptografado de volta ao seu formato original. 

## Como Usar

1. Insira o texto que deseja criptografar ou descriptografar no campo de texto.
2. Clique em "Criptografar" para transformar o texto em uma mensagem codificada.
3. Clique em "Descriptografar" para reverter a mensagem criptografada para o texto original.
4. Use o botão "Copiar" para copiar o texto resultante.

## Estrutura do Projeto

- `index.html`: Contém a estrutura básica da página.
- `style.css`: Inclui as regras de estilo e layout da aplicação.
- `script.js`: Contém a lógica de criptografia e descriptografia, assim como a funcionalidade de copiar texto.

## Próximos Passos

- Melhorar a interface de usuário (UI).
- Implementar suporte para outros métodos de criptografia.
- Adicionar testes automatizados para validar a lógica de criptografia e descriptografia.

## Contribuição

Sinta-se à vontade para abrir issues ou enviar pull requests com melhorias, correções de bugs ou novas funcionalidades!

---

**Feito por Victor Rocha**
