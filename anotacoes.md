textos fixos:
1px = 0.75 pontos.
16px(padrão de textos dos nossos navegadores atuais)

textos fluidos:

- 'em': Este atributo é multiplicado pelo pai.
  ex:

li{
font-size:14px
}
li a{
font-size: 2em;
}

// o elemento a ficará com uma fonte de 14X2 =28px

- 'rem': Este atributo é multiplicado pelo root

obs:
para adicionarmos uma classe a alguma estrutura html, utilizamos o seguinte recuros
javaScript:
Utilizamos a classe 'toglle', da seguinte maneira:
nomeDaClasseAoQualQuerAdicionarOutraClasse.classList.toggle("nomeDaClasseAserAdicionada")
