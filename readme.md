# Dashboard com dados COVID 2022

Nesse projeto será criado um dashboard interativo utilizando dados reais sobre o COVID.

## Instalando bibliotecas necessárias:

```py
import dash
import dash_core_components as dcc
import dash_html_components as html
from dash.dependencies import Input, Output
import dash_bootstrap_components as dbc

import plotly.express as px
import plotly.graph_objects as go

import numpy as np
import pandas as pd
import json
```
