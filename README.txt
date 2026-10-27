NEO - ENLACES PERMANENTES CON GITHUB PAGES

Repositorio previsto:
https://github.com/neoneolap-ai/neolap-links

GitHub Pages previsto:
https://neoneolap-ai.github.io/neolap-links/

ARCHIVOS:
- config.js       -> única URL de Apps Script que se cambia cuando haya nueva implementación
- catalogo.html   -> redirige catalogo.html?v=TOKEN a Apps Script ?v=TOKEN
- portal.html     -> redirige portal.html?u=TOKEN a Apps Script ?modo=portal&u=TOKEN
- index.html      -> página neutra

SEGURIDAD:
- No guardar contraseñas.
- No guardar sesiones s= en GitHub.
- No guardar una lista usuarios.js con todos los tokens.
- Ventas, Inventario, Trabajos y Publicidad IA siguen protegidos por Apps Script.

PASO 1:
Editar config.js y reemplazar PEGA_AQUI_TU_IMPLEMENTACION por la URL /exec actual.

PASO 2:
Subir estos 4 archivos a la raíz del repositorio neolap-links y activar GitHub Pages desde la rama main / root.

PASO 3:
En Apps Script reemplazar Código.gs por Code_V9.38.2_GITHUB_LINKS_PERMANENTES.gs y publicar nueva versión.

PASO 4:
En la hoja, usar el menú Catálogo -> Reparar usuarios y enlaces para regenerar Enlace portal y Enlace catálogo.

RESULTADO POR USUARIO:
Catálogo: https://neoneolap-ai.github.io/neolap-links/catalogo.html?v=TOKEN
Portal:   https://neoneolap-ai.github.io/neolap-links/portal.html?u=TOKEN
