# Eye Controlled Mouse

Este é um projeto que utiliza a biblioteca OpenCV junto com a MediaPipe e PyAutoGUI para criar um controle de mouse baseado no movimento dos olhos detectado pela câmera.

## Funcionalidades

- **Detecção Facial e de Pontos de Referência**: Utiliza a detecção de rosto e pontos de referência faciais para identificar a posição dos olhos.
- **Controle do Mouse**: Move o cursor do mouse com base nos movimentos dos olhos detectados.
- **Clique do Mouse**: Realiza cliques do mouse quando o usuário fecha os olhos por um determinado período de tempo.

## Instalação

1. Certifique-se de ter o Python instalado em seu sistema.
2. Instale as dependências necessárias executando o seguinte comando:
   ```
   pip install opencv-python mediapipe pyautogui
   ```
3. Execute o script Python fornecido neste repositório.

## Como Utilizar

1. Execute o script Python.
2. Posicione seu rosto de forma que sua câmera possa detectá-lo.
3. Mova seus olhos na direção desejada para mover o cursor do mouse.
4. Feche os olhos por um período de tempo especificado para realizar um clique do mouse.

## Limitações

- A precisão do controle do mouse pode variar dependendo das condições de iluminação e da qualidade da detecção facial.
- O desempenho pode ser afetado em condições de baixa iluminação ou quando há obstruções no rosto.

