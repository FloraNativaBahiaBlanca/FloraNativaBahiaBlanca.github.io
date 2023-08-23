---
layout: post
title: "Phyla nodiflora (Bella Alfombra)"
tags: [Cubresuelos, Flores blancas]
categories: [Flora, Verbenaceae]
image: assets/images/Phyla1.png
---

***

**Tipo:** Herbácea

**Medidas:** Hasta 10 cm. de alto

**Otros nombres:** Verbena del Pozo, Lipia

***

📋 **Descripción:** Herbácea perenne de follaje caduco. Hojas pequeñas, entre 1 y 2,5 cm. de longitud, algo carnosas, con pelos y el borde aserrado desde la mitad hasta el extremo. Flores de 2 a 3 mm. de longitud, blancas o liliáceas, en capítulos. El fruto es seco y se separa en la madurez.

**Fauna que atrae:** (🦋🐝🪲🐦) Atrae diversos insectos autóctonos como abejas, mariposas y escarabajos. Es hospedera de la mariposa 'Cuatro Ojos' (*Junonia genoveva hilaris*). Sus semillas atraen aves granívoras.

🔍 **Otros datos:** Especie muy difundida como cubresuelos. Requiere exposición al sol y muy poco riego. Se puede propagar por semillas pero resulta más sencillo hacerlo por división de matas. Florece abundantemente de primavera a otoño. Presenta tres variedades; var. nodiflora, var. minor y var. reptans, diferenciándose entre ellas por la forma y tamaño de la lámina foliar.

***

<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Carrusel de Fotos</title>
    <style>
        /* Estilos CSS para el carrusel */
        .carousel-container {
            width: 100%;
            overflow: hidden;
            position: relative;
        }

        .carousel {
            display: flex;
            transition: transform 0.5s ease;
        }
    
        .carousel img {
            width: 100%;
            height: auto;
        }
    
    /* Estilos específicos para dispositivos móviles (ejemplo: pantalla menor de 768px) */
    @media (max-width: 768px) {
        .carousel img {
            /* Ajustar el tamaño de la imagen para pantallas más pequeñas si es necesario */
            max-width: 100%;
            height: auto;
        }
    
        /* Ajustar estilos adicionales según sea necesario */
    }
    
        .carousel-button {
            position: absolute;
            top: 50%;
            transform: translateY(-50%);
            background: rgba(0, 0, 0, 0.5);
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            z-index: 1;
        }
    
        .prev-button {
            left: 0;
        }
    
        .next-button {
            right: 0;
        }
    </style>
</head>
<body>
    <div class="carousel-container">
        <button class="carousel-button prev-button" onclick="prevSlide()">&#9664;</button>
        <div class="carousel">
            <img src="/assets/images/1.jpg" alt="Imagen 1">
            <img src="/assets/images/3.jpg" alt="Imagen 2">
            <img src="/assets/images/4.jpg" alt="Imagen 3">
            <!-- Agrega más imágenes aquí -->
        </div>
        <button class="carousel-button next-button" onclick="nextSlide()">&#9654;</button>
    </div>

    <script>
        const carousel = document.querySelector('.carousel');
        let currentIndex = 0;
    
        function showSlide(index) {
            if (index < 0) {
                currentIndex = carousel.children.length - 1;
            } else if (index >= carousel.children.length) {
                currentIndex = 0;
            }
    
            carousel.style.transform = `translateX(-${currentIndex * 100}%)`;
        }
    
        function prevSlide() {
            currentIndex--;
            showSlide(currentIndex);
        }
    
        function nextSlide() {
            currentIndex++;
            showSlide(currentIndex);
        }
    
        // Inicialmente, muestra la primera imagen
        showSlide(currentIndex);
    </script>
    </body>
    </html>
***

**Bibliografía:**

Cané, L. & Nardini, C. A. (2023). *Nativas* (1ᵃ ed.). Revista Jardín

Instituto de Botánica Darwinion. (2018). *Flora Argentina. Phyla nodiflora var. nodiflora*. Recuperado de http://buscador.floraargentina.edu.ar/species/details/193031

Sanhueza, C. et al. (2016). *Plantas nativas de Bahía Blanca y alrededores: descubriendo su historia, belleza y magia* (2ᵃ ed.). BBF UNS