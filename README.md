# 🌶️ SALUD Y ENFERMEDADES RELACIOANDAS CON LA DIETA [🍌](https://emojipedia.org/shortcodes)

> Trabajo realizado por;
>
> -   **Oier Zuñiga** ([ozt1001\@alu.ubu.es](mailto:ozt1001@alu.ubu.es){.email})[📩](https://emojipedia.org/shortcodes)
> -   **Diego Ramirez** ([drs1003\@alu.ubu.es](mailto:drs1003@alu.ubu.es){.email})[📩](https://emojipedia.org/shortcodes)
> -   3º GIS. / [Fuentes de datos biomédicas y webs semanticas GIS.](https://ubuvirtual.ubu.es/course/view.php?id=14468)[🎓](https://emojipedia.org/shortcodes)

![🥝](Fotos/Portada.jpg)

### ¿Sobre qué trata nuestra investigación? [🔎](https://emojipedia.org/shortcodes)

En este proyecto, intentaremos relacionar y buscar información sobre algunas enfermedades vinculadas con la dieta, como la **obesidad** o la **diabetes tipo 2** entre otras como puede ser la **hipertensión** o **enfermedades cardiovasculares**.

Para ello, proporcionaremos datos y estadísticas relacionadas con ambas enfermedades, junto con otros factores que pueden favorecer su aparición.

Nos centraremos en **3 OBJETIVOS PRINCIPALES.**

## OBJETIVOS PRINCIPALES [📋](https://emojipedia.org/shortcodes)

### **Objetivo 1**

-   Relación entre Diabetes e Hipertensión.

### **Objetivo 2**

-   Relación entre la mortalidad por diabetes y cantidad de establecimientos de comida rápida.

### **Objetivo 3**

-   Comparar la mortalidad por enfermedades cardiovasculares entre la Peninsula y las islas canarias

![💪](Fotos/DietaDeporte.jpg)

## Explicación de los objetivos

> En estos objetivos, la idea principal es generar unos graficos comparativos con distintas variables y datos las cuales intentaremos explicar. Estos graficos los hemos generado usando el paquete de ***GGplot2***
>
> A la hora de revisar las graficas, os encontrareís con codigo como este para su realización, por si os es de utilidad;
>
> **EJEMPLO CODIGO DEL GRAFICO 3**
>
> ```{r}
>   grafico <- ggplot(nueva_tabla_filtrada, aes(x = Year, y = Value, fill = Territorio)) +
> geom_bar(stat = "identity", position = "dodge") +
> labs(title = "Gráfico de barras por Territorio",
> x = "Año",
> y = "Valor") +
> scale_fill_manual(values = c("ES" = "red", "ES70" = "green")) +
> theme_minimal()
> >
> print(grafico)
>  
> ```

### **Explicación Objetivo 1**;

En este primer objetivo...

### **Explicación Objetivo 2**;

Para este segundo objetivo hemos buscado en diferentes bases de datos las cuales nos pudieran proporcionar alguna información sobre si existe alguna relación entre la aparición y mortalidad por diabetes tipo 2 y la cantidad de establecimientos de *Fastfood* que encontramos. En este caso estos datos son del estado de Allegheny en E.E.U.U.

### **Explicación objetivo 3**;

Por ultimo, en este tercer objetivo hemos comparado la tasa de mortalidad por enfermedades cardiovasculares. Hemos comparado la tasa de mortalidad desde el año 2010 hasta el 2021, pero, hemos realizado la comparativa también entre la peninsula y las islas canarias.

## Bibliografía [📰](https://emojipedia.org/shortcodes)

-   Aquí os dejamos un lista con los links y los sitios web que hemos consultado para llevar a cabo el trabajo.

| **Información**         | **Links** |
|:------------------------|:----------|
| Cardiovascular          | CSV       |
| Diabetes e Hipertensión | CSV       |
| Fasfood                 | CSV       |
| Mortalidad              | CSV       |

## FINAL

Esperamos que este ReadMe os sea de utilidad para entender un poco aunque sea sobre que trata nuestro trabajo de investigación y como lo hemos llevado a cabo.

De todoso modos, cualquier consulta que se tenga, al inicio de este documento teneis los e-mails de ambos creadores ~~que en caso de que tengais alguna consulta intentaremos resolverla. (No escribais porfavor 😭 )~~

**UN SALUDO Y MUCHAS GRACIAS POR APOYAR NUESTRO PROYECTO**

![**FIN**](Fotos/Despedida.jpg)
