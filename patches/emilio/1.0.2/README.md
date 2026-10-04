# Supaterm Emilio 1.0.2

Base: Supaterm 26.4.0 (build 40), aplicado después de Emilio 1.0.1.

Los cambios están separados por intención:

1. `0001-make-emilio-build-unmistakable.patch`: muestra siempre `EMILIO 1.0.2`, cambia el nombre visible a `Supaterm EMILIO` y elimina `SUFeedURL`.
2. `0002-prefer-local-scrollback-over-mouse-reporting.patch`: hace que la rueda vertical desplace el historial local antes de que `screen`, `tmux` u otra aplicación pueda consumirla como reporte de ratón.

El segundo parche se aplica dentro del submódulo `apps/mac/ThirdParty/ghostty`.

El paquete final conserva el icono EMILIO, Carbonfox modificado, las actualizaciones automáticas desactivadas y la firma ad hoc.
