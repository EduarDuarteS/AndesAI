# AndesAI - Test Roll Backend 

En este reto estaremos usando [Next.js](https://nextjs.org/) como complemento a React

</Br>

## Instalaciones Previas

### Installar Git



### Installar Node

 _**NOTA:** Se recomienda usar la versión 17 de node_

```
C1O0CS02CG51B2:AndesAI edduarte$ node -v
v14.18.3
C1O0CS02CG51B2:AndesAI edduarte$ npm -v
6.14.15
```

[Guía instalación Node en MAC](https://medium.com/javascript-comunidad/c%C3%B3mo-instalar-node-js-y-npm-en-mac-9d80f26fb88d)



## Empezar a trabajar

### Clonar repositorio

```
git clone https://github.com/EduarDuarteS/AndesAI.git
````


_**NOTA:** instale las dependencias del proyecto antes de correr cualquier script_

```bash
npm i
# or
yarn
```

En la carpeta donde se encuentra el proyecto, ejecutas el proyecto con el comando:

```bash
npm run dev
# or
yarn dev
```

Open http://localhost:3000 with your browser to see the result.

The api endpoints expose on http://localhost:3000/api/


## APIs públicas a consumir
- **Busqueda**

     https://api.mercadolibre.com/sites/MLA/search?q={ARTICULO}  

    Ejemplo:
    https://api.mercadolibre.com/sites/MLA/search?q=impresoras

- **Detalles de un item por ID**
    
    https://api.mercadolibre.com/items/{ID_ITEM}

    Ejemplo:
    https://api.mercadolibre.com/items/MLA869900164

- **Descripción de un item por ID**
    
    https://api.mercadolibre.com/items/{ID_ITEM}/description 

    Ejemplo:
    https://api.mercadolibre.com/items/MLA869900164/description  
- **Ruta de categorías padres** 
    
    https://api.mercadolibre.com/categories/{IDcategory}   
    Ejemplo:
    https://api.mercadolibre.com/categories/MLA1648


</Br>

## Rúbrica de calificación
| Backend | Excelente trabajo  |Buen trabajo | Regular |  Mal  |  Puntuación del criterio |
|-------------------------------|-------------|---------------|--------------|--------------------------|---|
|  Reto realizar busqueda de items consumiendo API Mercado Libre  | **10 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> - Se Encontró la mejor solución ténica </br> - Se crea código claro facil de entender y mantener   | **6 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> </br> </br> </br>  </br>   </br>   </br>  |**4 puntos** </br> </br> - Se Resolvió el reto  </br> - El código esta ofuscado (difícil de entender) </br>  - No es la mejor solución técnica              |**0 puntos** </br> </br> No se logró resolver el reto        </br> </br>  </br> </br> </br> </br> </br>    |
|  Reto consumir Detalles de un item por ID con API Mercado Libre  | **10 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> - Se Encontró la mejor solución ténica </br> - Se crea código claro facil de entender y mantener   | **6 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> </br> </br> </br>  </br>   </br>   </br>  |**4 puntos** </br> </br> - Se Resolvió el reto  </br> - El código esta ofuscado (difícil de entender) </br>  - No es la mejor solución técnica              |**0 puntos** </br> </br> No se logró resolver el reto         </br> </br>  </br> </br> </br> </br> </br>    |
|  Reto consumir Descripción de un item por ID con API Mercado Libre  | **10 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> - Se Encontró la mejor solución ténica </br> - Se crea código claro facil de entender y mantener   | **6 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> </br> </br> </br>  </br>   </br>   </br>  |**4 puntos** </br> </br> - Se Resolvió el reto  </br> - El código esta ofuscado (difícil de entender) </br>  - No es la mejor solución técnica              |**0 puntos** </br> </br> No se logró resolver el reto         </br> </br>  </br> </br> </br> </br> </br>    |
|  Reto Ruta de categorías padres del API Mercado Libre (IDcategory)  | **10 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> - Se Encontró la mejor solución ténica </br> - Se crea código claro facil de entender y mantener   | **6 puntos** </br> </br> - Se Resolvió correctamente el reto desde el punto de vista del backend </br> </br> </br> </br>  </br>   </br>   </br>  |**4 puntos** </br> </br> - Se Resolvió el reto  </br> - El código esta ofuscado (difícil de entender) </br>  - No es la mejor solución técnica              |**0 puntos** </br> </br> No se logró resolver el reto         </br> </br>  </br> </br> </br> </br> </br>    |
|  Reto Realizar API propia para traer Items  | **60 puntos** </br> </br> - Se Crea una API propia que remplace la de de mercado libre </br> - Se Crea diagrama de Arquitectura y presentación explicando la Arquitectura de la aplicación total </br> - Se explica arquitectura de como su API podría escalar a millones de peticiones   | **40 puntos** </br> </br> - Se Crea una API propia que remplace la de de mercado libre </br> - Se Crea diagrama de Arquitectura y presentación explicando la Arquitectura de la aplicación total </br> </br> </br></br>|**20 puntos** </br> </br> - Se Crea una API propia que remplace la de de mercado libre </br>  </br> </br> </br></br> </br> </br>|**0 puntos** </br> </br> No se logró resolver el reto         </br> </br>  </br> </br> </br> </br> </br>  |