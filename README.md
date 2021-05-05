# Languages
 
 * [en-US](#Responsiveness)
 * [pt-BR](#Responsividade)
# 📱Responsiveness

This repository was made for I train responsinevess concepts, and study into practice responsiveness.

## CSS Units

CSS unit of measure.

 **Fixed Layout:**
 * `px` - Pixels

 **Fluid Layout:**
 * `%` - Percentage Usage (0% - 100%)
 * `auto` - Automatic Balancing
 * `vh` - Viewport Height (Y) (0vh - 100vh)
 * `vw` - Viewport Width (X) (0vw - 100vw)

 **Fixed Text:**
 * 1px = 0.75pt
 * 16px = 12pt

 **Fluid Text:**
 * `em` - multiplied for father
 * `rem` - multiplied for root

 **OBS: These properties do not apply only to texts.**
## CSS Media Queries

```css
@media (max-width: 320px) {
  #form h3 {
    font-size: 2rem;
  }
}
```
## HTML Media Attrib.

```html
  <link rel="stylesheet" href="responsive.css" media="screen and (max-width: 768px)">
  
  <link rel="stylesheet" href="print.css" media="print">
```
## Imagens

`<picture>` and `<source>`
```html
<picture class="image" alt="Imagem">
  <source media="(min-width: 768px)" 
    srcset="https://i.ytimg.com/vi/GykTLqODQuU/maxresdefault.jpg">
  <source media="(min-width: 320px)" 
    srcset="https://i.ytimg.com/vi/GykTLqODQuU/hqdefault.jpg">
  <source media="(min-width: 10px)" 
    srcset="https://i.ytimg.com/vi/GykTLqODQuU/mqdefault.jpg">

  <img 
    src="https://i.ytimg.com/vi/GykTLqODQuU/hqdefault.jpg" 
    alt="Imagem" />
</picture>
```
 * Always use the SVG format for creating responsive websites, as it supports changing the image with good resolution.
# 📱Responsividade 

Esse repositório foi feito para eu treinar conceitos de responsivdade, e estudar mesmo na prática responsividade.

## CSS Units

Unidades de medida do CSS.

 **Layout Fixo:**
 * `px` - Pixels

 **Layout Fluido:** 
 * `%` - Uso da Porcentagem (0% - 100%)
 * `auto` - Balanceamento Automático
 * `vh` - Viewport Height (Y) (0vh - 100vh)
 * `vw` - Viewport Width (X) (0vw - 100vw)

 **Textos Fixos:**
 * 1px = 0.75pt 
 * 16px = 12pt

 **Textos Fluidos:**
 * `em` - multiplicado pelo pai
 * `rem` - multiplicado pelo root

 **OBS: Essas propriedades não se aplicam somente em textos.**

## CSS Media Queries

```css
@media (max-width: 320px) {
  #form h3 {
    font-size: 2rem;
  }
}
```
## HTML Media Attrib.

```html
  <link rel="stylesheet" href="responsive.css" media="screen and (max-width: 768px)">
  
  <link rel="stylesheet" href="print.css" media="print">
```
## Images

`<picture>` e `<source>`
```html
<picture class="image" alt="Imagem">
  <source media="(min-width: 768px)" 
    srcset="https://i.ytimg.com/vi/GykTLqODQuU/maxresdefault.jpg">
  <source media="(min-width: 320px)" 
    srcset="https://i.ytimg.com/vi/GykTLqODQuU/hqdefault.jpg">
  <source media="(min-width: 10px)" 
    srcset="https://i.ytimg.com/vi/GykTLqODQuU/mqdefault.jpg">

  <img 
    src="https://i.ytimg.com/vi/GykTLqODQuU/hqdefault.jpg" 
    alt="Imagem" />
</picture>
```
 * Utilize sempre o formato SVG para criação de sites responsivos, pois ele suporta a alteração da imagem com boa resolução.
   
