# React Basic

## What´s React?



```text
<blockquote class='tip'>
 <p><strong>Tip:</strong> Texto</p>
</blockquote>
```

![Tip](https://s-media-cache-ak0.pinimg.com/originals/30/2a/f1/302af1274d68e41fcd549e4538f78ecf.png)

Código para los mensajes de advertencia en un post:

```text
<blockquote class='warning'>
 <p><strong>Advertencia:</strong> Texto</p>
</blockquote>
```

![Advertencia](https://s-media-cache-ak0.pinimg.com/originals/ba/54/df/ba54dfb4e1c57fa17830150d90de112b.png)

### Dependencias

Filisantillan cuenta con un archivo `gulpfile.js` que sirve para automatizar el trabajo en desarrollo y que el código de producción sea mucho mejor.

Antes de empezar, se necesita instalar lo siguiente:

* [Node.js](https://nodejs.org/es/)
* [Gulp](http://gulpjs.com/)

Una vez instalado, podemos empezar a descargar todas las dependencias:

**NPM**

```text
$ npm install --save
```

**Yarn**

```text
$ Yarn
```

De no funcionar, se puede usar `sudo` antes del comando y así ejecutar como administrador.

Para que todo el código de desarrollo pase a producción es necesario ejecutar:

```text
$ gulp
```

Con este comando, todo el código que tenemos en desarrollo va a estar optimizado, comprimido y mucho más en la zona de producción.

Para comprimir imágenes:

```text
$ gulp c-images
```

Con este comando las imágenes de producción van a estar comprimidas.

Para comprimir las fuentes:

```text
$ gulp c-fonts
```

Con este comando las fuentes de producción van a estar comprimidas.

### Contacto

* [Facebook](https://www.facebook.com/FiliSantillanMX)
* [Twitter](https://twitter.com/FiliMX)

## Licencia

© Fili Santillán

