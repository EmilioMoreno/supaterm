# Supaterm Emilio 1.0.0

Base: Supaterm 26.4.0 (build 40).

Los cambios están separados por intención para poder revisarlos y convertirlos en commits o pull requests independientes:

1. `0001-preserve-click-while-focusing-pane.patch`: el primer clic enfoca el panel y sigue llegando al terminal.
2. `0002-alternate-screen-scrollback.patch`: conserva scrollback en la pantalla alternativa y evita convertir el scroll en flechas por defecto.
3. `0003-two-point-pane-divider.patch`: aumenta el divisor visible de 1 a 2 puntos sin cambiar su zona total de arrastre.

Las personalizaciones de empaquetado —icono EMILIO, tema Carbonfox modificado y actualizaciones automáticas desactivadas— no forman parte de estos parches de código.
