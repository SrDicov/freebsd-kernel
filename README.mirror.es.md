# Kernel de FreeBSD

Copia exclusiva del kernel de [FreeBSD](https://www.freebsd.org): el contenido exacto del subdirectorio `sys/` del árbol oficial `src` — nada más.

- **Origen:** `https://git.FreeBSD.org/src.git` (espejo de solo lectura: `https://github.com/freebsd/freebsd-src`)
- **Subdirectorio:** `sys/`
- **Commit:** `39d6e2226484ca434c7d980eda4aa19ed0d62c9e` (2026-10-12)
- **Integridad:** cada archivo verificado byte por byte (hash de blob de git) contra el repositorio oficial.

Nota: `README.md` es el readme propio del kernel oficial, conservado tal cual.

## Estructura

`kern/` núcleo del kernel · `sys/` cabeceras y tipos centrales · `dev/` controladores · `amd64/`, `arm64/`, `i386/`… código dependiente de máquina · `net/`, `netinet/`, `netinet6/` red · `fs/`, `ufs/` sistemas de ficheros · `vm/` memoria virtual · `crypto/`, `opencrypto/` · `geom/` infraestructura GEOM · `cddl/`, `contrib/` código de terceros (p. ej. OpenZFS) · `modules/` pegamento de módulos · `conf/` ficheros de configuración del kernel.

## Licencia

Licencias BSD (mayormente BSD-2-Clause) más otras licencias permisivas — ver las cabeceras de cada fichero. Los términos canónicos están en el árbol oficial.

## Enlaces

- FreeBSD: <https://www.freebsd.org> · Documentación: <https://docs.freebsd.org> · Navegador de código: <https://cgit.freebsd.org/src/tree/sys>

*Read this in [English](README.mirror.md) · Legu tion en [Esperanto](README.mirror.eo.md).*
