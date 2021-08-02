# Como usar HackMD, Markdown e arquivos .MD

### O que é Markdown
 - É uma linguagem de programação que se converte de maneira eficiente em arquivos de texto;
 - Compõe os arquivos README no GitHub;
 - Usada em Fóruns e em Posts;
 - Tem uma linguagem de programação extremamente simples e intuitiva.

### O que se pode fazer com Markdown

 - Títulos;
 - Listas;
 - Links;
 - Blocos de código;
 - Tabelas;
 - e outros.

### Onde escrever Markdown
Pode-se escrever Markdown em diversos editores de texto, como Atom, VSCode e similares, mas a ferramenta usada para fazer esse guia é o site [HackMD](https://hackmd.io/), que pode inserir com poucos comandos os arquivos escritos em repositórios no GitHub.

## Como escrever Markdown



### **Títulos**

Basta colocar a quantidade de # correspondente ao tamanho do título. Exemplo:

"# Título 1"

"## Título 2"

"### Título 3"

E assim segue até o 6.

---


### **Itálico, negrito e cortado**

Para itálico basta usar asteriscos ao redor da palavra. Para negrito, dois asteriscos. Para cortado, dois '~' Exemplo: 

Este texto está em *itálico*. Já este, em **negrito**. Por fim, ~~cortado~~. Código correspondente: 

![](https://i.imgur.com/OxFVRWT.png)


Obs.: funciona com '_' também.

---

### **Linha horizontal**
É a linha que divide cada tópico desse arquivo.

Exemplo do texto acima:

![](https://i.imgur.com/y2DO2GV.png)


---

### **Citação**

Se faz usando '>' no início da frase. Exemplo:

> Isso é uma citação.

![](https://i.imgur.com/eAWjCWJ.png)

---

### **Links**

Se escreve primeiro o nome que aparece no lugar do link entre colchetes ( [] ), depois entre parênteses o link do site. Exemplo usado no início do arquivo:

> [HackMD](https://hackmd.io/)

Se escreve: 

![](https://i.imgur.com/GNzgDpz.png)

---

### **Listas**

Se fazem listas usando travessões ou asteriscos. Exemplo:

* Item 1
* Item 2
    * Item 2.1

ou

1. Item 1
2. Item 2

![](https://i.imgur.com/5Ioj9yK.png)

---

### **Imagens**
Para se inserir imagens, no caso do [HackMD](https://hackmd.io/), basta dar Ctrl+V no local desejado ou selecionar a imagem que se deseja usar que já está no seu pc através da ferramenta disponível no site. em outros casos, é necessário escrever:

!, depois [], que pode conter o título da imagem entre parênteses, depois () contendo o link da imagem.

Exemplo:

! [Imagem do item anterior] (https://i.imgur.com/5Ioj9yK.png)

Mas sem os espaços entre os elementos.

![](https://i.imgur.com/HQ3CV8n.png)

---

### **Específicos do GitHub**

#### Blocos de código

Pode-se inserir blocos de outros códigos dentro do arquivo .MD; Exemplo com um bloco de python:

```python=
def add(num1, num2):
    return num1 + num2
```

![](https://i.imgur.com/pmyGTY5.png)

---

#### **Tabelas**

Podem se integrar mais células horizontalmente e verticalmente, basta inserir mais elementos. Observe:

|Nome | E-mail|
| ----- | ------ |
| Wolverine | wolverine@gmail.com |

![](https://i.imgur.com/VcLpV4L.png)

---

## Como colocar os arquivos feitos no [HackMD](https://hackmd.io) diretamente no [GitHub](https://github.com)

O site HackMD, além de um facilitador na escrita e edição de Markdown, funciona perfeitamente com o GitHub na hora de puxar arquivos que já existem, a fim de editá-los, ou simplesmente enviar novos. O processo funciona da seguinte maneira:

### Para obter arquivos

1. Clique nos três pontos no lado direito de cima da tela
2. Escolha "Versions and GitHub Sync"

![](https://i.imgur.com/pu6TACi.png)

3. Escolha a opção Pull

![](https://i.imgur.com/ydJohKS.png)

4. Então, basta escolher o arquivo que se deseja editar no site.

### Para fazer upload para o GitHub

O processo é o mesmo que o anterior, mas quando se estiver na aba "Versions and GitHub Sync", deve-se selecionar o arquivo na coluna da esquerda, clicar em Push e selecionar o repositório que será seu destino.