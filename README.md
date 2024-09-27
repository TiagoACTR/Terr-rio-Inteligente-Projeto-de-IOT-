# Terrário Inteligente (Projeto de IoT)

Este projeto IoT implementa um **terrário inteligente** que monitora a temperatura e a umidade do ambiente interno, utilizando o sensor **DHT22**. Com base nos valores medidos, o sistema ativa automaticamente um ventilador (simulado com um LED na plataforma WOKWI) para regular a temperatura, e um alarme (simulado com um buzzer) caso os níveis excedam os limites pré-definidos. 

Os dados de temperatura e umidade são enviados em tempo real para o ThingSpeak, onde são armazenados e visualizados em gráficos interativos. O monitoramento contínuo e a análise dos dados coletados podem ser realizados remotamente, garantindo que o terrário esteja sempre em condições ideais. No entanto, o acesso às informações é restrito, podendo ser visualizado apenas pelo responsável autorizado por meio da plataforma ThingSpeak, garantindo a privacidade e segurança dos dados do sistema.

## Funcionalidades:
- **Monitoramento Climático Automático**: Mede e controla a temperatura e a umidade do terrário.
- **Ativação Automática**: O ventilador é ligado quando a temperatura ultrapassa o limite de 30°C, e o alarme é ativado em situações de alerta.
- **Integração com ThingSpeak**: Os dados coletados são enviados para a plataforma ThingSpeak para análise e visualização remota.
- **Simulação de Hardware**: O ventilador e o alarme são simulados com LED e buzzer.

## Simulações:
- **Tinkercad**: [Projeto 3D do Terrário Inteligente](https://www.tinkercad.com/things/5gHcBtLy3to-copy-of-iot-terraruim/edit?sharecode=B53nezKMbVTBiScVmxk61h2mXQsfM72u7WkLn1jWT2w)
- **Wokwi**: [Simulação do Código no Wokwi](https://wokwi.com/projects/410050401857268737)

## Tecnologias Utilizadas:
- **Sensor DHT22**: Para medir a temperatura e a umidade.
- **Microcontrolador ESP32**: Para conectar o projeto à Internet e enviar dados para o ThingSpeak.
- **ThingSpeak**: Plataforma IoT para armazenamento e visualização de dados.
- **Simulações em Wokwi**: Testes e desenvolvimento sem necessidade de hardware físico.
- **Tinkercad**: Protótipo 3D do terrário inteligente.
