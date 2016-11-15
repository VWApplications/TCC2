# TCC

## Instalação

```sudo apt-get install texlive-full```

## Compilando

Para compilar o texto através do Makefile digite:

  ```sh
	  make clean
	  make
  ```

## Estrutura do template

* **Pasta fixos**: Arquivos de configuração, não necessário e nem aconselhável mexer caso não tenha conhecimento.

* **Pasta Figuras**: Onde será inserido as figuras do tipo **.eps**, para converter é só baixar o ImageMagick e no terminal digitar:

```sh
  convert figura.png figura.eps
  convert figura.png figura.pdf
  convert figura.jpg figura.eps
  convert figura.jpg figura.pdf
```

* **Pasta Editaveis**: Onde será inserido todo o conteúdo do documento.

* **Arquivo Makefile**: Cada arquivo.tex da pasta editaveis terá que ser inserido no makefile na área chamada EDITAVEIS_SOURCES para que seja compilado

* **Arquivo main.tex**: Onde será organizado o corpo do documento, cada arquivo.tex criado na pasta editaveis deve ser
inserido na ordem que irá aparecer no documento através do comando ```\input{editaveis/NomeDoArquivo.tex}```

## Outras informações

Licenciado em Creative Commons Atribuição 3.0: http://creativecommons.org/licenses/by/3.0/

Desenvolvido e adaptado pelo professor Edson Alves edsomjr@gmail.com.

Contribuição pelo aluno Victor Arnaud

