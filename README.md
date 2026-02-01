# quality_XAI
Attention, il faut avoir une version de python en 3.11 car quantus n'est disponible qu'en 3.11.
Je conseille donc de créer un nouvel environnement conda :
conda create -n quality_XAI python =3.11
conda activate quality_XAI
conda install pytorch torchvision captum matplotlib numpy
pip install quantus #librairie en 3.11

Sinon :
pip install torch torchvision captum quantus matplotlib numpy