# Supaterm Emilio 1.0.1

Base: Supaterm 26.4.0 (build 40), aplicado después de los parches de Emilio 1.0.0.

Los cambios están separados por intención:

1. `0001-about-emilio-build-identifier.patch`: muestra `EMILIO 1.0.1` junto a la versión oficial en About.
2. `0002-scroll-alternate-screen-with-scrollback.patch`: conserva el desplazamiento visual cuando una aplicación activa DEC 1007 pero la pantalla alternativa ya tiene scrollback.

El segundo parche se aplica dentro del submódulo `apps/mac/ThirdParty/ghostty`.

Las personalizaciones de empaquetado —icono EMILIO, tema Carbonfox modificado y actualizaciones automáticas desactivadas— no forman parte de estos parches de código.
