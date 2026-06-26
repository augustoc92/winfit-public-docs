---
title: Política de Privacidad
layout: default
---

# Política de Privacidad de Winfit

**Última actualización:** 26 de junio de 2026

Esta política describe cómo Winfit (la "App") recolecta, usa y protege la información de sus usuarios. Al usar Winfit aceptás los términos descritos a continuación.

**Responsable del tratamiento:** {NOMBRE_LEGAL_O_RAZON_SOCIAL}, contacto: winfitsupportcenter@gmail.com.

---

## 1. Datos que recolectamos

Winfit recolecta únicamente la información necesaria para operar las funcionalidades de la App:

### 1.1 Datos de cuenta
- **Email** y datos de autenticación.
- **Nombre/alias** y avatar elegido por el usuario.

### 1.2 Datos de actividad física
- **Pasos diarios**: leídos del sensor de movimiento del dispositivo.
  - En iOS, a través de Core Motion / CMPedometer (permiso `NSMotionUsageDescription`).
  - En Android, a través de Health Connect, con el permiso `android.permission.health.READ_STEPS` y `android.permission.ACTIVITY_RECOGNITION`.
- **Registros de entrenamiento** ingresados por el usuario (tipo de actividad, duración, ubicación opcional).

### 1.3 Ubicación
- **Coordenadas de geolocalización** únicamente cuando el usuario registra un entrenamiento que requiere validar la ubicación. Permiso `NSLocationWhenInUseUsageDescription` (iOS) y `ACCESS_FINE_LOCATION` / `ACCESS_COARSE_LOCATION` (Android). La App no recolecta ubicación en segundo plano.

### 1.4 Cámara y fotos
- **Fotos** que el usuario decide tomar o seleccionar como evidencia de un entrenamiento. Permiso `NSCameraUsageDescription` y `NSPhotoLibraryUsageDescription` (iOS); `CAMERA` (Android).

### 1.5 Datos técnicos
- Identificador anónimo de dispositivo, sistema operativo, versión de la App. Se usan exclusivamente para diagnóstico de errores.

**No recolectamos** datos sensibles distintos a los descriptos, ni datos de contactos, navegación web, o información financiera.

---

## 2. Para qué usamos los datos

| Dato | Finalidad |
|------|-----------|
| Email + auth | Identificarte y permitirte ingresar a tu cuenta. |
| Pasos diarios | Mostrarte tu progreso y validar la finalización de desafíos basados en pasos. |
| Entrenamientos | Llevar tu historial y calcular tu progreso en desafíos. |
| Ubicación | Validar dónde se realizó un entrenamiento (solo cuando el usuario lo registra). |
| Fotos | Adjuntar evidencia visual de entrenamientos elegida por el usuario. |
| Datos técnicos | Detectar y corregir errores de la App. |

Los datos de Health Connect se manejan conforme a la [Health Connect Privacy Policy de Google](https://developer.android.com/health-and-fitness/guides/health-connect/develop/privacy). Solo se accede a los pasos del día actual, agregados por fuente, y únicamente cuando el usuario abre la App o un desafío activo.

---

## 3. Cómo almacenamos y protegemos los datos

- Los datos de cuenta y de actividad se almacenan en servidores administrados (Railway) protegidos mediante TLS en tránsito y aislamiento por usuario.
- Las contraseñas (cuando aplica) se almacenan **hasheadas**, nunca en texto plano.
- Los tokens de sesión se guardan en el almacenamiento seguro del dispositivo (`expo-secure-store`).
- No almacenamos datos biométricos ni de salud distintos a los pasos diarios descriptos.

---

## 4. Con quién compartimos los datos

**No vendemos, alquilamos ni cedemos datos personales a terceros con fines publicitarios.**

Los datos solo pueden compartirse en los siguientes casos:
- Con proveedores estrictamente necesarios para operar la App (hosting, autenticación), sujetos a obligaciones de confidencialidad equivalentes a esta política.
- Cuando lo requiera una autoridad competente por orden legal.

---

## 5. Tus derechos

Como usuario podés en cualquier momento:

- **Acceder** a los datos que tenemos sobre vos.
- **Corregir** datos inexactos.
- **Eliminar** tu cuenta y todos los datos asociados.
- **Revocar permisos** desde la configuración de tu dispositivo (Health Connect, ubicación, cámara, etc.).

Para ejercer cualquiera de estos derechos, escribinos a **winfitsupportcenter@gmail.com** indicando el motivo. Procesamos los pedidos de eliminación en un plazo máximo de 30 días.

---

## 6. Retención de datos

- Los datos se conservan mientras la cuenta esté activa.
- Si pedís la eliminación, tus datos se borran completamente de la base productiva dentro de los 30 días. Los backups se purgan en los ciclos rotativos habituales (máximo 90 días).

---

## 7. Menores de edad

Winfit no está dirigida a menores de 13 años. Si detectamos que se ha creado una cuenta con datos de un menor sin autorización, la eliminaremos.

---

## 8. Cambios a esta política

Podemos actualizar esta política cuando agreguemos nuevas funcionalidades o cambien los requisitos legales. La versión vigente siempre estará disponible en esta misma URL, con la fecha de última actualización al inicio del documento. Los cambios materiales se notifican dentro de la App.

---

## 9. Contacto

Cualquier consulta sobre privacidad: **winfitsupportcenter@gmail.com**.
