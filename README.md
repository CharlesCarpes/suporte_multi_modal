# Suporte Multi Modal

Este projeto utiliza a API do Gemini para permitir que pessoas com deficiência visual possam obter a descrição de imagens através de comandos de voz.

O código foi escrito em Python e usa o Google COLAB para interagir com os modelos generativos do Google. Assim, é possível utilizar esta solução diretamente em qualquer dispositivo (PC, Notebook ou celular Android) que tenha o navegador Chrome instalado.

O caso de uso principal para qual o projeto foi pensado é o de facilitar o acesso à informações visuais por pessoas com algum tipo de deficiência visual. Em uma futura versão, o código poderia ser embarcado em um equipamento vestível (como óculos ou um capacete com câmera) e o usuário poderia fazer consultas por voz através da API para obter a descrição das imagens capturadas pela câmera do dispositivo. Neste caso de uso, o deficiente visual poderia transitar pela cidade com o equipamento e ser capaz de localizar informações visuais como placas de trânsito, pontos de ônibus, estabelecimentos comerciais e, eventualmente, reconhecer novos obstáculos no trajeto.

### Outros casos de uso incluem:

1. **Assistente virtual acionado por voz (semelhante à Alexa)** com capacidade de visão computacional que poderia ser utilizada em dispositivos vestíveis ou móveis (como celulares, drones e veículos robóticos). No caso de dispositivos vestíveis, a assistente poderia ser acionada por um botão físico e, a partir do toque no botão, iniciar a conversa e a captura de imagens.
2. **Análise de emoções com a webcam do usuário**: Com uma pequena modificação no código, é possível utilizar as imagens da webcam do usuário para identificar suas emoções durante um diálogo de atendimento com um chatbot. Isso seria especialmente interessante para chatbots utilizados para atendimento a demandas de clientes (identificar ansiedade, humor do cliente em casos de reclamação) e em sistemas de vendas automatizadas onde o cliente poderia receber informações sobre produtos e dialogar com o chatbot para efetivar a compra. Com acesso à câmera, o chatbot poderia avaliar o nível de interesse dos clientes em relação a cada produto apresentado através da análise de suas expressões faciais e linguagem corporal.
3. **Sistema de segurança para identificação de pessoas suspeitas**: O mesmo sistema poderia ser utilizado em sistemas de segurança para identificar pessoas suspeitas em um local monitorado e iniciar um aviso ao usuário.

