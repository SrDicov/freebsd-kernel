# FreeBSD Kernel

Kernel-only snapshot of [FreeBSD](https://www.freebsd.org): the exact contents of the `sys/` subtree of the official `src` tree — nothing else.

- **Origin:** `https://git.FreeBSD.org/src.git` (read-only mirror: `https://github.com/freebsd/freebsd-src`)
- **Subtree:** `sys/`
- **Commit:** `39d6e2226484ca434c7d980eda4aa19ed0d62c9e` (2026-10-12)
- **Integrity:** every file verified byte-for-byte (git blob hash) against upstream.

Note: `README.md` is the upstream kernel's own readme, preserved verbatim.

## Layout

`kern/` core kernel · `sys/` core headers and types · `dev/` drivers · `amd64/`, `arm64/`, `i386/`… machine-dependent code · `net/`, `netinet/`, `netinet6/` networking · `fs/`, `ufs/` filesystems · `vm/` virtual memory · `crypto/`, `opencrypto/` · `geom/` GEOM framework · `cddl/`, `contrib/` third-party code (e.g. OpenZFS) · `modules/` module glue · `conf/` kernel configuration files.

## License

BSD-licensed (mostly BSD-2-Clause) plus other permissive licenses — see the file headers. Canonical terms live in the upstream tree.

## Links

- FreeBSD: <https://www.freebsd.org> · Docs: <https://docs.freebsd.org> · Code browser: <https://cgit.freebsd.org/src/tree/sys>

*Lee esto en [español](README.mirror.es.md) · Legu tion en [Esperanto](README.mirror.eo.md).*
