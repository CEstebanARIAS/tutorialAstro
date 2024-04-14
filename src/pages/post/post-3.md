---
title: Referencia de la API 
author: Alumno de Astro
description: "Tuve algunos problemas, pero preguntar en la comunidad me ayudó mucho."
image:
    url: "https://docs.astro.build/assets/rays.webp"
    alt: "Miniatura de los rayos de Astro."
pubDate: 2024-04-14
tags: ["astro", "aprender en público", "contratiempos", "comunidad"]
---
No siempre ha sido fácil, pero disfruto construyendo con Astro. Además, la [comunidad de Discord](https://astro.build/chat) es muy amable y servicial.

## Para construir una row function se utiliza el signo => con el que devuelve la informacion

1. las fechas en astro se pueden formatear para que solo aparezca AAA/MM/DD porque siempre devuelve el formato con la zona horaria por lo que se puede utilizar dentro de {}

{new Date(post.frontmatter.pubDate).toISOString().split('T')[0]}

new Date: Crea un array en donde se almacenan los strings

.toISOString(): Cambia el formato de fecha a String

.split(). Separa el texto desde la T que es la letra que indica la zona horaria y que no necesitamos