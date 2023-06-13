# HTML5-CSS3-Tecnicas-Avancadas
Curso HTML5 e CSS3: Técnicas Avançadas (Com Flexbox e 5 Projetos) da Udemy - https://www.udemy.com/course/html5-e-css3-tecnicas-avancadas-com-flexbox-e-3-projetos/


## <strong>HTML5 - TÓPICOS AVANÇADOS</strong>

### <strong>figure - Imagem com legenda</strong>
````
<figure>
  <img src="..." alt="...">
  <figcaption>legenda da imagem</figcaption>
</figure>
````  

### <strong>Atributo autofocus aplicado em um input</strong>
- O autofocus faz com que a caixa do input fique selecionado assim que a página seja carregada.
````
<input type="text" placeholder="digite aqui" autofocus>
````  

### <strong>Content editable</strong>
- Atributo para tornar uma tag editável pelo usuário. A edição feita é somente visual, não possui persistência.

### <strong>Tag progress</strong>
- Barra de loading
```
<progress value="50" max="100"></progress>
```

## <strong>CSS3 - TÓPICOS AVANÇADOS</strong>

### <strong>Animações - CSS3</strong>
- @keyframes: é onde definimos o comportamento da animação, o que irá acontecer. Pode ser sair de um estado A para B, utilizando from e to, ou definindo vários passos, utilizando porcentagens.
- animation-name: atributo inserido no elemento que queremos animar, e passamos o nome da keyframe que queremos que ele execute.
- animation-duration: duração da animação.
- animation-delay: define um delay para a animação iniciar.
- animation-iteration-count: quantidade de vezes que a animação ocorrerá.
- animation-timing-function: define como será o comportamento da animação.
  - linear
  - ease
  - ease-in
  - ease-out
  - ease-in-out

### <strong>Gradiente - CSS3</strong>
- Linear: por padrão a primeira cor é a de cima, seguida da de baixo
```
background-image: linear-gradient(purple, blue);
```
```
background-image: linear-gradient(to right, purple, blue);
```
- Radial