# Store Theme Asus

## Índice

* [Resumen del proyecto](#Resumen-del-proyecto)
* [Vistas](#Vistas)
* [Home](#Home)
* [Header Desktop, tablet y phone](#Header-Desktop,tablet-y-phone)
* [Footer Desktop, tablet y phone](#Footer-Desktop,tablet-y-phone)
* [Configuración](#Configuración)


## Resumen del proyecto

Realizar una copia de la página de Asus usando la tecnología de Vtex IO.

## Vistas

## Home
![Home](https://i.imgur.com/5QOXgYm.jpg) 

## Header Desktop,tablet y phone

**Header desktop** 

![Header desktop](https://i.imgur.com/eAPoXpy.png) 

**Header tablet** 

![Header tablet](https://i.imgur.com/mbbolcT.jpg)

**Header phone** 

![Header phone](https://i.imgur.com/s3OupKn.jpg)

## Footer Desktop,tablet y phone

**Footer desktop** 

![Footer desktop](https://i.imgur.com/xp5DRd7.jpg) 

**Footer tablet** 

![Footer tablet](https://i.imgur.com/z4U5riI.jpg)

**Footer phone** 

![Footer phone](https://i.imgur.com/sXkiz6A.jpg)

## Configuración

### Paso 1 - Configuración básica

Ingrese a la [guía básica de configuración](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-2-basicsetuptodevelopinvtexio) de VTEX IO y siga los pasos.  
Al final de la configuración, debería tener instalada la interfaz de línea de comandos de VTEX (Toolbelt) junto con un workspace para desarrolladores en el que pueda trabajar.

### Paso 2 - Clonación del repositorio Minimum Boilerplate.

Use este repositorio como [plantilla](https://github.com/vtex-apps/minimum-boilerplate-theme) para crear un repositorio de forma local para poder comenzar a trabajar de manera efectiva en él, luego acceda al directorio del repositorio usando su terminal.

### Paso 3 - Editando el archivo Manifest.json

Una vez en el directorio del repositorio, es hora de editar el archivo manifest.json.

Una vez estemos en el archivo, deberá remplazar los valores de vendor y name. vendor es el nombre de la cuenta en la que estamos trabajando y account es lo que desee colocar de nombre para su tema. Opcionalmente puede modificar la versión

Por ejemplo:  
{
"vendor": "itgloberspartnercl",
"name": "store-theme",
"version": "0.0.1",
"builders": {
"assets": "0.x",
"docs": "0.x",
"store": "0.x",
"styles": "2.x"
},
}

### Paso 4 - Instalando las apps requeridas

Para usar Store Framework y trabajar en el tema de su tienda, es necesario tener `vtex.store-sitemap` y `vtex.store` instalados.

Ejecute `vtex list` y compruebe si esas aplicaciones ya están instaladas.

Si no es así, ejecute el siguiente comando para instalarlos: `vtex install vtex.store-sitemap vtex.store -f`

### Paso 5 - Desinstalar cualquier tema existente

Al correr `vtex list`, puede verificar si hay algún tema instalado.

Es común tener ya instalado un vtex.store-theme cuando inicia el proceso de desarrollo front de la tienda.

Por lo tanto, si lo encuentra en la lista de la aplicación, copie su nombre y utilícelo junto con el comando `vtex uninstall`. Por ejemplo:

```json
vtex uninstall vtex.store-theme
```

### Paso 6 - Ejecute y obtenga una vista previa de su tienda

Entonces ha llegado el momento de cargar todos los cambios que realizó en sus archivos locales a la plataforma. Para eso, use el comando `vtex link`.

Si el proceso se ejecuta sin errores, se mostrará el siguiente mensaje: `App linked successfully`. Luego, ejecute el comando vtex browse para abrir una ventana del navegador con su tienda vinculada.

Esto le permitirá ver los cambios aplicados en tiempo real, a través de la cuenta y el espacio de trabajo en el que está trabajando.

## Dependencias

1. Store minimun boilerplate theme
2. Store GraphQl

## Store Component Apps

1. "vtex.store": "2.x",
2. "vtex.store-header": "2.x",
3. "vtex.product-summary": "2.x",
4. "vtex.store-footer": "2.x",
5. "vtex.store-components": "3.x",
6. "vtex.styleguide": "9.x",
7. "vtex.slider": "0.x",
8. "vtex.carousel": "2.x",
9. "vtex.shelf": "1.x",
10. "vtex.menu": "2.x",
11. "vtex.minicart": "2.x",
12. "vtex.product-details": "1.x",
13. "vtex.product-kit": "1.x",
14. "vtex.search-result": "3.x",
15. "vtex.login": "2.x",
16. "vtex.my-account": "1.x",
17. "vtex.flex-layout": "0.x",
18. "vtex.rich-text": "0.x",
19. "vtex.store-drawer": "0.x",
20. "vtex.locale-switcher": "0.x",
21. "vtex.product-quantity": "1.x",
22. "vtex.product-identifier": "0.x",
23. "vtex.product-specification-badges": "0.x",
24. "vtex.product-review-interfaces": "1.x",
25. "vtex.telemarketing": "2.x",
26. "vtex.order-placed": "2.x",
27. "vtex.stack-layout": "0.x",
28. "vtex.tab-layout": "0.x",
29. "vtex.responsive-layout": "0.x",
30. "vtex.slider-layout": "0.x",
31. "vtex.iframe": "0.x",
32. "vtex.breadcrumb": "1.x",
33. "vtex.sticky-layout": "0.x",
34. "vtex.add-to-cart-button": "0.x",
35. "vtex.store-link": "0.x",
36. "vtex.disclosure-layout": "1.x",
37. "vtex.search": "2.x",
38. "vtex.store-icons": "0.x",
39. "vtex.overlay-layout": "0.x",
40. "vtex.product-context": "0.x",
41. "vtex.product-price": "1.x",
42. "vtex.modal-layout": "0.x",
43. "vtex.product-highlights": "2.x",
44. "vtex.product-specifications": "1.x",
45. "vtex.product-list": "0.x",
46. "vtex.checkout-summary": "0.x",
47. "vtex.store-form": "0.x",

## Dependencias Peer store component

1.  "vtex.mega-menu": "2.x",
2.  "vtex.wish-list": "1.x",
3.  "vtex.questions-and-answers": "0.x"

## Custom Apps

1.  "itgloberspartnercl.whatsapp-button": "0.x"

## Contributors

Dannit Alexandra Hernández Cristancho