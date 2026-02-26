# Modelo SMC v1.0
Indicadores:
No se utilizan indicadores en la versión v1.0.
Modelo basado únicamente en estructura de precio.
## Hipótesis
El modelo funciona cuando 15M manda, 5M confirma, 1M ejecuta.

## Estructura
HTF: 15M
Confirmación: CHoCH en 5M + retroceso
Entrada: micro-CHoCH en 1M

## Gestión
RR mínimo:
Riesgo por trade:
Máximo trades por sesión:

## Condiciones inválidas
- Rango sin liquidez tomada
- Noticias alto impacto
- Sin desplazamiento claro

## Resultados esperados
Winrate estimado:
Drawdown tolerable:
---

## Registro de Test

Periodo evaluado:
Cantidad de trades:
Winrate:
RR promedio:
Drawdown máximo:
Errores de ejecución:
Notas psicológicas:
Periodo evaluado: 26/02/2026 - 12/03/2026
Tipo de validación: Baseline sin modificaciones

Cantidad de trades:
Winrate:
RR promedio:
Drawdown máximo:
Errores de ejecución:
Notas psicológicas:
---

## Diario de Operaciones

### Trade 1
Fecha:
Activo:
Sesión:
Setup válido según reglas (sí/no):
RR planificado:
Resultado:
Error de ejecución (sí/no):
Comentario breve:
### Día sin operación
Fecha:
Motivo: No hubo confirmación válida según reglas v1.0.
Máximo trades por día: 2
No se permite tercer trade bajo ninguna circunstancia.
Si ocurre error de ejecución, no se habilita trade adicional.
El límite de 2 trades diarios es absoluto.
Confirmación 5M:
Solo se considera CHoCH válido con cierre estructural.
No se aceptan quiebres solo con mecha.
