# Colección: 40 scripts independientes para Termux

Colección educativa para Termux en Android, sin root. Cada archivo `.sh` funciona de forma independiente.

## Instalación
1. Extrae el ZIP.
2. Copia la carpeta `scripts` a `$HOME/scripts` en Termux.
3. Ejecuta `chmod +x ~/scripts/*.sh`.
4. Ejecuta un script, por ejemplo: `bash ~/scripts/01_diagnostico.sh`.

También puedes ejecutar directamente los scripts desde la carpeta donde los extrajiste.

## Dependencias opcionales
- `curl`: pruebas HTTPS, descarga y consulta de IP pública.
- `python`: servidor HTTP local.
- `dnsutils`: `nslookup`.
- `inetutils`: `ping`.
- `iproute2`: `ip` y `ss`.
- `termux-api` y la app Termux:API: lectura de batería.

Instalación de utilidades: `pkg install curl python dnsutils inetutils iproute2 termux-api`

## Seguridad
- No requieren root.
- Los scripts de actualización, instalación, limpieza y copia de seguridad piden confirmación.
- `26_servidor_http_local.sh` escucha únicamente en `127.0.0.1`, no en la red Wi-Fi.
- No ejecutes scripts que no entiendas. Revisa el contenido antes de usarlos.
- Android puede limitar información de procesos, memoria, batería y red.

## Aplicaciones que debes tener instaladas 

- Termux
- Termux API