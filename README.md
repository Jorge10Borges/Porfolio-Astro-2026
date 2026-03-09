# QRV+

Sitio oficial de QRV+ — https://qrvplus.com

Este repositorio contiene la web estática del proyecto QRV+ (anteriormente "QR Salvavidas").

## Comandos

Ejecuta desde la raíz del proyecto:

```bash
npm install
npm run dev      # Desarrollo local
npm run build    # Generar build de producción
npm run preview  # Previsualizar build
```

## Despliegue

El sitio está preparado para desplegarse en GitHub Pages usando el archivo `CNAME` con el dominio `qrvplus.com`. También es compatible con despliegue en Vercel o Netlify.

## Estructura

```
public/
src/
	Components/
	Layouts/
	pages/
package.json
README.md
CNAME
```

## Notas

- Actualizar metadata, Open Graph y assets de marca cuando estén disponibles.
- Revocar cualquier token compartido públicamente y asegurar integraciones externas.

Para más cambios, abre un issue o PR.
