En un archivo de texto `respuestas.md`:

1. Escriban qué esperan de cada uno de los pasos
   1) El preprocesador declarará todas las funciones incluidas en las librerias que se incluyeron.
   2) La compilacion I pasa todo el código a lenguaje asssmbler.
   3) La compilación II pasa a lenguaje de máquina los archivos objetos que luego se linkearán.
   4) El linkeo lo que hará es vincular los objetos generados en el paso anterior y además permite ejecutar el conjunto
      (esto también estará en lenguaje de máquina). 
2. ¿Qué agregó el preprocesador?
   El preprocesador lo que hace es declarar todas las funciones que esten definidas en las librerias o macros
   que incluyamos en nuestro programa.
3. Identificar en la rutina de assembler las funciones
   Las funciones en la rutina de assembler son la funciones main y add_numbers que aparecen detras de @function.
   Otra función en la rutina assembler es 
4. Explicar qué quieren decir los símbolos que se crean en el objeto
   T (texto código ejecutable) significa que el simbolo está en la sección de código y es global o externo.
   U significa que el simbolo es de tipo indefinido (Undefined) y externo o global.
5. ¿En qué se diferencian los símbolos del objeto y del ejecutable?
   La diferencia entre los símbolos del objeto y el ejecutable es que los símbolos del ejecutable son mucho más
   numerosos que en el objeto. 
(siéntanse libres, si quieren, de usar la sintaxis markdown. no hace falta)
