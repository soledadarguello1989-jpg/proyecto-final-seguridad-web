# Proyecto final: Sistema de Rol de Pagos con control de versiones y seguridad web

Este proyecto simula el desarrollo de un sistema de rol de pagos, aplicando control de versiones mediante GitHub y buenas prácticas de seguridad web.

El sistema contiene funciones relacionadas con:

- Cálculo de sueldo
- Horas extras
- Bonificación
- Atrasos
- Neto a pagar
- Cálculo de IESS
- Comisiones
- Alimentación
- Impuesto a la renta

Además, se simula el proceso de seguridad para el ingreso al sistema mediante login, contraseña robusta y código enviado al teléfono móvil.

## Objetivo del proyecto

Integrar GitHub con buenas prácticas de seguridad web, simulando cambios realizados durante el desarrollo de un sistema de rol de pagos en ambientes de Desarrollo, Certificación y Producción.

## Ambientes simulados

| Ambiente | Configuración | Fecha simulada |
|---|---|---|
| Desarrollo | Creación login inicial | ene-26 |
| Desarrollo | Manual validación contraseñas | ene-26 |
| Certificación | Error contraseñas débiles | feb-26 |
| Certificación | Retorno versión anterior v1.2 | mar-26 |
| Producción | Corrección final v1.4 | dic-26 |

## Control de versiones simulado

| Versión | Descripción | Estado |
|---|---|---|
| v1.0 | Creación inicial del sistema de rol de pagos | Estable |
| v1.1 | Creación de login inicial | Estable |
| v1.2 | Manual de validación de contraseñas | Estable |
| v1.3 | Error detectado: contraseñas débiles permitidas | Con error |
| v1.2 | Retorno a versión anterior estable | Restaurada |
| v1.4 | Corrección final de validación de contraseñas | Estable |

## Error detectado

Durante la etapa de certificación se detectó que el sistema permitía contraseñas débiles como:

- 123456
- admin
- password

Este error representaba un riesgo para el acceso al sistema de rol de pagos, ya que podía permitir accesos no autorizados a información sensible del personal.

## Acción correctiva

Se decidió volver temporalmente a la versión anterior estable v1.2. Luego se corrigió la validación de contraseñas y se generó la versión final v1.4 para producción.
