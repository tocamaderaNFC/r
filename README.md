# Placas Toca Madera NFC (`links.json`)

Cada placa abre `https://tocamaderanfc.github.io/r/?id=NÚMERO` y redirige al link de ese número.
Número vacío = "Soporte #N disponible para activación".

| Rango | Uso |
|---|---|
| 001–099 | Reseñas de Google (Colonia, placas chicas genéricas) |
| 101–199 | Pagos personalizados Colonia (página en repo `colonia`) |
| 201–299 | Pagos genéricos Buenos Aires (página en repo `buenos-aires`) |

**Bloqueada, no tocar:** 003 = pagos The Crown Barber (Buenos Aires).

Volver atrás: `git revert <commit>` o restaurar la copia con fecha guardada antes de cada cambio.
