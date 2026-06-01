---
title: "Política de Privacidad"
lastUpdated: "2026-05-31"
description: "Cómo Override System Monitor protege tus datos y privacidad en Android."
---

## 1. Información que Recopilamos

Override System Monitor accede a información de tu dispositivo **únicamente** para proporcionar las funciones de monitoreo. Esta información incluye:

### Datos de Sistema

| Categoría | Datos Recopilados |
|-----------|-------------------|
| **Batería** | Nivel, estado de carga, salud, temperatura, voltaje |
| **Memoria** | Uso de RAM, almacenamiento disponible y usado |
| **Sensores** | Acelerómetro, giroscopio, magnetómetro, presión, luz, proximidad |
| **Red** | Estado WiFi, información de conexión, velocidad de transferencia |
| **Dispositivo** | Modelo, fabricante, versión de Android, uptime |

### Datos de Ubicación

La aplicación puede acceder a información de ubicación **solo** para identificar redes WiFi cercanas. Esta funcionalidad requiere permisos de ubicación y los datos se procesan **localmente** en tu dispositivo.

## 2. Uso de la Información

La información recopilada se utiliza **exclusivamente** para:

1. Mostrar métricas en tiempo real del sistema del dispositivo
2. Proveer información detallada cuando solicitas más datos
3. Guardar tus preferencias de configuración
4. Mejorar el rendimiento y funcionalidad de la aplicación

### No Vendemos Datos

> **No vendemos, alquilamos ni compartimos** tu información personal con terceros bajo ninguna circunstancia.

## 3. Almacenamiento Local

La aplicación almacena datos **únicamente** en tu dispositivo:

### Datos de Configuración

```kotlin
// Preferencias guardadas localmente
- Tema seleccionado (oscuro/claro)
- Intervalo de actualización
- Preferencias de visualización
- Configuración de notificaciones
```

### Caché

- Datos de rendimiento para mejorar tiempos de carga
- Información de sensores para funcionamiento offline
- Historial de métricas (opcional)

### Eliminación de Datos

Puedes borrar estos datos de las siguientes formas:

| Método | Acción |
|--------|--------|
| **Desinstalar app** | Elimina todos los datos |
| **Ajustes de Android** | Borrar datos de la aplicación |
| **Dentro de la app** | Resetear preferencias |

## 4. Permisos Requeridos

La siguiente tabla detalla cada permiso y su propósito:

| Permiso | Propósito | ¿Requerido? |
|---------|-----------|-------------|
| `INTERNET` | Verificar conexión a internet | No |
| `ACCESS_NETWORK_STATE` | Estado de red | No |
| `ACCESS_WIFI_STATE` | Mostrar información WiFi | No |
| `ACCESS_COARSE_LOCATION` | Identificar redes WiFi | Opcional |
| `ACCESS_FINE_LOCATION` | Mejor precisión de ubicación | Opcional |
| `READ_PHONE_STATE` | Información del dispositivo | No |
| `ACTIVITY_RECOGNITION` | Sensores de movimiento | Opcional |

> Todos los permisos son **opcionales** y se solicitan solo cuando son necesarios para una función específica. Puedes revocar cualquier permiso desde los ajustes del sistema.

## 5. No Rastreo

### Compromiso de Privacidad

- **No rastreamos** tu actividad fuera de la aplicación
- **No utilizamos** cookies de seguimiento
- **No enviamos** telemetría o análisis a servidores externos
- **No hay** publicidad ni rastreadores de terceros

La aplicación funciona completamente **offline** para todas las funciones de monitoreo.

## 6. Seguridad de Datos

Implementamos medidas de seguridad apropiadas para proteger tus datos:

- **Cifrado local**: Los datos se almacenan de forma segura en el dispositivo
- **Sin transmisión externa**: Ningún dato abandona tu dispositivo
- **Permisos mínimos**: Solo solicitamos permisos necesarios

## 7. Derechos del Usuario

Tienes control total sobre tus datos:

| Derecho | Cómo ejercerlo |
|---------|-----------------|
| **Acceso** | Ver métricas en tiempo real en la app |
| **Eliminación** | Desinstalar o usar reset en ajustes |
| **Revocar permisos** | Ajustes del sistema > Apps > Permisos |
| **Control** | Todas las funciones funcionan sin conexión |

## 8. Cambios a esta Política

Podemos actualizar esta política periódicamente. Cualquier cambio será publicado en esta página con:

- Fecha de "Última actualización" actualizada
- Descripción de los cambios relevantes
- Notificación dentro de la aplicación (si aplica)

Te recomendamos revisar esta política regularmente.

## 9. Niños

La Aplicación no está dirigida a menores de 13 años. No recopilamos deliberadamente información personal de niños. Si descubrimos que hemos recopilado información de un menor, la eliminaremos inmediatamente.

## 10. Contacto

Si tienes preguntas o preocupaciones sobre esta Política de Privacidad, puedes contactar al desarrollador a través de:

- **Web**: override.com.mx/landing/#contact
- **Email**: Soporte disponible en la aplicación

---

*Última actualización: {lastUpdated}*
