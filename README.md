# Guia de instalação

## Introdução
A conversão de 2D para 3D ocorre quando a retificação está habilitada e é
obtido a partir de um valor fornecido da coordenada Z sendo esse valor adimensional,
também é fornecido valores constantes, de uma parede paralela ao plano do sensor,
o valor da distância radial aumenta quanto mais se distância do centro do pixel 

## Caracteristicas da camera:
Captura e Gravação: 

    - resolução de 640X480 pixels 
    - 20 fps (resolução de gravação máxima no modo de processamento)
    - calibração e 0,5m a 5m precisão absoluta de 1 cm (média entre a média da distância e a distância verdadeira)
    
# Instruções de Instalação 

**Datasheet:** (https://www.baslerweb.com/en/sales-support/downloads/document-downloads/basler-tof-camera-users-manual/)

## Pylon

**Repositorio github oficial da interface:** (https://github.com/basler)
**Link de Download:** (https://www.baslerweb.com/en/sales-support/downloads/software-downloads/)

### windows
   
Baixar e instalar o arquivo: (pylon 6.3.0 Camera Software Suite Windows .exe)

### Linux

Baixar e intalar o arquivo (pylon 6.3.0 Camera Software Suite Linux x86 (64 Bit) .gz)
- Neste ponto já é possivel visualizar imagens no pypilon:


### Requesitos para desenvolvimento Python
- python 3.6 ou superior (recomendado 3.7) <br>
Recomendação - Instalar as bibliotecas com o pip a seguir:
    - pip install numpy
    - pip install open3d
    - pip install Pillow
    - pip install matplotlip
    - pip install opencv-python

# Mais informações
https://www.baslerweb.com/en/products/cameras/3d-cameras/basler-blaze/?creative=588896446450&keyword=basler%20tof&matchtype=p&network=g&device=c&gclid=CjwKCAjwjZmTBhB4EiwAynRmDxcvMQj-eaoSSoRvwkGZEgYHz5bu4jpW-tksN8tVT9l9M_LDtKIQGBoCl30QAvD_BwE
