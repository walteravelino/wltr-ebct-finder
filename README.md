# Wltr EBCT Finder

<a href="https://pypi.org/project/wltr-ebct-finder/">
  <img alt="PyPI" src="https://img.shields.io/pypi/v/wltr-ebct-finder">
</a>

[![Build Status](https://travis-ci.com/walteravelino/Projetos.svg?branch=master)](https://travis-ci.com/walteravelino/Projetos)
<img src = "https://img.shields.io/github/languages/top/walteravelino/wltr-ebct-finder">
<a href="https://github.com/walteravelino/Projetos/blob/master/LICENSE"><img src = "https://img.shields.io/github/license/walteravelino/Projetos"></a>

Wltr EBCT Finder é uma API para consulta de endereços e CEP através do site da Empresa Brasileira de Correios e Telégrafos.

## Autor

👤 **Walter Avelino**

- StackOverFlow [@walteravelino](https://stackoverflow.com/users/13001807/walter-avelino)
- Github: [@walteravelino](https://github.com/walteravelino)
- Linkedin: [@walteravelino](https://linkedin.com/in/walter-avelino-434197105)
- DEV: [@walteravelino](https://dev.to/walteravelino)


## 📝 Licença

Copyright © 2020 [Walter Avelino](https://github.com/walteravelino). <br />
Os projetos estão sob a licença [MIT](https://github.com/walteravelino/Projetos/blob/master/LICENSE).


## Requerimentos

- beautifulsoup4
- requests
- unidecode


## Instalação

 A API Wltr EBCT Finder pode ser instalada usando pip:

    $ pip install wltr-ebct-finder


## Guia rápido

Essa API permite consultar os códigos postais e o endereço através da mesma chamada:

```python
>>> import wltr_ebct_finder

>>> address = wltr_ebct_finder.find_cep('R. Ramiro Barcelos')
>>> print(address)
{'address': 'Rua Ramiro Barcelos', 'neighborhood': 'Vila Guarani (Z Sul)', 'city/state': 'São Paulo/SP', 'zipcode': '04311-050'}
```

```python
>>> import wltr_ebct_finder

>>> address = wltr_ebct_finder.find_cep('04311-050')
>>> print(address)
{'address': 'Rua Ramiro Barcelos', 'neighborhood': 'Vila Guarani (Z Sul)', 'city/state': 'São Paulo/SP', 'zipcode': '04311-050'}
```
