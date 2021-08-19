# **Ciclos de vida del Desarrollo de Software**

## *Laboratorio No. 1 (Parte II - Introducción General Git)*

___

¡Buen día! Mi nombre es **Camilo Andrés Pichimata Cárdenas** tengo 20 años y me encuentro estudiando ***Ingeniería de Sistemas*** en la ***Escuela Colombiana de Ingeniería Julio Garavito***, en este momento estoy en _séptimo semestre_ y estoy cursando las siguietes materias:

1. **AUPN** - Automatización de Procesos de Negocio
2. **CVDS** - Ciclos de vida del Desarrollo de Software
3. **EGI4** - Inglés 4
4. **RECO** - Redes de computadores

El plan de estudios que curso actualmente se puede visualizar dando click [aquí](https://escuelaing.s3.amazonaws.com/staging/documents/Malla-curricular-a_partir_de_2018-2-Ingenier%C3%ADa_de_Sistemas.pdf?AWSAccessKeyId=AKIAWFY3NGTFBJGCIWME&Signature=YSxo31VdocoPdbOM6LRMDnt4hiQ%3D&Expires=1631730416).

Actualmente me encuentro viviendo en una de las veredas del municipio de [Cachipay](https://es.wikipedia.org/wiki/Cachipay) Cundinamarca, la mayor parte de mi vida he vivido en el campo, estudié hasta grado 5° en la sede escuela rural Cayunda de la I.E.D. Alfonso López Pumarejo y luego en el Instituto Técnico Olga Santamaría del municipio de [Anolaima](https://es.wikipedia.org/wiki/Anolaima), un municipio vecino, hasta graduarme de bachiller; Dejo algunas fotos de los lugares en los que estudié.

### Escuela Rural Cayundá 
![](EscuelaCayunda.png)

### Instituto Técnico Olga Santamaría
![](https://userscontent2.emaze.com/images/16c42b75-cbda-4dd1-8cd9-b6aaa558e687/c3470757-984f-48d2-99ee-d275129be73a.jpg)

Una de las cosas que más me gusta hacer es _montar bicicleta_, algo que me llamó la atención desde que era un niño, he ido a distintos lugares y conocido gran parte de sitios cercanos al lugar en el que vivo, a continuación menciono algunos de ellos

+ Municipio de Zipacón
+ Municipio de La Mesa
+ La Gran Vía
+ Corregimiento de Peñanegra 
+ Corregimiento de la Florida 
+ Y muchos más...

Y para finalizar, les dejo uno de los códigos que he realizado durante mis estudios, este tiene como fin *calcular el producto punto de dos vectores* en el lenguaje de programación C

```
#include <stdio.h>
#include <stdlib.h>

int main() {
    int numToCalc;
    int longVect;
    int i, j, k, l;
    float rta;

    scanf ("%d", &numToCalc);
    
    for (i=1; i<=numToCalc; i++) {
        scanf ("%d", &longVect);
        float vector1[longVect];
        float vector2[longVect];

        for (j=1; j<=longVect; j++) {
            scanf ("%f", &vector1[j-1]);
        }

        for (k=1; k<=longVect; k++) {
            scanf ("%f", &vector2[k-1]);
        }
        rta = 0;
        for (l=1; l<=longVect; l++) {
            rta = rta + vector1[l-1]*vector2[l-1];
        }
        printf ("%f \n", rta);
    }
    return 0;
}
```
