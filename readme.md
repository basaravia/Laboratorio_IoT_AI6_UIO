# Guía de Laboratorio para Introducción al IoT - Saturdays AI Quito 2020

### Esta guía recopila todos los conocimientos en un ejercicio práctico empleando la máquina virtual facilitada a lo largo del curso de __IoT__.

<center>
 <img src="img/glootie.png" height="300px" width="300px"></img>
</center>

---

Conocimientos a aplicar: 
- Conexiones remotas a Raspberry pi
- Uso de Raspbian OS a través de `bash`
- Manejo de `GPIO/GPIOEmulator`
- Uso de la clase `time` y `threading`en python
- Manejo de protocolo `UART` a través de pyserial (empleando SOCAT para simular puertos seriales)
- Publicacion y suscripcion de mensajes a través de `MQTT`
- Uso de `Node-RED` como interfaz de aplicación IoT
- Despliegue de información de `MQTT` a Cloud

---
### La entrega de esta guia debe realizar a través de la plataforma `Schoology` de la Comunidad, con los siguientes entregables:

- `lab_Apellido_Nombre.ipynb` (cuaderno de jupyter)
- `node_Apellido_Nombre.txt` (archivo de texto plano) con los flujos exportados desde `Node-RED` (Como exportar flujos en Node-RED: https://randomnerdtutorials.com/exporting-and-backing-up-your-node-red-nodes/)
- `bash_Apellido_Nombre.txt` con el historico de comandos bash empleados en el laboratorio, ejecutando el siguiente comando en la terminal de la Raspberry Pi (simulado o real):

```bash
history > bash_<Apellido>_<Nombre>.txt
```

### Todo esto en una carpeta comprimida en formato .ZIP con el nombre `Apellido_Nombre_AI6_IoT_2020.zip`
---

<center>
 <img src="img/ai6UIO.png" height="300px" width="300px"></img>
</center>

___

[![Open In Colab](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alexander-saravia) 


> Desarrollo: Alexander Saravia

> email: alexandersaravia@protonmail.com 

<center>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><center><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /> </center> </a> <br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>
</center>
