# futbolDeCabeza

Juego de fútbol arcade con cabezones, hecho en Python (pygame) para el trabajo práctico de Programación Concurrente (UNLaM). Tiene modo local y modo online, con efectos y poderes durante el partido.

- Sitio y modo online: https://futbol.timecore.com.ar

## Descargas

Las 3 descargas están en la sección **[Releases](../../releases/latest)** de este repositorio. Elegí el archivo que corresponda a tu equipo.

| Archivo | Para qué |
|---|---|
| `FutbolDeCabeza-windows-gpu.zip` | Windows 10/11 con placa NVIDIA |
| `FutbolDeCabeza-windows-cpu.zip` | Windows 10/11, cualquier equipo |
| `FutbolDeCabeza-mac-arm64.zip` | macOS Apple Silicon (M1 o superior) |

Los hashes están en `SHA256SUMS.txt` (versión actual: **v1.0**).

## Requisitos

- Windows o macOS (la versión de Mac es para Apple Silicon: M1 o superior).
- Para jugar online hace falta conexión a internet.
- El modo OPTIMIZADO anda bien en cualquier equipo; el modo FULL usa efectos por CPU/GPU y es más exigente (en Mac, con CPU, es poco jugable en los efectos pesados).

## Abrir la app de macOS (sin firma)

La app no está firmada ni notarizada, así que macOS la bloquea la primera vez:

1. Descomprimí el `.zip` y movela a Aplicaciones (opcional).
2. Clic derecho sobre `FutbolDeCabeza.app` > **Abrir** > **Abrir**.
3. Si no aparece esa opción: **Ajustes del Sistema > Privacidad y seguridad**, bajá hasta el aviso de la app y tocá **Abrir igualmente**.

Solo hace falta la primera vez.
