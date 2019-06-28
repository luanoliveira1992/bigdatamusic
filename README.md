# Data Lake Música

### Descrição :
 Este projeto trás uma estrutura básica de um data lake que armazenará dados de audios vindos do soundcloud.

### Estrutura do Lago
- Landed : arquivos brutos, que acabaram de chegar;
- Raw : Arquivos otimizados, já em um formato mais estruturado;
- Modeled : Arquivo com agregações, joined e etc;
- Self : Arquivos pronto para uso

### Ambiente:
- python 3+
- FFmpeg (https://github.com/adaptlearning/adapt_authoring/wiki/Installing-FFmpeg)
- CMU Phinx (https://cmusphinx.github.io/wiki/download/)
- CMU-Sphinx para que usa ubuntu (http://jrmeyer.github.io/asr/2016/01/09/Installing-CMU-Sphinx-on-Ubuntu.html) verificado !


### Leituras Importantes:
 - Speech Recognition com Python: https://realpython.com/python-speech-recognition/
 - Classificação de músicas: https://towardsdatascience.com/music-genre-classification-with-python-c714d032f0d8
 - Data lake manifesto: https://tdwi.org/articles/2017/10/16/arch-all-data-lake-manifesto-10-best-practices.aspx
 - Pipeline de dados na AWS: https://medium.com/@luanoliveira1992/criando-um-pipeline-model-na-aws-sem-sagemaker-727c0fb93aab
 - Fundamentos de feature engineering : https://towardsdatascience.com/feature-engineering-for-machine-learning-3a5e293a5114
 - Como melhor trabalha com Spark : https://medium.com/teads-engineering/spark-performance-tuning-from-the-trenches-7cbde521cf60
 
 
 ### Comandos
 #### Quem usa pip
 - sudo pip install virtualenv (instalar virtualenv)
 - Na pasta do projeto, virtualenv .venv
 - source .venv/bin/activate (Ativar ambiente virtual)
 - pip install -r requirements.txt
 - jupyter notebook
 
 #### Quem usa pipenv
 - sudo pip install pipenv
 - na pasta do projeto pipenv shell
 - pipenv install
 - jupyter notebook


