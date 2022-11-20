# Algoritmos Não-Supervisionados para clusterização


### Objetivo:

Classificar os países usando fatores socioeconômicos e de saúde que determinam o desenvolvimento geral do país.

### Sobre organização:

A HELP International é uma ONG humanitária internacional que está empenhada em combater a pobreza e fornecer às pessoas de países atrasados ​​serviços básicos e alívio durante o período de desastres e calamidades naturais.

### Declaração do problema:

A HELP International conseguiu arrecadar cerca de US$ 10 milhões. Agora o CEO da ONG precisa decidir como usar esse dinheiro de forma estratégica e eficaz. Portanto, o CEO deve tomar a decisão de escolher os países que mais precisam de ajuda. Portanto, seu trabalho como cientista de dados é categorizar os países usando alguns fatores socioeconômicos e de saúde que determinam o desenvolvimento geral do país. Então você precisa sugerir os países nos quais o CEO precisa se concentrar mais.


bibliotecas importadas no projeto:
```
import pandas as pd
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
import seaborn as sns
import matplotlib.pyplot as plt 
import scipy
import scipy.spatial
from sklearn.preprocessing import StandardScaler
import numpy as np
import scipy.cluster.hierarchy as hcluster
from sklearn.cluster import AgglomerativeClustering
```

