---
title: "Política de Privacidad"
lastUpdated: "2026-06-01"
description: "Política de privacidad de Override System Monitor para Android."
---


**Override** (en adelante, "nosotros", "nuestro" o "la Empresa") está firmemente comprometida con la protección de la privacidad de los usuarios (en adelante, el "Usuario") de la aplicación móvil **Override System Monitor** (en adelante, la "Aplicación").

Esta Política de Privacidad explica detalladamente cómo tratamos la información y los datos técnicos cuando utilizas nuestra Aplicación. Al descargar y utilizar la Aplicación, aceptas las prácticas descritas en este documento.

## **1\. Principio de Privacidad por Diseño (Procesamiento 100% Local)**

Nuestra filosofía de desarrollo se basa en la privacidad del usuario. **Override System Monitor** es una herramienta de diagnóstico y monitoreo que funciona de manera autónoma en tu dispositivo.

* **Sin servidores externos:** No poseemos ni operamos servidores remotos para almacenar tus métricas.  
* **Almacenamiento Local:** Toda la información recolectada por la Aplicación sobre el rendimiento, batería, sensores o almacenamiento de tu dispositivo se guarda única y exclusivamente en el almacenamiento interno de tu teléfono o tableta, utilizando tecnologías de base de datos seguras (Room) y preferencias del sistema (DataStore).  
* **Sin transmisión de datos:** Tus datos técnicos, de rendimiento o de ubicación física jamás son transmitidos, vendidos, compartidos ni transferidos a nosotros ni a ningún tercero.

## **2\. Permisos del Sistema y Uso de la Información**

Para que la Aplicación pueda realizar diagnósticos de hardware y conectividad en tiempo real, requiere la concesión de permisos específicos del sistema operativo Android. A continuación, detallamos qué datos lee cada permiso y para qué se utilizan:

### **A. Diagnóstico de Red y Conectividad**

* **Permisos:** INTERNET, ACCESS\_NETWORK\_STATE y ACCESS\_WIFI\_STATE.  
* **Uso:** Permiten a la Aplicación comprobar si el dispositivo está conectado a una red, identificar el tipo de conexión (WiFi o Datos Móviles), evaluar la intensidad de la señal y realizar pruebas básicas de diagnóstico de red.

### **B. Información de Redes Cercanas (Ubicación)**

* **Permisos:** ACCESS\_COARSE\_LOCATION y ACCESS\_FINE\_LOCATION (Ubicación aproximada y precisa).  
* **Uso:** El sistema operativo Android exige estos permisos para permitir que las aplicaciones accedan a los metadatos de las conexiones inalámbricas (como el nombre de la red WiFi o SSID y la dirección MAC del router).  
* **Garantía de Privacidad:** La Aplicación **no** rastrea, registra, mapa ni comparte tu ubicación geográfica real. Este acceso se utiliza estrictamente para completar la tarjeta de información técnica de red en tu pantalla de diagnóstico.

### **C. Estado del Hardware Telefónico**

* **Permiso:** READ\_PHONE\_STATE.  
* **Uso:** Se utiliza para leer información técnica sobre el módem celular (como el tipo de red móvil: 4G, 5G, etc.) y la calidad de la señal de la red del operador telefónico para fines de diagnóstico de conectividad. No se accede a registros de llamadas, contactos ni a tu número de teléfono.

### **D. Optimización de Sensores y Consumo**

* **Permiso:** ACTIVITY\_RECOGNITION (Reconocimiento de Actividad física).  
* **Uso:** Permite a la Aplicación pausar o disminuir la frecuencia de actualización de las lecturas de los sensores físicos (acelerómetro, giroscopio, etc.) cuando detecta que el dispositivo se encuentra en absoluto reposo sobre una superficie, disminuyendo drásticamente el impacto en el consumo de la batería.

## **3\. Servicios de Terceros**

La Aplicación está construida de forma nativa utilizando el SDK de Android y librerías de código abierto de confianza. No integramos SDKs de publicidad de terceros (como Google AdMob), herramientas de análisis de comportamiento (como Firebase Analytics) ni rastreadores de marketing.

Las conexiones de red externas que el framework de desarrollo de la Aplicación pudiera realizar (por ejemplo, a través de la librería Retrofit o Coil para cargar imágenes o validar APIs si el usuario interactúa con funciones externas en el futuro) se rigen por los estándares de encriptación seguros HTTPS y no recopilan identificadores personales del usuario.

## **4\. Retención y Eliminación de Datos**

Dado que todos los datos se almacenan localmente en tu dispositivo:

* Los datos de diagnóstico históricos permanecen en tu base de datos local de Room o en las preferencias de DataStore.  
* Puedes borrar de manera definitiva todos los datos guardados por la Aplicación en cualquier momento yendo a: **Ajustes del Dispositivo \> Aplicaciones \> Override System Monitor \> Almacenamiento \> Borrar Datos**.  
* Al desinstalar la Aplicación, el sistema operativo Android elimina automáticamente toda la base de datos local y los archivos asociados de forma permanente.

## **5\. Privacidad Infantil**

Nuestra Aplicación no recopila intencionalmente datos de niños menores de 13 años (o la edad mínima legal en tu jurisdicción), ya que no recopilamos información personal de ningún usuario en absoluto. La Aplicación es segura para el público en general.

## **6\. Cumplimiento Legal Internacional**

Aunque no recopilamos datos personales, el diseño técnico local de la Aplicación cumple con las directrices de privacidad más estrictas del mundo, incluyendo:

* El Reglamento General de Protección de Datos de la Unión Europea (**RGPD**).  
* La Ley de Privacidad del Consumidor de California (**CCPA**).  
* Las directrices para desarrolladores de **Google Play Store** respecto al uso de permisos de ubicación y estado del teléfono.

## **7\. Cambios a esta Política de Privacidad**

Nos reservamos el derecho de actualizar nuestra Política de Privacidad en el futuro para adaptarla a nuevas características de monitoreo o cambios regulatorios. Cualquier cambio será publicado dentro de la sección de Configuración (*Settings*) de la Aplicación, actualizando la fecha de "Última actualización" en la parte superior de este documento. Te recomendamos revisar esta política periódicamente.

## **8\. Contacto**

Si tienes alguna pregunta o inquietud respecto a cómo tratamos la privacidad en nuestra Aplicación, puedes contactarnos a través de los canales de soporte oficiales provistos en la tienda de aplicaciones o en nuestro repositorio oficial de desarrollo.
