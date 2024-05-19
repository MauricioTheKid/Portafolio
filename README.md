# Portafolio de Programas en Lenguaje Ensamblador

Este repositorio contiene tres programas en lenguaje ensamblador para realizar operaciones matemáticas básicas. Cada programa está escrito para diferentes registros (16 bits, 8 bits, y 32 bits).

## Programas

1. **Resta de Tres Enteros**: Utiliza registros de 16 bits.
2. **Multiplicación de Dos Números Enteros**: Utiliza registros de 8 bits.
3. **División de Dos Números Enteros**: Utiliza registros de 32 bits.

## Compilación y Ejecución

### Requisitos

- NASM (Netwide Assembler)
- Un sistema operativo Linux

### Pasos

1. **Clonar el repositorio**:

    ```sh
    git clone https://github.com/MauricioTheKid/Portafolio.git
    cd Portafolio
    ```

2. **Compilar el programa**:

    ```sh
    nasm -f elf32 programas.asm -o programas.o
    ld -m elf_i386 programas.o -o programas
    ```

3. **Ejecutar el programa**:

    ```sh
    ./programas
    ```

## Notas

- El primer programa realiza la resta de tres enteros utilizando registros de 16 bits.
- El segundo programa multiplica dos números enteros utilizando registros de 8 bits.
- El tercer programa divide dos números enteros utilizando registros de 32 bits.
- Asegúrate de ingresar valores válidos según las indicaciones en la consola.

## Autor

- **José Mauricio Chavarría González**
- **Carnet: CG 92088**
