# Copago Claro

Demo funcional para el reto 3 del hackIAthon: **Estimador Agéntico de Copago y Cobertura para el Paciente**.

## Problema

Antes de atenderse, las personas necesitan saber qué especialidad consultar, qué centro de la red conviene y cuánto pagarán. La incertidumbre genera abandonos y sorpresas en caja.

## Solución

Copago Claro recibe una descripción breve de la necesidad, el plan y el tipo de atención. Con datos de demostración:

1. Sugiere una especialidad mediante reglas transparentes.
2. Aplica cobertura y deducible según el plan.
3. Ajusta la tarifa para una atención de emergencia.
4. Ordena hospitales de red por copago estimado.
5. Desglosa cada componente de la estimación.

## Alcance de la demo

Los planes, tarifas, hospitales y reglas son ficticios. La aplicación no solicita datos identificables ni toma decisiones médicas; el resultado siempre se comunica como orientación y no como autorización de seguro.

## Arquitectura

Aplicación web estática de una sola página, sin persistencia ni transferencia de datos. El motor de cálculo vive en el navegador para que sea auditable en la demostración.

## Próxima evolución

- Integrar datos de pólizas y red mediante API segura.
- Sustituir reglas por clasificación asistida por IA con guardrails clínicos.
- Añadir autenticación, consentimiento y trazabilidad de cada estimación.
- Confirmar elegibilidad en tiempo real antes de presentar un valor final.

## Ejecución local

Abrir `index.html` en un navegador o servir el directorio con cualquier servidor HTTP estático.
