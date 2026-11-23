# Daniel Afonso

Frequento a Licenciatura em Engenharia Eletrotécnica e de Computadores (LEEC) no Instituto Superior de Engenharia do Porto (ISEP). O meu trabalho abrange sistemas embebidos, eletrónica analógica e desenvolvimento de software.

Atualmente à procura de estágio curricular nas áreas de sistemas embebidos, firmware ou desenvolvimento de sistemas.

## Projetos em Destaque

### [telemetry-sim](https://github.com/daniel-af25/telemetry-sim) — Simulador 2D/3D de Telemetria Automóvel
Aplicação web *client-side* em **TypeScript**, **MapLibre GL** e **Three.js** para reconstrução física e visualização de viagens a partir de ficheiros CSV (formato LABSIS v2.2 e ISO 8855):

- **Motor de Física (Web Worker):** calibração de IMU com compensação de inclinação da estrada, modelo paramétrico a partir de um catálogo de ~25 000 veículos, círculo de atrito de Kamm, transferência de carga nas 4 rodas (`ΣFz = m·g`), cinemática WGS84 ↔ ENU com *dead-reckoning* em túneis e interpolação a 60 FPS (validado com 94 testes em Vitest).
- **Visualização e Análise:** mapa 3D com relevo real (DEM) e edifícios extrudidos, veículo 3D articulado com vetores de força, HUD a 60 FPS (diagrama G-G, cargas `Fz` e 5 pilares de condução), *Black Box Incident Replay* (`0,25×`), simulação de cenários *What-If* (piso seco/molhado/gelo e carga), laboratório de engenharia 2D/3D e exportação de vídeo WebM e CSV científico (`# schema=6`).

## Portefólio Académico — [ISEP](https://github.com/daniel-af25/ISEP)

Repositório central onde reúno projetos e relatórios desenvolvidos ao longo do curso, organizados por domínio:

- **[Embedded_Systems](https://github.com/daniel-af25/ISEP/tree/main/Embedded_Systems)** — programação *bare-metal* e sistemas embebidos em **ATmega128** (C e Assembly AVR: máquinas de estados, PWM, ADC, USART/RS232, controlo de motores DC/passo e telemetria via *Input Capture*) e em **ATmega328P + ESP8266** ([Automotive_Telemetry_LABSIS](https://github.com/daniel-af25/ISEP/tree/main/Embedded_Systems/Automotive_Telemetry_LABSIS): aquisição a 5 Hz com MPU6050, GPS NEO-6M via UBX e LM35Z, controlo térmico PWM autónomo, ponte MQTT + painel OLED 128×64, dashboard Node-RED, base de dados SQLite com 25 374 veículos, alertas de acidente e motor Node.js de debrief PDF/CSV).
- **[Analog_Electronics](https://github.com/daniel-af25/ISEP/tree/main/Analog_Electronics)** — sistema de instrumentação e controlo térmico analógico com termístor NTC, condicionamento de sinal (Ponte de Wheatstone, amplificador de instrumentação e limitador de precisão), simulação em PSpice, atuação linear/PWM e aquisição de dados com Arduino Mega 2560 e LabVIEW.
- **[C_Applications](https://github.com/daniel-af25/ISEP/tree/main/C_Applications)** — desenvolvimento em C estruturado aplicado à gestão de fluxos de atendimento e triagem clínica, com registo temporal e geração de métricas operacionais.
- **[Web_Applications](https://github.com/daniel-af25/ISEP/tree/main/Web_Applications)** — plataformas web *full-stack* com bases de dados relacionais, incluindo uma loja online em Python/Django (`beer_shop`) e um sistema de gestão de stock e encomendas em PHP/MySQL (`stock_management`).

## Competências Técnicas

- **Sistemas Embebidos e Hardware:** C, C++, Assembly (AVR), Microcontroladores ATmega / Mega, ESP8266, I2C/TWI, UART/USART, PWM, ADC, Timers, MQTT, sensores IMU (MPU6050), GPS (NMEA/UBX), eletrónica analógica
- **Software e Web:** TypeScript, JavaScript, Node.js, Python, Django, PHP, SQL (SQLite, MySQL), HTML5/CSS3, Three.js, MapLibre GL
- **Ferramentas:** Microchip/Atmel Studio, PlatformIO, Arduino IDE, KiCad, PSpice, LabVIEW, Node-RED, Mosquitto, Vite, Vitest, Git

## Contacto

- Email: danielkyyr@gmail.com
- LinkedIn:
