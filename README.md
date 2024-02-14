![Carnaval](https://github.com/LaQuokka/Analise_BuscaBloco/assets/122839919/0f052cb0-78d9-4253-94a3-8a40904c0bdf)

<div align="center">

  **Análises:** <a href="https://github.com/LaQuokka">[![GitHub Badge](https://img.shields.io/badge/Cinthya_Beneducci-100000?style=for-the-badge&logo=GitHub&logoColor=white)](https://github.com/LaQuokka)</a>

</div>

---

# O FEA.dev e o Busca Bloco 👩‍💻🎉
O [FEA.dev](https://github.com/fea-dev-usp) é uma entidade estudantil da USP que tem como objetivo conectar os estudantes à intersecção entre o mundo dos negócios e o universo da programação. Já o  [Busca Bloco](https://www.buscabloco.com.br/)  é uma iniciativa que visa ajudar as pessoas a planejarem a sua folia através de um painel interativo do Power BI que contém todos os desfiles de blocos oficiais do Rio de Janeiro e de São Paulo mapeados por data, região e estilo musical!

---

## Overview 
 Esse projeto consiste em uma ***análise de dados sobre bloquinhos de Carnaval na cidade de São Paulo em 2024 utilizando Python***. Os dados foram disponibilizadas ao FEA.dev pela equipe do Busca Bloco, de modo que, no total, foram analisados 464 bloquinhos.

 ## Instalação

Foram utilizadas as seguintes dependências:

__Extração de dados:__
```bash
import os
```

__Manipulação de dados:__
```bash

import pandas as pd
import datetime
import numpy as np
import random
import json
```

__Visualização de dados:__
```bash
import matplotlib.pyplot as plt
from matplotlib.colors import LinearSegmentedColormap
from matplotlib.ticker import FuncFormatter
import folium
```

Caso falte alguma dependência na sua máquina, basta instalar com o comando pip, como pode ser visto no exemplo abaixo.
```bash
  pip install folium
```

## Dados
Os dados utilizados são referentes ao bloquinhos oficiais de São Paulo em 2024 podem ser visualizados no [Power BI do Busca Bloco](https://app.powerbi.com/view?r=eyJrIjoiMzVjZjEzNDEtOGNhOC00ZTU3LWJjZTUtYmExODQ4ZDhlNThhIiwidCI6IjA4NzllN2Q3LTQ4ZWQtNDE2My1hM2M5LWRjNDJhMTUwZDE0YyJ9). Caso queira ter acesso a base de dados para a realização de projetos, entre em contato com as responsáveis pela iniciativa por meio de seu [site](https://www.buscabloco.com.br/) ou de seu [Instagram](https://www.instagram.com/buscabloco?igsh=OG93ZW95dHk3cGVo).

Basicamente, a base consiste em uma tabela de 464 linhas e 11 colunas com as seguintes características e variáveis:
* **Nome do Bloco:** coluna com dados do tipo ```object``` que corresponde ao nome do bloquinho;
* **Zona:**  coluna com dados do tipo ```object``` que corresponde a zona da cidade em que o cloquinho está localizado;
* **Itinerário:**  coluna com dados do tipo ```object``` que corresponde ao itinerário do bloquinho;
* **Estilo Musical:** coluna com dados do tipo ```object``` que corresponde ao estilo musical do bloquinho;
* **Cidade:**  coluna com dados do tipo ```object``` que corresponde a cidade em que o bloquinho está localizado;
* **Latitude:** coluna com dados do tipo ```object``` que corresponde a latitude do local em que o bloquinho irá começar;
* **Longitude:** coluna com dados do tipo ```object``` que corresponde a longitude do local em que o bloquinho irá começar;
* **Data:** coluna com dados do tipo ```datetime64[ns]``` que corresponde ao dia da semana em que o bloquinho irá ocorrer;
* **Dia:** coluna com dados do tipo ```object``` que corresponde ao dia da semana em que o bloquinho irá ocorrer;
* **Hora:** coluna com dados do tipo ```object``` que corresponde ao horário de início do bloquinho.

[Clique aqui para visualizar o Power BI completo do Busca Bloco 👇](https://app.powerbi.com/view?r=eyJrIjoiMzVjZjEzNDEtOGNhOC00ZTU3LWJjZTUtYmExODQ4ZDhlNThhIiwidCI6IjA4NzllN2Q3LTQ4ZWQtNDE2My1hM2M5LWRjNDJhMTUwZDE0YyJ9)
![Capa do BI](https://github.com/LaQuokka/Analise_BuscaBloco/assets/122839919/52eb53f7-baef-4191-b45a-2d5f48768ffe)

## Resultados
As conclusões e os resultados das análises podem ser vistos no [perfil do FEA.dev no Instagram!](https://www.instagram.com/fea.dev/)
<div align="center">
 <a href="https://www.instagram.com/fea.dev/" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>
</div>
