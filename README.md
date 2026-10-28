# PetsCare

Proyecto de análisis y diseño de un sistema de gestión veterinaria. Reúne modelos UML, una especificación de caso de uso y una matriz de trabajo para documentar los procesos del negocio.

## Procesos modelados

- Gestión de citas y agenda de atención.
- Historial clínico, consultas, expedientes y recetas.
- Gestión de ventas de productos.
- Almacén, proveedores, órdenes de compra y suministro de productos.
- Entidades y actores como mascotas, clientes, veterinarios, empleados y administradores.

## Herramientas y formatos

- **IBM Rational Rhapsody:** proyecto y modelos UML en archivos `.rpyx`, `.rpwx` y `.sbsx`.
- **Word o un visor compatible:** documento de especificación en `.docx`.
- **Excel o un visor compatible:** matriz en `.xlsx`.

## Estructura

| Archivo o carpeta | Contenido |
| --- | --- |
| `Veterinaria_AV/Project/Project.rpyx` | Archivo principal del proyecto Rhapsody. |
| `Veterinaria_AV/Project/Project_rpy/` | Paquetes, entidades y modelos de los procesos. |
| `Veterinaria_AV/profiles/` | Perfiles de modelado de negocio, análisis y diseño. |
| `Especificación de Caso de Uso.docx` | Documento de especificación. |
| `Matriz_VET.xlsx` | Matriz de apoyo del proyecto. |

## Cómo revisar el proyecto

```bash
git clone https://github.com/thoonidev/PetsCare.git
cd PetsCare
```

1. Abre `Veterinaria_AV/Project/Project.rpyx` con una versión compatible de Rhapsody.
2. Conserva la estructura de carpetas para mantener las referencias a los modelos.
3. Si Rhapsody solicita localizar perfiles con rutas antiguas como `Z:\profiles\`, vincúlalos a las carpetas correspondientes dentro de `Veterinaria_AV/profiles/`.
4. Explora los paquetes de citas, historial clínico, ventas y almacén, y consulta los documentos complementarios.

## Alcance

El repositorio contiene los modelos y la documentación del sistema. No incluye una aplicación implementada, una base de datos desplegable ni comandos de ejecución de un servidor.
