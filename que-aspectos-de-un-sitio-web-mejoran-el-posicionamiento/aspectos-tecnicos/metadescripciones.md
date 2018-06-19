# Metaetiquetas

## Descripción general de meta etiquetas

## ¿Cuáles son importantes para el posicionamiento de la Universidad?



## Título o Meta etiqueta Title 

1. Entre 15 y 100 caracteres como máximo. Recomendable hasta 70 caracteres.
2. El título debe ser claro y preciso.
3. Se sugiere que el título del home lleve el nombre del sitio completo: Ejemplo: Facultad de Física UC, Educación Continua UC, etc
4. No usar títulos predeterminados como “Sin título” o “Página nueva”.
5. Para términos de SEO y posicionamiento no es recomendable utilizar nombres simples como “Inicio”, “Home”, “Interior”, etc.
6. Estructura adecuada:
   * Nombre de la página \| Nombre del sitio
   * Nombre del sitio \| Nombre de la página

## **Descripción o Meta Etiqueta Description**

1. 60 a 150 caracteres o 24 palabras como máximo.
2. Debe ser una definición del sitio web y debe ser una propuesta atractiva.
3. Utilizar conceptos o palabras claves relacionadas al contenido.
4. Evitar descripciones extensas o que no tengan relación con el contenido.
5. Evitar duplicación de descripción por página web.

## Encabezados o Headings \(H1, H2, H3, etc\)

El uso de los encabezados o headings de un contenido web son elementos claves en la forma en como priorizamos los títulos del contenido de nuestra web.

Los headings nos ayudan a estructurar los títulos como elemento primordial en la segmentación e importancia que le damos a cada párrafo del contenido. Estos se estructuran del nivel más alto H1 al nivel más bajo H6 en donde el H1 es el encabezado título que se considera de más importancia o relevancia en el inicio de un contenido.

## Palabras claves o Keywords

Pese a que las keywords o palabras claves ya no es un factor que se considera como metadato para SEO, es necesario trabajar en un plan de palabras claves para incorporarlas en el contenido de la web de manera de incluirlas en las distintas secciones del 

```text

```

## Descripción o Alt de imagen

El atributo alt \(alternate text o texto alternativo\) es una breve descripción de la imagen y que se utiliza principalmente para que los buscadores web puedan indexar la imagen de acuerdo al uso de los conceptos o palabras claves de la descripción de la imagen.

### Características del atributo

Las características principales de este atributo son:

1. Descripción de la imagen
2. Uso de una o dos palabras claves asociada al contenido
3. Texto breve

## Meta Robots

Este metadato es de vital importancia para los actuales buscadores web, ya que considera cuándo y cómo debe ser indexado nuestro sitio web. 

Entre las características principales de configuración son:  
****

### Valores 

* Index: Indexa el contenido de la página web, es decir, considera el buscador lo muestra en los resultados de búsqueda.
* NoIndex: Este valor evita la indexación del contenido en los buscadores.
* Follow: Permite que los motores de búsquedas recorran el sitio a través de enlaces.
* No Follow: Evita que los motores de búsqueda consideren los enlaces

### Otros valores a considerar

* _NoODP_, _NoYDIR_ y _NoArchive_

### Uso

El uso de este metadato depende de la definición de cada proyecto web. Entre estos casos tenemos:

1. Cuando una web debe aparecer en los buscadores web y se debe indexar todo el contenido incluyendo los enlaces, el metadato debe poseer los siguientes valores:`<meta name="robots" content="index, follow">`
2. Cuando una web debe aparecer en los buscadores web y se debe indexar todo el contenido pero no se realiza el rastreo a los enlaces o contenido, el metadato debe poseer los siguientes valores:`<meta name="robots" content="index, nofollow">`
3. Cuando una web no debe indexarse pero sus enlaces se deben incluir en el PageRank se debe considerar los siguientes valores:

   `<meta name="robots" content="noindex, follow">`

   El uso de esta combinación la podemos utilizar para plataformas web internas que por ser de uso interno no es necesario indexarlas pero sus enlaces son necesarios para el PageRank en los buscadores.

4. Para indicar que no queremos que se indexe la página ni se sigan los enlaces que pueda contener.

   `<meta name="robots" content="noindex,nofollow">`

   El uso de esta combinación la podemos utilizar para intranets que por ser de uso interno no es necesario indexarlas o seguirlas en los buscadores.

## Etiqueta Rel=Canonical

