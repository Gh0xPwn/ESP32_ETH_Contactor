## ESP32 Ethernet 24 V Relay Controller – V1

Primera versión de un módulo de control de cargas de 24 V basado en ESP32, con salidas mediante relés y conectividad Ethernet para permitir posteriormente el control remoto de cargas eléctricas.

<img width="1999" height="1414" alt="image" src="https://github.com/user-attachments/assets/8fca041d-40b6-42d8-b9cf-7906d779dfdb" />
<img width="1999" height="1414" alt="image" src="https://github.com/user-attachments/assets/247f821e-b6c6-4cf3-b386-0ad933a0659a" />

<img width="1999" height="1414" alt="image" src="https://github.com/user-attachments/assets/fca4e2cd-9d09-40a0-9ed2-52c465815a59" />


# ESP32 Ethernet 24V Relay Controller – V1

## 📋 Descripción
Módulo de control de cargas de 24V basado en ESP32 con conectividad Ethernet para control remoto de dispositivos industriales.

## 🔧 Características Técnicas
- Microcontrolador: ESP32-WROOM-32
- Conectividad: Ethernet (W5500)
- Salidas: 4 canales de relé para cargas de 24V DC
- Alimentación: 24V DC industrial con regulación a 5V/3.3V
- Protección: Fusibles, diodos flyback, optoacopladores

## 📐 Diseño
- PCB diseñada en [Altium/EasyEDA]
- 2 capas con plano de tierra
- Separación de etapas de potencia y lógica
- Conectores industriales (bornieros de tornillo)

## 🚧 Estado del Proyecto
- ✅ Diseño de esquemático completado
- ✅ Layout de PCB y generación de Gerbers
- ⏳ Fabricación de PCB (en proceso)
- ⏳ Ensamblaje y pruebas funcionales

## 📷 Galería
[Aquí deberías subir capturas del esquemático, layout 3D, y fotos cuando tengas el prototipo físico]

## 🔮 Próximas versiones
- V2: Integración con MQTT para control remoto vía web
- V3: Aislamiento galvánico completo entre potencia y lógica
