# Entrega de Exercícios do GA!
### Lista feita para a disciplina de Fundamentos de Computação Gráfica

## 🤖 Lista 1 - Programação
Exercicios 7 e 8 estão listados juntos com os 6 e 9, feitos em aula.

Exercicios teóricos estão respondidos um pouco mais abaixo deste texto
## Build

No terminal rode o comando
```bash
  cmake -- build build
```
Ou se preferir entre direto na pasta build como a seguir:
```bash
  cd build
```
Execute o build direto nesta pasta
```bash
  cmake --build .
```
Para executar os códigos entre na pasta build com o código do item 2) e execute a linha abaixo:

```bash
  .\Ex@@
```
## Teoria

- Exercicio 1 - O que é a GLSL? Quais os dois tipos de shaders são obrigatórios no pipeline programável da versão atual que trabalhamos em aula e o que eles processam?

    R: Linguagem associada ao OpenGL, usada para criar shaders que manipulam vértices, pixels e calculam iluminação e os shaders obrigatórios são os Vertex shader e Fragment Shader

- Exercicio 2 - O que são primitivas gráficas? Como fazemos o armazenamento dos vértices na OpenGL?

    R: Primitivas gráficas são as unidades básicas de construção de objetos em gráficos computacionais. Elas são usadas para representar formas geométricas simples no espaço 2D ou 3D.
    
    O armazenamento dos vértices é feito principalmente utilizando buffers, tais como: Vertex Buffer Objects (VBOs) - usados para armazenar os dados dos vértices na memória da GPU) ou o Element Buffer Objects (EBOs) – que armazenam índices que apontam para os vértices em um VBO.

- Exercicio 3 - Explique o que é VBO e VAO, e como se relacionam (se achar mais fácil, pode fazer um gráfico representando a relação entre eles).

    R: Os objetos Vertex Buffer Objects (VBOs)  são usados para armazenar os dados dos vértices na memória da GPU, permitindo acesso rápido e eficiente durante a renderização. Ao usar VBOs, você pode enviar muitos vértices para a GPU de uma só vez, o que melhora o desempenho.

    O Vertex Array Object (VAO) é um objeto que encapsula a configuração de um conjunto de atributos de vértice. Ele armazena o estado das associações entre os VBOs e os atributos de vértice (como posição, cor, normal, etc.). Quando você cria um VAO, você configura como os dados de vértice em um ou mais VBOs devem ser interpretados. Isso significa que você pode facilmente alternar entre diferentes configurações de renderização sem precisar reconfigurar os atributos de vértice toda vez que deseja desenhar um objeto diferente.

    A relação entre VBOs e VAOs é que o VAO "aponta" para um ou mais VBOs que contêm os dados de vértices. Quando você vincula um VAO, todas as configurações de atributos de vértice associadas são ativadas, tornando o processo de renderização mais eficiente.

- Exercicio 4 - Como são feitas as chamadas de desenho na OpenGL? Para que servem as primitivas de desenho?

    As chamadas de desenho são feitas principalmente por meio da função glDrawArrays ou glDrawElements logo após a configuração dos buffers de vértices (VBOs), o objeto de array de vértices (VAO) e os shaders.
    As primitivas de desenho servem para definir a forma básica que será renderizada, como pontos, linhas ou triângulos. Elas informam à GPU como interpretar os vértices passados

## 📌 Contato

- Linkedin: https://www.linkedin.com/in/joão-pedro-carvalho-silva-2b6bba17b/

- Email: pedrocarvalho2021@hotmail.com
