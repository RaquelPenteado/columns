# columns

# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

### The challenge

O desafio consiste em criar uma tela responsiva com 3 colunas

### Screenshot

![](C:\Users\raque\Documents\projetos\3-column-preview-card-component-main\images\resultado.png)

![](C:\Users\raque\Documents\projetos\3-column-preview-card-component-main\images\responsive.png)

### Links

- Solution URL: [GitHub](https://github.com/RaquelPenteado/columns)
- Live Site URL: [Vercel](https://columns.vercel.app)

## My process

### Built with

- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

Pude aprender um pouco mais sobre o uso de grids e responsividade

```css
.content{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}
```



```css
@media only screen and (max-width: 768px){
    .content{
        grid-template-columns: 1fr;
    }
}
```

### Useful resources

- [Link](https://www.youtube.com/watch?v=rCBYZ7xn-us&t=6s) - Para entender um pouco mais sobre grids, eu encontrei um vídeo que me guiou.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/RaquelPenteado)
- Twitter - [@yourusername](
