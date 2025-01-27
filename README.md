# CAPTCHA BREAKER

Este código aprovecha la opcion de dictado del CAPTCHA v2 y la explota para que un robot tenga acceso a una página.

---

## Pasos para corre el programa

Primero, debemos instalar todas las librerias para python. En el documento __requirementes.txt__ ya vienen todas listas ser instaladas con el comando:

  - ``pip install -r requirements.txt`` 

Una vez instaladas las librerias, en la carpeta __webdriver__ ya vienen dos versiones de Chromedriver, una es para windows y la otra para MacOS. En caso de tener MacOS y que la version que viene dentro de la carpeta le cause errores deberá seguir el procedimiento a continuación (deberá tener Brew previamente instalado):

  - ``brew install --cask chromedriver`` (Debe tener instalada la ultima versión de Chrome instalada)

Teniendo instalado esto ahora deberá instalar ffmpeg con pip y en su sistema.

---

### MacOS

Para instalar ffmpeg deberá ejecutar los siguientes comandos:

- ``pip install ffmpeg``
- ``brew install ffmpeg``

---

### Linux (apt-get)

Para instalar ffmpeg deberá ejecutar los siguientes comandos:

- ``pip install ffmpeg``
- ``sudo apt-get install ffmpeg``

---

Una vez finalizado estos pasos verifique que la ruta donde se encuentra el Chromedriver este correcta.

Una vez finalizados estos pasos deberá correr el codigo con el comando:

- ``python recaptcha_solver.py``

Deje que se ejecute todo automaticamente.
