# discovery

`ddcolor.7z` is published as two parts because GitHub Free rejects a single file over 2 GB.

Rejoin the original archive:

```sh
cat ddcolor.7z.00 ddcolor.7z.01 > ddcolor.7z
7z t ddcolor.7z
```

The archive contains the DDColor project: the four released checkpoints, inference code, Windows and Linux wheels, and the related arXiv papers.
