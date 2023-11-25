# MedControl-IoT
## Este repositório aborda especificamente a automação do dispensador de medicamentos.

Repositório contendo o MVC do projeto: https://github.com/Jakeline-xx/MedControl

Repositório contendo o front-end mobile do projeto: https://github.com/milenaggoes/MediControl

O projeto MedControl consiste em um sistema para automatização de farmácias hospitalares com um escopo específico, concentrando-nos na distribuição de suprimentos para setores internos, como enfermarias, centros cirúrgicos, laboratórios, entre outros.

Essa iniciativa integra automação, controle de estoque em tempo real, segurança por meio de restrições de acesso, e um aplicativo mobile reservado e também relatórios analíticos para criar uma solução abrangente que otimiza a gestão interna da farmácia, assegurando eficiência, precisão e confiabilidade nas operações.

Nesse repositório exploraremos mais a automação do dispensador de remédios.
Unindo Arduino, Node-RED, MQTT e o Tinkercad exploramos maneiras simples, mas ainda viáveis de criar a máquina.
Apesar das limitações das ferramentas dispostas pelo Tinkercad, com algumas alterações fizemos diferentes modelos para o funcionamento do dispensador.

## Este projeto consiste em um sistema IoT que utiliza um Arduino para controlar um dispensador de medicamentos. O dispensador é equipado com um servo motor para a liberação dos medicamentos e um sensor infravermelho para detecção de uma mão/copo, e então acionar outro servo motor responsável por soltar os medicamentos ao usuário.
# Link do Protótipo no Tinkercad 
https://www.tinkercad.com/things/k2qxn5SHVO6-glorious-sango-waasa/editel?sharecode=ODXJpRocMAMBsfgWBdZCQ3MfsCzIYmMSn1VZ4oi1M18


# Projeto com interface no Node-RED
O Node-RED desempenha um papel fundamental na integração e controle do sistema de dispensador de medicamentos, utilizando uma abordagem visual para programação.
O fluxo no Node-RED foi desenhado para se comunicar com o Arduino por meio do protocolo MQTT.
Inicialmente, configura-se os nós MQTT para estabelecer uma conexão com o broker local, garantindo a comunicação entre o dispositivo simulado e o ambiente virtual do Node-RED.
Foram incorporados nós específicos, como o dropdown para a escolha do medicamento e uma caixa numérica para determinar a quantidade desejada. Simulando o sistema que seria visto no aplicativo mobile.
Esse ambiente visual do Node-RED, combinado com a capacidade de usar protocolos como o MQTT, oferece uma solução flexível, de fácil visualização e manejo para gerenciar dispositivos IoT, proporcionando uma experiência de controle eficiente e acessível para o usuário.

## O código em json está disponível clicando aqui [flows.json](https://github.com/GuilherSil/MedControl-IoT/files/13462602/flows.json). Basta importar o arquivo .json no seu Node-RED e o fluxo será criado.
