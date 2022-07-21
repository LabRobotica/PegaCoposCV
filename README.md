# Tarefa PegaCoposCV

Tarefa da disciplina 'Laboratório de Sensores e Atuadores para Engenharia Mecatrônica' em que consiste em mensurar a posição de copos em cima de uma mesa visão computacional e os empilhar usando um robô industrial com controladora aberta.

## Estrutura

- **Robo Industrial:** Comau Smart5Six
- **Controladora do robô:** Comau C5G
- **Computador auxiliar da controladora:** B&R APC-910
- **Computador estação de trabalho:** Dell OptiPlex 7010
- **Câmera:**

## Instruções

Realize os seguinte passos, em ordem:
- Capture fotos do copo posicionado na ferramenta do robô, armazenando também a posição XY do robô no momento da foto. 
- Identifique o centroide do copo em coordenadas de imagem UV, em cada foto capturada.
- Criae uma tabela correlacionando as coordenadas do copo UV com as coordenadas XY do robô.
- A partir da tabela, crie uma relação UV -> XY de certa forma que, dada as cordenas u1 e v1, seja possível encontrar matemáticamente a posição x1 e y1 do robô que leve a ferramenta no copo. 
- Desenvolva um software que:
  - Se conecte com a câmera instalada.
  - Realize a captura de imagem.
  - Processe a imagem encontrando o centroide UV de cada copo.
  - Use a relação encontrada para achar as respectivas posições XY que leva o robô a cada copo.
  - Realize uma rotina de empilhar um copo em cima do outro e depois desempilhar o mesmo.

**Facilitador:** No dia 20/07/2022 foi realizada a captura de fotos do copo em algumas posições XY do robô. As capturas estão na pasta "Calibração", em "DadosCru". Caso a posição ou orientação da câmera no laboratório seja alterada, os dados serão inválidos.
