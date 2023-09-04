# Projeto-IA-22-23-Malware-Android
Deteção e Classificação de Malware em Android com Deep Learning

Este projeto foi desenvolvido por Edgar Andrade e Luís Duarte sob a orientação do Professor Doutor João da Silva Pereira e do Professor Humberto Ferreira.
# Informações
Aqui encontram-se informações relevantes sobre os conteúdos deste repositório.
## Dataset
Neste trabalho foi utilizado o dataset CICMalDroid2020[^1][^2] que pode ser requisitado em https://www.unb.ca/cic/datasets/maldroid-2020.html.
## Feature Extraction
O processo de feature extraction utilizado neste trabalho baseou-se no projeto de Asim Darwaish e Farid Naït-Abdesselam[^3] que pode ser encontrado em https://github.com/asimswati553/RGB-based-Andorid-Malware-detection.
## Notas
- A pasta Images contém dois arquivos RAR que têm as imagens de dimensões 64x64 e 80x80 geradas e utilizadas neste projeto;
  
- As diretorias Dataset e Models vêm com uma estrutura pronta a utilizar, sendo que os ficheiros de texto nelas contidos apenas serviram para que se pudesse realizar o commit das diretorias;
  
- Para se poder utilizar a aplicação no estado em que se encontra é necessário inserir três modelos na pasta [App/models/](App/models/), sendo que os nomes têm que ser "flatten.hdf5", "conv2D.hdf5" e "resnet50.hdf5".
# Instalação de dependências
Este trabalho foi desenvolvido utilizando a versão 3.10.9 do Python, sendo o uso desta versão o recomendado. 

Para instalar todos os pacotes necessários para o funcionamento da aplicação basta correr o seguinte comando:
```shell
pip install -r requirements.txt
```
# Executar a aplicação
Para iniciar a aplicação apenas é necessário correr o seguinte comando na consola, dentro da pasta App.
```shell
python MalwareClassificationApp.py
```
# Referências
[^1]: Samaneh Mahdavifar, Andi Fitriah Abdul Kadir, Rasool Fatemi, Dima Alhadidi, Ali A. Ghorbani; Dynamic Android Malware Category Classification using Semi-Supervised Deep Learning, The 18th IEEE International Conference on Dependable, Autonomic, and Secure Computing (DASC), Aug. 17-24, 2020.

[^2]: Samaneh Mahdavifar, Dima Alhadidi, and Ali A. Ghorbani (2022). Effective and Efficient Hybrid Android Malware Classification Using Pseudo-Label Stacked Auto-Encoder, Journal of Network and Systems Management 30 (1), 1-34.

[^3]: A. Darwaish e F. Naït-Abdesselam, “RGB-based Android Malware Detection and Classification Using Convolutional Neural Network,” 
RGB-based Android Malware Detection and Classification Using Convolutional Neural Network, 2020.
