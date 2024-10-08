# Repositorio para aprender Polars
## Introducción al repositorio

Este repositorio tiene como objetivo proporcionar recursos y ejemplos para aprender a utilizar Polars, una poderosa librería de Python para el procesamiento y análisis de datos. Polars ofrece una interfaz intuitiva y eficiente para realizar operaciones de manipulación y transformación de datos, similar a la popular librería pandas.

Con Polars, podrás realizar tareas como filtrar, ordenar, agrupar y combinar conjuntos de datos de manera sencilla y eficiente. Además, Polars cuenta con una amplia gama de funciones y métodos que te permitirán realizar cálculos complejos y aplicar transformaciones avanzadas a tus datos.

En este repositorio encontrarás ejemplos de código, tutoriales y documentación detallada que te ayudarán a familiarizarte con la sintaxis y funcionalidades de Polars. Ya seas un principiante en el análisis de datos o un experto en Python, este repositorio te brindará los recursos necesarios para aprovechar al máximo la potencia de Polars en tus proyectos de análisis y procesamiento de datos.

¡Comienza a explorar y descubre todo lo que Polars tiene para ofrecerte!

## 1. Activa ambiente virtual con Conda

1. Abre una terminal o línea de comandos.
2. Navega hasta la ubicación del proyecto utilizando el comando `cd`.
3. Crea un nuevo ambiente virtual con Conda usando el siguiente comando:

    ```shell
    conda create --name polars python=3.11
    ```

4. Activa el ambiente virtual recién creado con el siguiente comando:

    ```shell
    conda activate polars
    ```

## 2. Activa ambiente virtual con venv

1. Abre una terminal o línea de comandos.
2. Navega hasta la ubicación del proyecto utilizando el comando `cd`.
3. Crea un nuevo ambiente virtual con venv usando el siguiente comando:

    ```shell
    python -m venv polars
    ```


4. Activa el ambiente virtual recién creado con el siguiente comando:

    - En Windows:

      ```shell
      polars\Scripts\activate
      ```

    - En macOS y Linux:

      ```shell
      source polars/bin/activate
      ```

## Instalación de quarto en ambiente virtual

Puedes instalar quarto en tu máquina
Link de instalación: https://quarto.org/docs/get-started/

Para conda puedes hacer: 

```shell
 conda install conda-forge::r-quarto 
```

Documentación de quarto para VSCode: https://quarto.org/docs/get-started/hello/vscode.html

## Instalación de Polars en el ambiente virtual

Una vez que hayas activado tu ambiente virtual, puedes instalar Polars utilizando el siguiente comando:

```shell
pip install polars
```

Este comando instalará la última versión estable de Polars en tu ambiente virtual. Una vez completada la instalación, estarás listo para comenzar a utilizar Polars en tus proyectos de análisis y procesamiento de datos.

Recuerda que si estás utilizando Conda, debes asegurarte de haber activado el ambiente virtual antes de ejecutar el comando de instalación.

¡Disfruta explorando las funcionalidades de Polars en tu ambiente virtual!

## Instalación de paquetes con requirements

Si deseas instalar los paquetes especificados en un archivo `requirements.txt`, puedes seguir los siguientes pasos:

1. Asegúrate de haber activado tu ambiente virtual con Conda o venv, como se menciona en los pasos anteriores.

2. Abre una terminal o línea de comandos.

3. Navega hasta la ubicación del proyecto utilizando el comando `cd`.

4. Ejecuta el siguiente comando para instalar los paquetes:

    ```shell
    pip install -r requirements.txt
    ```


# Para redenrizar *.qmd
Para renderizar archivos .qmd en la terminal, puedes utilizar el siguiente comando:

```shell
quarto render <nombre_archivo>.qmd
```

Asegúrate de reemplazar `<nombre_archivo>` con el nombre del archivo .qmd que deseas renderizar.

Recuerda que debes tener instalado Quarto en tu ambiente virtual antes de ejecutar este comando.

¡Espero que esto te sea útil! Si tienes alguna otra pregunta, no dudes en preguntar.
