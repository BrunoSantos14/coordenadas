# Coordenadas
<img src="https://cdn-icons-png.flaticon.com/512/2179/2179254.png" alt="drawing" width="400"/>

# Sobre
Recebe um arquivo CSV e retorna outro acrescentando colunas com as coordendas geográficas (Latitude e Longitude).

Status do projeto: :heavy_check_mark: Concluído

# Índice
:small_blue_diamond: [Desafios](#desafios)

:small_blue_diamond: [Principais características](#principais-características)

:small_blue_diamond: [Pré-requisitos](#pré-requisitos)

:small_blue_diamond: [Como usar](#como-usar)

:small_blue_diamond: [Definindo as classes](#definindo-as-classes)

- [Teste](#Teste)


:small_blue_diamond: [Contribuições futuras](#contribuições-futuras)

# Desafios

# Principais características
- Tratamento da coluna cep para deixar em formato padronizado (xxxxx-xxx);
- Caso o endereço não tenha sido encontrado (pode ocorrer por erro de digitação no cadastro da rua, por exemplo), as colunas de "Latitude" e "Longitude" recebem o texto "Erro";
- O programa calcula o tempo de execução. Por meio de testes, vimos que uma requisição para uma localidade demora entre 0.6 a 1.1 segundo para encontrar suas coordenadas geográficas. Se tratando uma base de dados grande, esse código pode se tornar demorado.

# Pré-requisitos
Para conseguir utilizar todas as classes, verifique se os seguintes pacotes já estão instalados na sua máquina:

- [Pandas](https://pandas.pydata.org/)
- [Requests](https://requests.readthedocs.io/en/latest/)
- [Time](https://docs.python.org/3/library/time.html)
- [Re](https://docs.python.org/3/library/re.html)
- [Geopy](https://pypi.org/project/geopy)

# Como usar
```python
import requests
import pandas as pd
import numpy as np
from geopy.geocoders import ArcGIS
import time
import re
```

# Definindo as classes
### 1. Teste <a name="Teste"></a>

    
# Contribuições futuras
- ...

 
