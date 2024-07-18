# Projeto para disciplina de Inteligência Artificial com intuito de explorar possibilidades sobre visão computacional.

## Bibliotecas utilizadas

opencv: visão computacional e processamento de imagens e frames.
mediapipe: Captura de movimento

## Como rodar o projeto (windows)

Crie seu ambiente virtual python utilizando o comando

```
python -m venv env
```

ative o ambiente virtual com o comando abaixo:

```
./env/Scripts/activate
```

por fim, basta instalar as dependências com o comando `pip install -r requirements.txt`

### Navegando pelo projeto

Dentro da pasta do contador-series, haverá 2 pastas (supino e puxada-frontal) onde, em cada uma, constará um arquivo .ipynb com alguns vídeos de exercícios que condizem com os nomes de suas pastas.

Para ver o projeto rodando, basta executar todas suas células para que o vídeo do exercício abra e seja possível ver o opencv e o mediapipe agindo para contar a repetição da execução dos exercícios.

## Considerações

Para este tipo de trabalho, um consolidado conhecimento sobre ângulos se faz necessário para poder calcular o movimento das markações das articulações do mediapipe. Além disso, o presente modelo pego nas referências possui dificuldade em se adaptar com vídeos cuja movimentação da câmera é frequênte, ou então, o ângulo o qual o vídeo foi gravado pode fazer com que o modelo se perca na identificação das articulações.

Autor: Matheus Martins Scheffer
Referências:
https://learnopencv.com/ai-fitness-trainer-using-mediapipe/
https://www.youtube.com/watch?v=06TE_U21FK4
