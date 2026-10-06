# SIDEBFLMS Downloader · Releases

Solo binarios de cada versión publicada de [SIDEBFLMS Downloader](https://github.com/sidebflms/sideb-downloader) (repo privado) -- sin código fuente aquí.

Existe para que la propia app pueda comprobar si hay una versión nueva sin necesitar acceso al repo privado ni ningún token: lee la API pública de GitHub (`GET /repos/sidebflms/sideb-downloader-releases/releases/latest`) y, si hay una versión más nueva y la licencia la cubre, ofrece abrir la descarga (`.dmg` en Mac, `.zip` en Windows). La app **no se sustituye sola**: se abre la descarga y se arrastra a Aplicaciones, como en DIT.

Las releases se publican con `tools/publicar_release.py` del repo privado. Requiere licencia: sin una licencia válida para tu equipo la app no descarga.
