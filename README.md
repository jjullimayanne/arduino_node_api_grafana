# Arduino_Node_API_Grafana 🚥🌐📊

## Introdução

Os 193 Estados membros da ONU, incluindo o Brasil, comprometeram-se a adotar a chamada Agenda Pós-2015, considerada uma das mais ambiciosas da história da diplomacia internacional. A partir dela, as nações trabalharão para cumprir os Objetivos de Desenvolvimento Sustentável (ODS).

Baseando-se nisso e alinhado ao objetivo 12, Cidades e Comunidades Sustentáveis: as cidades são parte importante da vida no planeta. Até 2050, cerca de 77% da população mundial viverá em áreas urbanas, de acordo com dados da Organização das Nações Unidas (ONU).

Este projeto visa implementar um sistema básico de monitoramento de tráfego urbano, instalando sensores de tráfego para ser usado em cruzamentos movimentados, estradas e áreas congestionadas da cidade. Será usada IoT para coletar dados de tráfego em tempo real, incluindo volume de veículos e velocidade média.

Será utilizado o Prometheus para coletar e armazenar esses dados, e o Grafana para criar painéis interativos para visualizar o fluxo de tráfego, identificar pontos de congestionamento e analisar padrões de tráfego ao longo do tempo.

## Arduino

Arduino é uma plataforma que possibilita o desenvolvimento de projetos eletrônicos. Em outras palavras, é uma plataforma de prototipagem eletrônica.

O Arduino é constituído de hardware e software, tornando assim possível a realização de diversos projetos tecnológicos.

A placa tem como principal componente o microcontrolador, que é um tipo de processador bem menor do que o convencional.

O microcontrolador executa os programas e avalia qualidade das entradas e saídas, ou seja, dos canais pelos quais é possível a comunicação entre mundo externo e digital.

O Arduino é uma placa open-source. Sendo assim, toda a propriedade intelectual é compartilhada entre os usuários. A linguagem de programação utilizada no Arduino é a linguagem C++ (com pequenas modificações), que é uma linguagem muito tradicional e conhecida.

## Componentes Utilizados

- 1 Arduino Uno
- Sensor Ultrassônico HC-SR04
- Módulo Esp8266 WiFi

### Como funciona o sensor:

Seu comportamento se baseia no envio de sinais ultrassônicos pelo sensor, que aguarda o retorno (echo) do sinal, e com base no tempo entre envio e retorno, calcula a distância entre o sensor e o objeto detectado.

## Estrutura do Projeto

Todo o código do Arduino estará na pasta chamada 'sensor_system_arduino'.
