# cocsign

[![DOI](https://zenodo.org/badge/4102/sinfallas/cocsign.svg)](https://zenodo.org/badge/latestdoi/4102/sinfallas/cocsign)

[![Build Status](https://travis-ci.org/sinfallas/calc-mem.svg?branch=master)](https://travis-ci.org/sinfallas/calc-mem)

Script para la firma del código de conducta de ubuntu y crear la llave ssh que se utilizara en launchpad.net

Basado en código de Eduardo Echeverria <echevemaster@gmail.com>

## Modificaciones y Optimizaciones

* Jesus Palencia <sinfallas@gmail.com>
* Hector Mantellini <xombra.com@gmail.com>

Uso:

```bash
cocsign instalar|gpg|ssh nombre apellido tu@correo.com
```

Ejemplos:

* instalar (como root)
```bash
./cocsign instalar
```

* gpg
```bash
./cocsign gpg nombre apellido tu@correo.com
```

* ssh
```bash
./cocsign ssh
```
