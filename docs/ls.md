# Comando   `ls`

--- 
`ls [flags] [directory]`
---

1. Lista de archivos en un directorio.
```bash
$ ls
```

Output:
```bash
$ ls
.
..
README.md
```

2. Lista de archivos en un directorio.
```bash
$ ls Downloads
```

Output:
```bash
$ ls Downloads
Scripts
images.jpg
```

3. Lista de archivos en home
```bash
$ ls ~/
```

Output:
```bash
$ ls ~/
.
..
Documents
Downloads
Pictures
```


4. Listar solo directorios
```bash
$ ls -d */
```

Ejemplo:
```bash
$ ls -d */
Documents/
Downloads/
Pictures/
```


5. Listar archivos con subdirectorios
```bash
$ ls *
```

6. Listar archivos con sus tamaños
```bash
$ ls -s
```


7. Listar archivos con formato largo
```bash
$ ls -l
```

Output:
```bash
$ ls -l
total 0
-rw-r--r-- 1 root root 0 May  2 15:04 .
-rw-r--r-- 1 root root 0 May  2 15:04 ..
-rw-r--r-- 1 root root 0 May  2 15:04 README.md
-rw-r--r-- 1 root root 0 May  2 15:04 Scripts
-rw-r--r-- 1 root root 0 May  2 15:04 images.jpg
```

8. Listar archivos con formato largo y tamaño
```bash
$ ls -lh
```

```bash
$ ls -lh
total 0
-rw-r--r-- 1 root root 0 May  2 15:04 .
-rw-r--r-- 1 root root 0 May  2 15:04 ..
-rw-r--r-- 1 root root 0 May  2 15:04 README.md
-rw-r--r-- 1 root root 0 May  2 15:04 Scripts
-rw-r--r-- 1 root root 0 May  2 15:04 images.jpg
```

9. Listar archivos incluyendo archivos ocultos
```bash
$ ls -a
```

Output:
```bash
$ ls -a
.
..
.gitignore
README.md
```

10. Listar archivos incluyendo archivos ocultos y directorios
```bash
$ ls -al
```

Output:
```bash
$ ls -al
total 0
-rw-r--r-- 1 root root 0 May  2 15:04 .
-rw-r--r-- 1 root root 0 May  2 15:04 ..
-rw-r--r-- 1 root root 0 May  2 15:04 .gitignore
-rw-r--r-- 1 root root 0 May  2 15:04 README.md
-rw-r--r-- 1 root root 0 May  2 15:04 Scripts
-rw-r--r-- 1 root root 0 May  2 15:04 images.jpg
```

11. Listar y ordenar archivos por tamaño y tiempo
```bash
$ ls -t
```

output:
```bash
$ ls -t
README.md
Scripts
images.jpg
```

12. Listar archivos y ordenar por tamaño
```bash
$ ls -S
```

Output:
```bash
$ ls -S
README.md
Scripts
images.jpg
```


