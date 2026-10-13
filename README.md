# 42Zeus

## Resumen

42zeus es una herramienta automatizada de pruebas diseñada para ayudar a encontrar problemas en el `libft` de 42.

## Aviso legal

El propósito principal del tester es utilizarse como medida de protección frente a casos de prueba que los estudiantes suelen pasar por alto, o como último recurso para problemas difíciles de diagnosticar. Sin embargo, depender demasiado de este o de cualquier otro tester es perjudicial para el proceso de aprendizaje y resta valor a la experiencia 42. Cuando desarrolles un proyecto, primero debes confiar en tus propias pruebas y comprobaciones de errores, en segundo lugar en tus compañeros y, por último, en una herramienta de prueba.

Este tester tampoco está pensado para usarse al evaluar el trabajo de otros estudiantes. Las evaluaciones deben asegurar que la persona evaluada comprende los conceptos clave del proyecto, puede explicar cómo funciona su propio código y defender las decisiones que tomó. La persona evaluada también debe poder probar su propio código.

En última instancia, 42zeus es solo una herramienta; si se usa para aportar valor a tu experiencia o se usa incorrectamente depende de ti.

## Instalación y actualización

42Zeus es compatible con sistemas Mac y Linux (probado en Ubuntu 22.04). Está pensado funcionar en los ordenadores utilizados en las instalaciones de 42, ya que está construido con las mismas tecnologías que utilizan la mayoría de los proyectos oficiales.

Ejecutando el siguiente comando se instalará 42zeus para el usuario actual:

	curl https://raw.githubusercontent.com/ander-vieira/42zeus/master/setup | bash

Este comando instalará 42zeus en el directorio ~/42zeus dentro del directorio personal del usuario. Si este directorio ya está en uso debido a una instalación previa, tendrás que eliminar esta carpeta manualmente antes de instalar. Si lo estás usando para otros fines, considera renombrar el directorio para permitir la instalación de 42zeus.

Esto también configurará los alias necesarios para ejecutar el comando "zeus" en zsh y bash.

Para actualizar una instalación existente a una versión más reciente, simplemente ejecuta este comando:

	zeus --update

Esto descargará la última versión del repositorio.

## Uso

42zeus detectará automáticamente el proyecto que necesita probarse. Por lo tanto, para ejecutar el tester en el directorio actual, puedes hacerlo directamente con:

	zeus

Alternativamente, puedes especificar el directorio que contiene el proyecto a probar pasándolo como argumento. Por ejemplo, para probar un proyecto dentro del directorio projects/libft/:

	zeus projects/libft/
