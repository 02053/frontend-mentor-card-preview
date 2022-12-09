# Solucion a Product preview card component - Frontend Mentor

Esta es una solucion del reto [Product preview card component de Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa)
## Tabla de contenido

- [Vision general](#vision-general)
  - [El reto](#el-reto)
  - [Captura de pantalla](#captura-de-pantalla)
  - [Enlaces](#enlaces)
- [Mi proceso](#mi-proceso)
  - [Hecho con](#hecho-con)
  - [Que he aprendido](#que-he-aprendido)
  - [Recursos utiles](#recursos-utiles)
- [Autor](#autor)

## Vision general
### El reto

Los usuarios deben ser capaces de:

- Ver el diseño óptimo dependiendo del tamaño de pantalla de su dispositivo
- Ver estados de desplazamiento y enfoque para elementos interactivos
### Captura de pantalla

![captura de pantalla del reto de Frontend menter](./Frontend-Mentor-Product-preview-card-component.png)

### Enlaces

- Solucion: [Repositorio de Github](https://github.com/02053/frontend-mentor-card-preview)
- Sitio en vivo: [Pagina en Github Pages](https://02053.github.io/frontend-mentor-card-preview/)

## Mi proceso

### Hecho con

- HTML5
- CSS
- Variables de CSS
- Flexbox
- Media queries
- Variables fluidas

### Que he aprendido

Usar las etiquetas **picture** y **source** para ralizar el cambio de la imagen de la tarjeta cuando este en un dispositivo movil o una PC.

A continuacion un ejemplo de la etiqueta **picture** y **source**:

```html
<picture class="card-image">
  <source srcset="./images/image-product-mobile.jpg" media="(max-width:756px)"/>
  <img src="./images/image-product-desktop.jpg" alt="perfume image"/>
</picture>
```

### Recursos utiles

- [fluid type scale calculator](https://utopia.fyi/type/calculator/?c=320,17,1.2,1500,20,1.333,6,2,&s=0.75|0.5|0.25,1.5|2|3|4|6,s-l&g=s,l,xl,12) - Este es una calculadora que nos da diferentes variables CSS que nos ayuda a crear un diseño responsivo fluido en cuanto al tamaño de las fuentes, margenes y relleno (padding).

## Autor

- Frontend Mentor - [@02053](https://www.frontendmentor.io/profile/02053)
