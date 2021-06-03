# 코로나 이후 이동량, 정말  줄었을까?
## sub Title - seoultraffic EDA projrct
------
### Useing library

    - import pandas as pd
    - import numpy as np
    - import matplotlib.pyplot as plt
    - import matplotlib
    - from matplotlib import pyplot
    - import seaborn as sns
    - import matplotlib.font_manager as fm
    - import missingno as msno #결측데이터 검색
    - import warnings
    - import time
    - %matplotlib inline
    - %config InlineBackend.figure_formats = {'png', 'retina'}
-----------

![initial](https://user-images.githubusercontent.com/80030759/120570772-cfa5a080-c453-11eb-89a7-02f9095e9ba6.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120570989-35922800-c454-11eb-82e5-67268a336598.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120570992-37f48200-c454-11eb-8786-b96a021514f3.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120570994-388d1880-c454-11eb-8ca2-4854f538fab3.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120570998-3925af00-c454-11eb-8ac7-f7ab129a44b7.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571002-39be4580-c454-11eb-8c07-280d3a875363.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571011-3b880900-c454-11eb-9c6c-444d845c407f.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571013-3c209f80-c454-11eb-85dc-9aff59397d44.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571014-3cb93600-c454-11eb-94cf-a6f8eb2c638b.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571015-3dea6300-c454-11eb-8180-052abfa26a64.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571018-3e82f980-c454-11eb-8e5a-21ec4bf4ec9b.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571019-3f1b9000-c454-11eb-9ea0-e9b5e60de674.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571020-3fb42680-c454-11eb-9b2a-94d9d067b9f9.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571021-404cbd00-c454-11eb-8f41-4cd06d8a1ce6.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571025-40e55380-c454-11eb-94d5-733e189c8494.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571026-417dea00-c454-11eb-8a6e-054875d44cb9.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571028-42168080-c454-11eb-830b-cadae93d0c9b.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571029-42af1700-c454-11eb-9280-b3e354308f70.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571031-42af1700-c454-11eb-8112-cebf193ab7bf.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571034-4347ad80-c454-11eb-8add-7cf6f5a15c5c.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571035-43e04400-c454-11eb-869a-d5fb599f62ba.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571039-45aa0780-c454-11eb-99b0-82c9c55f2dd2.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571042-46429e00-c454-11eb-831d-8999014ee123.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571048-4773cb00-c454-11eb-886f-61decaf4f2e1.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571056-493d8e80-c454-11eb-9e9e-5725b6f85afc.jpg)
![initial](https://user-images.githubusercontent.com/80030759/120571057-49d62500-c454-11eb-865d-9a922988afed.jpg)
