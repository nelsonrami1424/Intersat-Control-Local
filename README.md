# Intersat Control

Sistema web de control de asistencia de Intersat Los Andes.

## Componentes
- Interfaz web y lógica de control de asistencia.
- Registro y administración de trabajadores.
- Control de horarios, entradas, salidas y horas.
- Conector local para pruebas de comunicación con dispositivos Hikvision mediante ISAPI.

## Estado del conector biométrico
El conector de esta versión permite comprobar el servicio local y consultar información básica del dispositivo. Todavía no recibe ni registra automáticamente las marcaciones biométricas.

## Ejecución
Abre `index.html` en un navegador compatible.

Para utilizar el conector local, consulta las instrucciones de la carpeta `bridge/` e instala las dependencias indicadas en `bridge/requirements.txt`.

## Consideraciones
- Esta publicación contiene el código fuente; no despliega la aplicación en un servidor.
- En esta etapa, los datos de la aplicación se almacenan localmente en el navegador.
- No publiques contraseñas, datos personales de trabajadores ni datos biométricos.
- El entorno virtual de Python (`.venv`) no debe incluirse en el repositorio.