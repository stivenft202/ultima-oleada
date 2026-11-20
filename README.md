# THE LAST WAVE (antes Última Oleada)

Shooter top-down de zombis por oleadas, en un solo archivo HTML. Ábrelo en el navegador y juega.

## Cómo jugar

Abre `ultima-oleada.html` en cualquier navegador moderno (Chrome, Edge, Firefox). No necesita servidor ni instalación.

Al arrancar sale el menú inicial: elige uno de los 5 personajes y pulsa JUGAR. Desde ahí también se llega a CONTROLES y OPCIONES.

## Controles (por defecto, todos reasignables en el menú de Controles)

- **WASD / Flechas** — Moverse
- **Ratón** — Apuntar
- **Clic izquierdo** — Disparar / Puñetazo
- **R** — Recargar
- **1–6** — Cambiar de ranura (barra rápida)
- **Rueda del ratón** — Cambiar de arma (llega hasta el puño)
- **Espacio** — Correr (gasta estamina)
- **Shift** — Dash (esquive rápido, invulnerable)
- **P o Esc** — Pausa
- **M** — Silenciar sonido
- **G** — Gore intenso / reducido
- **TAB** — Mostrar / ocultar el reloj del juego (también en OPCIONES)
- **Caps Lock** — Modo DIOS (activar / desactivar)
- **FIN (End)** — En modo DIOS, acaba la oleada al instante
- **Re-Pág / Av-Pág** — En modo DIOS, +$100 / -$100 de dinero
- **F12** — En modo DIOS, rueda de clima (sol, lluvia o nieve); pausa el juego
- **F11** — En modo DIOS, cambiar la hora y los minutos; pausa el juego (ESC cancela)

Mando Xbox: stick izquierdo mover, stick derecho apuntar, RT disparar, X recargar, B correr, Start pausa.

Para reasignar una tecla: en CONTROLES, haz clic en la tecla (parpadea) y pulsa la nueva. ESC o ENTER cancela y deja la anterior. Nunca se pueden usar ESC, ENTER ni F1–F12. Si la tecla ya la usa otra acción, se intercambian. Las teclas y el personaje se guardan en el navegador.

## El juego

- Oleadas de zombis cada vez más numerosas y rápidas.
- Dinero por cada zombi eliminado (más difícil = más dinero) y bonus por limpiar la oleada.
- Tienda entre oleadas: 4 armas (pistola, escopeta, subfusil, rifle), munición, botiquines, armadura y mejoras de armas (daño, cargador, recarga).
- Barra rápida de 6 ranuras: puño, pistola y lo que compres. Clic para usar, arrastrar para mover, los botiquines iguales se agrupan.
- Zombis: normal, corredor, hinchado, tanque, escupidor y jefe cada 5 oleadas.
- Barriles explosivos, cajas de madera y de metal rompibles (a puños o a balas), objetos que caen al morir.
- Récords guardados en el navegador (mejor oleada, más abatidos, más dinero).
- Modo DIOS (Caps Lock): invencible, munición infinita y sin estamina (siempre se corre). Con FIN se acaba la oleada.
- Clima aleatorio: soleado, lluvioso y con nieve (la nieve es la más escasa); cambia solo cada cierto tiempo. Con lluvia caen truenos y rayos (resplandor blanco + retumbo) y se oye la lluvia de fondo, bajito.
- Ciclo día/noche: cada día empieza a las 7:00 y 1 minuto de juego = 5 segundos reales (el reloj avanza despacio, sin distraer). La luz cambia: día claro, noche oscura, amanecer y atardecer cálidos.
- Reloj del juego en el HUD, debajo de los zombis que quedan (TAB lo muestra/oculta, también en OPCIONES), con icono de sol/luna y del clima.
- Modo DIOS: F12 abre la rueda de clima para elegir sol, lluvia o nieve cuando quieras; F11 abre el panel para cambiar la hora y los minutos (flechas, botones rápidos 07:00/12:00/18:00/00:00, ACEPTAR o CANCELAR). Ambas pausan el juego mientras están abiertas.
- 5 personajes elegibles al inicio (CLÁSICO, ROJO, RUBIO, GORRA, VIOLETA), con distinta ropa, pelo y color.

## Historial de versiones

| Versión | Fecha | Cambios |
|---|---|---|
| v2026-11-20e | 2026-11-20 | Lluvia continua (sin tandas): cada gota tiene su propia velocidad (420-620 px/s) y nace en una altura al azar de toda la pantalla; al cambiar el clima se siembra la pantalla entera (180 gotas / 150 copos). Spawn por acumulador (480 gotas/s) para que la densidad no dependa de los FPS. La nieve tenía el mismo problema y se corrigió igual. 322 pruebas. |
| v2026-11-20d | 2026-11-20 | Sin el texto del menú ("Oleadas, dinero y tienda"). Reloj lento: cada día empieza a las 7:00, 1 min de juego = 5 s reales; opción de mostrar/ocultar el reloj en OPCIONES (además de TAB). Modo DIOS: F12 abre la rueda de clima (sol/lluvia/nieve, pausa el juego) y F11 el panel para cambiar la hora y minutos (flechas + botones rápidos, ESC cancela). Truenos y rayos aleatorios con lluvia (resplandor blanco + rayo dibujado + retumbo) y sonido de lluvia de fondo bajito. 316 pruebas. |
| v2026-11-20c | 2026-11-20 | Renombrado a THE LAST WAVE. Sonidos reales de puño (punch1/punch2 de Stiven). Modo DIOS: Re-Pág +$100, Av-Pág -$100, sin estamina. Teclas reasignables (correr=Espacio, dash=Shift por defecto; captura con parpadeo, ESC/ENTER cancelan, F1-F12 prohibidas, intercambio si se repite, guardado). Clima aleatorio (sol/lluvia/nieve, nieve escasa). Ciclo día/noche (1 s = 10 min). Reloj con TAB debajo de los zombis que quedan. HUD del arma sin fondo negro ni "RESERVA" (solo icono de bala, más grande). Sin textos de controles in-game. Menú inicial con JUGAR/CONTROLES/OPCIONES/SALIR + selector de 5 personajes. Icono del puño rehecho. 285 pruebas. |
| v2026-11-20b | 2026-11-20 | Jefe cada 5 oleadas (el de la captura era el jefe en la oleada 3, por el cambio a cada 3); tanque ahora azul acero con placa (antes morado, se confundía con el jefe). Sonido de subfusil recortado a un disparo de 0,18 s + pool de 4 audios (antes se cortaba). Sonidos de puño (2, se alternan, suenan siempre). Explosión de barril con fuego y humo; daño por explosión radio 70 → 80 px. Cajas sueltan astillas/esquirlas/chispas. Rueda del ratón llega al puño. 225 pruebas. |
| v2026-11-20 | 2026-11-20 | Modo DIOS (Caps Lock, invencible, munición infinita, FIN acaba la oleada, indicador GOD MODE). Puño cuerpo a cuerpo en la ranura 0, barra de 6 ranuras. Durabilidad: caja de madera 2, metal 4, barril 5. Sonidos reales de pistola, escopeta y subfusil + sin munición. Más dinero por zombi según dificultad. 207 pruebas. |
| v2026-11-19c | 2026-11-19 | Tienda compacta (cabe a lo alto), jefe cada 3 oleadas, mapa pradera muy abierto. 152 pruebas. |
| v2026-11-19b | 2026-11-19 | 7 mejoras: tanque, escupidor y jefe, drops, barriles y cajas, récords, mejoras de armas, dash con Espacio, rachas. 147 pruebas. |
| v2026-11-19a | 2026-11-19 | Oleadas, tienda con pausa, 4 armas, munición comprable, barra rápida, menú de pausa, dificultad. |
