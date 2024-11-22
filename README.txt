# **Projeto: Monitor de Temperatura com LEDs Indicadores**

Este projeto utiliza um sensor de temperatura DS18B20 para monitorar a temperatura de um sistema, como um servidor, e indicar sua condição através de dois LEDs:  
- Um **LED verde** que acende quando a temperatura está **abaixo de 60 °C**.  
- Um **LED vermelho** que acende quando a temperatura está **acima de 60 °C**.  

---

## **Descrição do Projeto**
Este sistema pode ser utilizado para monitorar temperaturas em servidores, PCs ou sistemas industriais. Ele utiliza:
- Um **sensor DS18B20** para medir a temperatura.
- Dois LEDs para sinalização:
  - **LED Verde:** Indica que a temperatura está em uma faixa segura (abaixo de 60 °C).
  - **LED Vermelho:** Indica que a temperatura ultrapassou o limite seguro (acima de 60 °C).

---

## **Componentes Utilizados**
1. **Arduino UNO** (ou equivalente).
2. **Sensor DS18B20** (sensor de temperatura).
3. **Resistor de 4.7 kΩ** (para o DS18B20).
4. **LED Verde**.
5. **LED Vermelho**.
6. **2x Resistores de 220 Ω** (um para cada LED).
7. **Breadboard**.
8. **Fios de conexão (Jumpers)**.

--

## **Instruções de Uso**
1. Monte o circuito conforme descrito.
2. Conecte o Arduino ao computador via cabo USB.
3. Abra o **Arduino IDE**, cole o código e envie-o para a placa.
4. Observe os LEDs:
   - O **LED verde** deve acender enquanto a temperatura estiver abaixo de 60 °C.
   - O **LED vermelho** deve acender quando a temperatura ultrapassar 60 °C.
5. Use o **monitor serial** para visualizar as leituras de temperatura em tempo real.

---

## **Requisitos e Dependências**
### **Bibliotecas Necessárias**
- **OneWire:** Biblioteca para comunicação com o sensor DS18B20.
- **DallasTemperature:** Biblioteca para leitura da temperatura do sensor.
