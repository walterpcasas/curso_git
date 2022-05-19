Limpiar archivos Untracked (commitear archivos que no seran eliminados)

```bash
$ git clean -f
```

Optimiza repositorio

```bash
$ git gc
```

File System Check - Verifica posibles archivos corruptos

```bash
$ git fsck
```

Historial de commit, branches, resets

```bash
$ git reflog
```

Convertir repo en un archivo comprimido

```bash
$ git archive --format zip --output master_files.zip master
```