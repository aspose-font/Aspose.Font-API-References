---
title: "System::Security::Permissions::SecurityPermissionFlag enum"
linktitle: "SecurityPermissionFlag"
second_title: "Aspose.Font para C++"
description: "System::Security::Permissions::SecurityPermissionFlag enum. Indicadores del permiso de seguridad en C++."
type: docs
weight: 300
url: /es/cpp/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag enum


Banderas del permiso de seguridad.

```cpp
enum class SecurityPermissionFlag
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| NoFlags | 0 | Sin acceso. |
| Aserción | 1 | Asegura que se haya concedido el permiso. |
| UnmanagedCode | 2 | Llama a código no administrado. |
| SkipVerification | 4 | Omitir la verificación de código. |
| Ejecución | 8 | Ejecutar código. |
| ControlThread | 16 | Realizar operaciones en hilos. |
| ControlEvidence | 32 | Controlar o modificar la evidencia CLR. |
| ControlPolicy | 64 | Ver y cambiar la política. |
| SerializationFormatter | 128 | Serializar. |
| ControlDomainPolicy | 256 | Establecer la política de dominio. |
| ControlPrincipal | 512 | Controlar el objeto principal. |
| ControlAppDomain | 1024 | Controlar el dominio de aplicación. |
| RemotingConfiguration | 2048 | Configurar la comunicación remota. |
| Infraestructura | 4096 | Conectar a la infraestructura CLR. |
| BindingRedirects | 8192 | Realizar redirección de enlace explícita. |
| AllFlags | 16383 | Sin restricciones. |

## Ver también

* Namespace [System::Security::Permissions](../)
* Library [Aspose.Font for C++](../../)
