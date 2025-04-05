# 00-Hello

Este directorio contiene un programa básico de "Hello, World!" en C.

## Información del compilador

### A. Compilador seleccionado

El compilador utilizado para este proyecto es **GCC 14.2.0**.

### B. Versión del compilador

La versión del compilador utilizada es **GCC 14.2.0**.  
Se verificó la versión ejecutando el siguiente comando en la terminal:

```bash
gcc --version
```

### C. Versión del lenguaje de programación C que el compilador compila

La versión del compilador **GCC 14.2.0** soporta múltiples versiones del estándar del lenguaje C. Entre ellas:

- C89
- C99
- C11
- C17
- **C23** _compilador seleccionado_

Para especificar la versión del estándar del lenguaje C que deseas utilizar, puedes usar la opción `-std` al compilar. Por ejemplo:

```bash
// En la carpeta del proyecto
gcc -std=c23 -o hello hello.c
```

### D. Ejecución del programa

Una vez compilado, puedes ejecutar el programa con el siguiente comando:

```bash
./hello
```

Consulta la [documentación oficial de GCC](https://gcc.gnu.org/) para más detalles sobre las versiones soportadas.