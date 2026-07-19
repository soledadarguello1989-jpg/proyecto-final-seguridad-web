# Diagrama: Proceso de entrada y validación de usuario

```mermaid
flowchart TD
    A[Inicio] --> B[Usuario ingresa login y contraseña]
    B --> C[Sistema valida usuario y contraseña]
    C --> D{¿Datos correctos?}
    D -- No --> E[Muestra mensaje de error]
    E --> B
    D -- Sí --> F[Envía código al teléfono móvil]
    F --> G[Usuario ingresa código recibido]
    G --> H[Sistema valida código]
    H --> I{¿Código correcto?}
    I -- No --> J[Rechaza acceso]
    J --> G
    I -- Sí --> K[Permite acceso al sistema transaccional]
    K --> L[Fin]
