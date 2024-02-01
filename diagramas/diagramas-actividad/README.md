<div style="text-align: center;"> 

# Diagramas de Actividad

</div> 

<div style="text-align: justify;"> 

En este documento podremos ver los Diagramas de Actividad sobre los [casos de uso](https://github.com/PeterMartEsc/proyecto_biblioteca/tree/main/diagramas/diagrama-casos-uso)

</div>

## Caso de Uso 1

<div align="center">

```mermaid
graph TD;
    Inicio --> BuscarLibro;
    BuscarLibro ----> PorTitulo;
    BuscarLibro ----> PorAutor;
    BuscarLibro ----> PorCategoría;
    PorTitulo --> Fin;
    PorAutor --> Fin;
    PorCategoría --> Fin;
```

</div>

## Caso de Uso 2

<div align="center">

```mermaid
graph TD;
    Inicio --> SeleccionarLibroPrestar;
    SeleccionarLibroPrestar --> Fin;
```

</div>

## Caso de Uso 3

<div align="center">

```mermaid
graph TD;
    Inicio --> DevuelveLibroPrestado;
    DevuelveLibroPrestado --> Fin;
```

</div>

## Caso de Uso 4

<div align="center">

```mermaid
graph TD;
    Inicio --> DejaComentarioEnLibro;
    DejaComentarioEnLibro --> Fin;
```

</div>

## Caso de Uso 5

<div align="center">

```mermaid
graph TD;
    Inicio --> SeleccionarCategoría;
    SeleccionarCategoría --> VerListaLibros;
    VerListaLibros --> Fin;
```

</div>

## Caso de Uso 6

<div align="center">

```mermaid
graph TD;
    Inicio --> RegistrarNuevoUsuarioEnSistema;
    RegistrarNuevoUsuarioEnSistema --> Fin;
```

</div>

## Caso de Uso 7

<div align="center">

```mermaid
graph TD;
    Inicio --> AgregarNuevoLibroAlSistema;
    AgregarNuevoLibroAlSistema --> Fin;
```

</div>

## Caso de Uso 8

<div align="center">

```mermaid
graph TD;
    Inicio --> RealizarPrestamoUsuario;
    RealizarPrestamoUsuario --> Fin;
```

</div>

## Caso de Uso 9

<div align="center">

```mermaid
graph TD;
    Inicio --> ProcesarDevolucionLibro;
    ProcesarDevolucionLibro --> Fin;
```

</div>

## Caso de Uso 10

<div align="center">

```mermaid
graph TD;
    Inicio --> GestionarReservaLibros;
    GestionarReservaLibros ----> VisualizarInformación;
    GestionarReservaLibros ----> ModificarInformación;
    VisualizarInformación ---> Fin;
    ModificarInformación ---> Fin;
```

</div>