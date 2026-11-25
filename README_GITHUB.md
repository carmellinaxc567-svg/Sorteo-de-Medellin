# Sorteo de Medellín — página web

Esta carpeta está preparada para publicar la página como sitio estático en **GitHub Pages**. Incluye el diseño del sorteo, QR y datos de pago actualizados, además del panel administrativo.

## Abrir el panel administrativo

En la página publicada, añade `#admin` al final de la dirección. Ejemplo:

`https://TU-USUARIO.github.io/TU-REPOSITORIO/#admin`

Pulsa **Administrar**. Desde el panel puedes editar los datos del sorteo, premios, resultados, números vendidos, número de Nequi/llave y cambiar el QR. Al terminar, pulsa **Descargar página**.

### Publicar los cambios del panel

GitHub Pages es alojamiento estático: el panel no puede escribir directamente en GitHub ni guardar cambios en el servidor. Después de descargar el nuevo `index.html`:

1. Abre tu repositorio de GitHub.
2. Entra en el archivo `index.html`.
3. Pulsa el lápiz **Edit** o elimina el archivo y sube el nuevo `index.html` descargado.
4. Guarda los cambios con **Commit changes**.
5. Espera unos minutos y recarga tu página publicada.

## Publicar por primera vez en GitHub Pages

1. Inicia sesión en [GitHub](https://github.com/) y pulsa **New repository**.
2. Pon un nombre, por ejemplo `sorteo-medellin`; selecciona **Public** y crea el repositorio.
3. En el repositorio, pulsa **Add file → Upload files**.
4. Descomprime este ZIP en tu computador y sube los archivos que contiene directamente a la raíz del repositorio. Asegúrate de que `index.html` quede en la raíz, no dentro de otra carpeta.
5. Pulsa **Commit changes**.
6. Ve a **Settings → Pages**.
7. En **Build and deployment**, selecciona **Deploy from a branch**.
8. Elige la rama `main` y la carpeta `/ (root)`, y pulsa **Save**.
9. Espera a que GitHub publique el sitio. La URL será parecida a `https://TU-USUARIO.github.io/sorteo-medellin/`. GitHub también mostrará la dirección exacta en **Settings → Pages**.

## Importante sobre seguridad y pagos

- `#admin` solo oculta/abre el panel; **no es una contraseña ni un sistema de acceso seguro**. Cualquier persona que conozca la dirección puede abrirlo y descargar una versión modificada. No introduzcas datos privados.
- No hay guardado automático ni base de datos. Los cambios se publican reemplazando `index.html` y haciendo un commit.
- El panel administra la información visible de la página; no confirma pagos ni verifica automáticamente comprobantes. Confirma cada pago por tu canal habitual.
- Revisa el QR y el número de pago antes de publicar.
