# Setup - NextgenPM.ES Web

## Información Local

Aunque esto es un respaldo en GitHub, aquí va info si alguien necesita setup local:

### Requisitos
- WordPress 6.0+
- Elementor Pro
- Node.js 18+ (para build tools si aplica)
- pnpm o npm

### Pasos
1. Clona: `git clone https://github.com/agustinasanguinetti89-cmyk/nextgenpm.es.git`
2. Copia `.env.example` → `.env`
3. Configura DB y credenciales
4. `pnpm install` (si hay dependencias)
5. WordPress setup normal

## Archivos Críticos

- `wp-config.php` - NO subir a GitHub (en .gitignore)
- `wp-content/uploads/` - NO subir (en .gitignore)
- Plugins activos - Documentar en `plugins.txt`

---

Ver [README.md](../README.md) para flujo general.
