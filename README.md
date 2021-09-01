# Origin-Six
#### Projeto desenvolvido durante a Next Level Week da Rocketseat.
<a href="https://leandrolucs.github.io/templateWeb/">![image](https://user-images.githubusercontent.com/48057126/131681579-06f9f955-e58e-42d5-a50e-b9be8bfef182.png)</a>

## 🚀 Tecnologias
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>Javscript</li>
</ul>

## 💻 Objetivo
Site desenvolvido com intuito de iniciar o estudo de HTML, CSS e Javascript, podendo ser usada como referência para a produção dos próximos.

## 📚 Features
### ◼️ Biblioteca Swiper para exibição dos depoimentos dos clientes do salão de beleza
```js
const swiper = new Swiper('.swiper-container', {
  slidesPerView: 1,
  pagination: {
    el: '.swiper-pagination'
  },
  mousewheel: true,
  keyboard: true,
  breakpoints: {
    767: {
      slidesPerView: 2,
      setWrapperSize: true
    }
  }
})
```
![image](https://user-images.githubusercontent.com/48057126/131682853-635d880c-8ad6-416b-b8c9-7fe8e4aeadd8.png)

####

### ◼️ Biblioteca Scroll Reveal para exibição dos itens gradualmente de forma suave, com uma pequena transição

```js
const scrollReveal = ScrollReveal({
  origin: 'top',
  distance: '30px',
  duration: 700,
  reset: true
})
scrollReveal.reveal(
  `#home .image, #home .text,
  #about .image, #about .text,
  #services header, #services .card,
  #testimonials header, #testimonials .testimonials,
  #contact .text, #contact .links
  footer .brand, footer .social
  `,
  { interval: 100 }
)
```

### ◼️ Além disso, apresenta responsividade para os diversos dispositivos

![image](https://user-images.githubusercontent.com/48057126/131684725-a436f9d8-b8aa-4162-8f4c-4920fbc0a3d0.png)
