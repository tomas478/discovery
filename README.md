# discovery

`ddcolor.7z` is published as two parts because GitHub Free rejects a single file over 2 GB.

Rejoin the original archive:

```sh
cat ddcolor.7z.00 ddcolor.7z.01 > ddcolor.7z
7z t ddcolor.7z
```

The archive contains the DDColor project: the four released checkpoints, inference code, Windows and Linux wheels, and the related arXiv papers.

`sam3.7z` is published the same way.

```sh
cat sam3.7z.00 sam3.7z.01 > sam3.7z
7z t sam3.7z
```

That archive contains SAM 3.1: the multiplex checkpoint, inference code, Windows and Linux wheels, and the Segment Anything, SAM 2, and SAM 3 papers.
