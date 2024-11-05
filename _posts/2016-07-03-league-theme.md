---
title: "CAPITULO 7"
layout: post
permalink: /league/
theme: league

slides:
 - title: "Medios de Transmisión"
   slide-data: "Se define en términos generales como cualquier cosa que pueda llevar información desde una fuente a un destino. Por ejemplo: El medio de transmisión para dos personas que conversan es el aire, ya que puede transmitir un mensaje."

 - title: "MEDIOS"
   slide-data: "En telecomunicaciones, los medios de transmisión se pueden dividir en dos grandes categorías: Medios guiados, que incluyen el cable de par trenzado, el cable coaxial y el cable de fibra óptica. Medios no guiados, que es el espacio libre."

 - title: "Medios Guiados"
   slide-data: "Los medios guiados, como el cable de par trenzado, coaxial y fibra óptica, dirigen las señales dentro de sus límites físicos. Los cables de cobre (par trenzado y coaxial) transportan señales eléctricas, mientras que la fibra óptica transporta señales de luz."

 - title: "Cable de Par Trenzado"
   slide-data: "Un par trenzado consta de dos conductores (normalmente cobre), cada uno con su propio aislamiento plástico, trenzados entre sí. Uno de los cables se utiliza para llevar señales al receptor y el otro se utiliza únicamente como referencia de tierra."

 - title: "Cable UTP vs STP"
   slide-data: "El conector UTP más común es el RJ45 (RJ significa conector registrado), como se muestra en la Figura 7.5.
Por otro lado, el cable de par trenzado blindando (STP)tiene una cubierta metálica que mejora la calidad al reducir el ruido y la diafonía, pero es más voluminoso y costoso, es desarrollada por IBM."

 - title: "Conectores UTP y STP"
   slide-data: "El conector UTP más común es el RJ45. Por otro lado, el cable de par trenzado blindado (STP) tiene una cubierta metálica que mejora la calidad al reducir el ruido y la diafonía."

 - title: "Categorías de Par Trenzado"
   slide-data: "Existen diferentes categorías de cables de par trenzado que se definen por sus capacidades de transmisión de datos, según su diseño y calidad de materiales."

 - title: "Conector RJ45"
   slide-data: "El RJ45 es un conector codificado que solo se puede insertar de una manera. Es utilizado comúnmente en redes Ethernet."

 - title: "Desempeño de Par Trenzado"
   slide-data: "La atenuación en los cables de par trenzado aumenta con la frecuencia, medida en decibeles por kilómetro (dB/km). Un cable de par trenzado puede transmitir una amplia gama de frecuencias, siendo común en conexiones telefónicas y redes LAN."

 - title: "Cable Coaxial"
   slide-data: "El cable coaxial transporta señales de alta frecuencia y tiene un conductor central de cobre, rodeado de una funda aislante y un conductor exterior metálico que protege contra el ruido y completa el circuito."

 - title: "Normas de Cable Coaxial"
   slide-data: "Los cables coaxiales se clasifican según el número RG, que define especificaciones como el calibre del conductor, tipo de aislante, blindaje y cubierta,adaptando cada tipo a funciones especializadas"

 - title: "Conectores de Cable Coaxial"
   slide-data: "Entre los conectores coaxiales se encuentran el BNC, para conectar el cable a un dispositivo, el conector BNC T para derivaciones y el terminador BNC para evitar reflexiones de señal."

 - title: "Fibra Óptica"
   slide-data: "La fibra óptica, hecha de vidrio o plástico, transmite señales como luz y se utiliza en redes troncales por su gran ancho de banda y seguridad contra interferencias electromagnéticas."

 - title: "Modos de Propagación de Fibra"
   slide-data: "Existen dos modos principales para propagar la luz en fibras ópticas: multimodo y monomodo, cada uno adecuado para diferentes aplicaciones y distancias."

 - title: "Tipos de Fibras Ópticas"
   slide-data: "Las fibras ópticas se definen por la relación entre el diámetro de su núcleo y el revestimiento, ambos expresados en micrómetros."

 - title: "Conectores de Fibra Óptica"
   slide-data: "El conector (SC) se utiliza para televisión por cable, El conector de punta recta (ST) se utiliza para conectar el cable a dispositivos de red."

 - title: "Ventajas y Desventajas de Fibra Óptica"
   slide-data: "La fibra óptica ofrece mayor ancho de banda, inmunidad a interferencias y seguridad, pero requiere instalación especializada y es más costosa que otros medios."

 - title: "Medios No Guiados (Inalámbricos)"
   slide-data: "Los medios no guiados transportan ondas electromagnéticas sin conductor físico, utilizando el espacio libre para transmisión. Es el caso de la comunicación inalámbrica."

 - title: "Métodos de Propagación Inalámbrica"
   slide-data: "Los métodos de propagación incluyen: terrestre (ondas de baja frecuencia), en el cielo (frecuencia media) y en línea de visión (alta frecuencia)."

 - title: "Antena Omnidireccional"
   slide-data: "Comunicaciones por microondas requieren antenas unidireccionales, siendo las más comunes las antenas parabólicas y las de bocina.
La antena parabólica utiliza una superficie en forma de parábola para reflejar las ondas que llegan paralelas a su eje, concentrándolas en un punto llamado foco.
permite captar y dirigir más señal, mejorando la calidad y eficiencia de la transmisión"

 - title: "Ondas de Radio"
   slide-data: "Las ondas de radio son omnidireccionales y no requieren alineación entre antenas, lo cual facilita su recepción, aunque pueden sufrir interferencias. Por eso, las antenas emisoras y receptoras no necesitan estar alineadas; una antena emisora puede enviar ondas que cualquier antena receptora puede captar."

 - title: "Microondas"
   slide-data: "Las microondas son ondas electromagnéticas con frecuencias entre 1 y 300 GHz y son unidireccionales, lo que significa que las antenas deben estar alineadas para comunicarse."

 - title: "Antena unidireccional"
   slide-data: "Comunicaciones por microondas requieren antenas unidireccionales, siendo las más comunes las antenas parabólicas y las de bocina."."
   
    - title: "Infrarojo"
   slide-data: "Las ondas infrarrojas, con frecuencias entre 300 GHz y 400 THz, son útiles para comunicación de corto alcance ya que no atraviesan paredes, evitando interferencias entre sistemas en distintas habitaciones."

---

{% for slide in page.slides %}
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
{% endfor %}

