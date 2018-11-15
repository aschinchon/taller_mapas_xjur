# Taller de Mapas Interactivos XjuR (22/11/2018)

Material del taller de mapas interactivos con Leaflet de las X Jornadas de usuarios de R en Murcia 2018

<img src="img\logo_xjur.png" width="25%" height="25%">

### Prerequisitos

Para seguir el taller se deben instalar los siguientes paquetes:

```
install.packages("opencage")
install.packages("leaflet")
install.packages("tidyverse")
install.packages("htmlwidgets")
install.packages("rworldmap")
install.packages("sp")
install.packages("sf", dep=T)
```

También hay que crear una cuenta gratuita de opencage [aquí](https://opencagedata.com/pricing). Después, hay que guardar el API Key que se obtenga en el .Renviron con el siguiente código:

```
cat("OPENCAGE_KEY=COPIA-AQUI-TU-API-KEY\n", file = file.path(normalizePath("~/"), ".Renviron"), append = TRUE)
```
## Authors

* **Antonio Sánchez Chinchón** - [@aschinchon](https://twitter.com/aschinchon)

