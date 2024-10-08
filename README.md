# Challenge-2024
Challenge John deere 1ECA - WS group

# Introdução:
   Nas fábricas da John Deere, enfrentamos desafios significativos no rastreamento de equipamentos e no gerenciamento de materiais, que levam a desperdícios e ineficiências. Problemas como variabilidade na produtividade, falhas de comunicação entre equipes e ineficiências operacionais têm impactado diretamente nossos custos, prazos de entrega e a qualidade dos produtos.

# Desenvolvimento:
  Desenvolvemos uma plataforma inteligente que proporciona visibilidade em tempo real de toda a operação. Utilizando trilaceração de sinal e integração em nuvem, nossa solução permite rastrear carros-kits, rebocadores e materiais com precisão. Gestores, poderão acompanhar o posicionamento exato dos recursos na fábrica, visualizar dados em tempo real para evitar a falta de materiais, e facilitar a comunicação entre as equipes, prevenindo problemas antes que impactem a produção.

Tecnologias utilizadas:
   Durante o desenvolvimento do projeto, foram utilizadas diferentes tecnologias, como trilaceração, leitura de RSSI e mac adress, exportação e importação de dados da nuvem, placa de circuitos ESP32 com módulo nrf24l01, bibliotecas de suporte, como matplotlib, requests, network, time, ujson, ssl, math e socket.
   O projeto foi estruturado em javascript, css e html com backend em python. As bibliotecas utilizadas foram requests, flask e math

# Resultados:
   A aplicação consiste em um projeto escalável para a localização de carros-kits e rebocadores na fábrica. Cada rebocador e cada kit serão equipados com uma placa de circuito ESP32, conectada a uma antena. Essa placa será responsável por calcular continuamente a localização do equipamento e enviar esses dados para a nuvem. O backend do servidor extrairá essas informações e as usará para mapear a posição dos rebocadores e kits em tempo real. Os montadores poderão solicitar o reabastecimento ou a entrega de um kit por meio de uma interface dedicada; o rebocador mais próximo do kit solicitado receberá uma notificação e deverá realizar a entrega no destino indicado na tela.

https://www.youtube.com/watch?v=iaZc8DCg9Lg
