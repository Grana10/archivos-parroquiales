# 📜 Buscador de Archivos Parroquiales de España

[![Licencia: CC BY-NC-ND 4.0](https://img.shields.io/badge/Licencia-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.es)
![Parroquias](https://img.shields.io/badge/parroquias-18.290-1E4D3C)
![Diócesis](https://img.shields.io/badge/diócesis-66-1E4D3C)

**Un único buscador para localizar los archivos parroquiales de toda España.**

Hasta ahora, para saber desde qué año se conservan los libros sacramentales de una
parroquia (bautismos, matrimonios, defunciones, confirmaciones y fábrica) había que
ir a mano por la *Guía de los Archivos de la Iglesia en España* (2001), un PDF de
cientos de páginas organizado diócesis por diócesis: engorroso de consultar y sin
enlaces a los recursos digitalizados que hoy existen en internet.

Este proyecto vuelca toda esa información en **un buscador web instantáneo**: escribes
un pueblo, una parroquia o un santo titular y obtienes al momento qué series se
conservan, desde qué año, si están concentradas en el archivo diocesano, dónde se
custodian hoy y —cuando existe— **un enlace directo al recurso online** de esa parroquia.

> 🔗 **Demo en vivo:** https://grana10.github.io/archivos-parroquiales/

---

## ✨ Qué ofrece

- **Búsqueda instantánea** por pueblo, parroquia o advocación (santo titular),
  con tolerancia a acentos y mayúsculas.
- **Filtro por diócesis** (66 disponibles, 18.290 parroquias).
- **Ficha por parroquia** con el año del primer libro conservado de cada serie:
  Bautismos · Confirmaciones · Matrimonios · Defunciones · Fábrica.
- Indicadores de **pérdidas en la Guerra Civil**, **concentración** en el archivo
  diocesano y **microfilmación**.
- **Dónde se conserva**: archivo diocesano de referencia con dirección.
- **Enlaces directos** a los recursos digitalizados de la parroquia cuando existen.
- **Una sola página**, sin servidor ni base de datos: rápida y funciona hasta offline.

---

## 🗂️ De dónde salen los datos

La fuente es la *Guía de los Archivos de la Iglesia en España* (Asociación de
Archiveros de la Iglesia en España / Ministerio de Cultura, 2001). El contenido se
extrajo de ese documento, se reorganizó parroquia a parroquia en una tabla única
para las 66 diócesis y se enriqueció con enlaces a los recursos online disponibles.

Cada año indica el **primer libro conservado** de esa serie según la Guía (2001),
**no la fundación** de la parroquia. Concentraciones y digitalizaciones posteriores
pueden haber cambiado el estado real de algunos archivos.

> Jerez de la Frontera no aparece: su entrada en la Guía no incluye tabla de
> parroquias, solo texto descriptivo del archivo.

---

## 📄 Licencia y fuente

Este buscador —diseño, presentación y organización de los datos—
© 2026 **Pablo Granadino Aranda**, bajo licencia
[**Creative Commons BY-NC-ND 4.0**](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.es):
se permite compartir citando al autor, pero **no** el uso comercial ni las obras
derivadas. Ver [`LICENSE`](LICENSE).

Los datos están **derivados** de la *Guía de los Archivos de la Iglesia en España*
(2001). Los hechos en sí no son objeto de derechos de autor; esta herramienta no
reproduce el texto de la obra.
