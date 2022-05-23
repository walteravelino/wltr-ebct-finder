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


## Instalação

 A API Wltr EBCT Finder pode ser instalada utilizando o pip:

    $ pip install wltr-ebct-finder


## Guia rápido

```python
>>> import wltr_ebct_finder

>>> address = wltr_ebct_finder.find_data('04311050')
>>> print(address)

    {'cep': '04311-050',
     'logradouro': 'Rua Ramiro Barcelos',
     'complemento': '',
     'bairro': 'Vila Guarani (Z Sul)',
     'localidade': 'São Paulo',
     'uf': 'SP',
     'ibge': '3550308',
     'gia': '1004',
     'ddd': '11',
     'siafi': '7107'}
```
