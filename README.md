# Api_LibroReclamos
Api de reclamos

configurar en IIS
agregar un agregar aplicacion en la raiz de default web site debe llevar este mismo nombre Alias: Api_LibroReclamos
![image](https://github.com/user-attachments/assets/7a3d2bac-2515-436e-9b27-609a1e655634)


agregar un grupo de aplicaciones IIS
se tiene q llamar asi
Api_LibroReclamos
![image](https://github.com/user-attachments/assets/970855ee-8a7b-4e0f-927b-367439b2d125)

crear las carpeta que debe llamarse Api_LibroReclamos y colocar el compilado q esta github q se llama Api_LibroReclamos
agregar ruta fisica en donde va estar la Api
y seleccionar el grupo de aplicaciones creado

![image](https://github.com/user-attachments/assets/fe7087d7-0b9d-41e7-9daa-3bd39671f0e2)

luego examinar para probar deberia salir
![image](https://github.com/user-attachments/assets/adca78ba-81a7-41d7-9b17-0fd6550f1ff5)

luego agregar swagger y enter
http://localhost/Api_LibroReclamos/swagger/index.html

/api/Reclamaciones/Monitoreo dar clic try it out
{
  "cpercodigo": "7000090106",
  "cPerJuridica": "1000098770",
  "dFechaInicio": "2024-09-01",
  "dFechaFin": "2024-10-01",
  "cTipoReclamo": "0",
  "cEstadoReclamo": "0",
  "pagination": {
    "pageIndex": 1,
    "pageSize": 10,
    "totalRows": 0
  }
}
