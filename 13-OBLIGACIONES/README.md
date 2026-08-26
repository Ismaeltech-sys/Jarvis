# 13-OBLIGACIONES

## Qué va aquí

Pagos recurrentes y servicios contratados. Una entrada por servicio en `servicios/`.

Sirve para recordar referencias de pago (no montos sensibles ni cuentas bancarias) y para no olvidar renovaciones.

## Cuándo agregar algo

- Contrataste un servicio recurrente (internet, hosting, suscripción SaaS, gimnasio).
- Cambiaste de plan o de proveedor.
- Necesitás recordar la referencia de pago de algo que pagás cada mes.

## Cuándo NO agregar acá

- **Pagos únicos o esporádicos.** No tiene sentido archivarlos acá.
- **Datos bancarios sensibles.** Nunca. Ni nombre de banco + número de cuenta juntos en plano.
- **Finanzas por proyecto.** Esas van a `09-FINANCE/`.

## Subcarpetas

- **`servicios/`** - un archivo por servicio.

## Ejemplo genérico

`13-OBLIGACIONES/servicios/internet-casa.md`

```
# Internet casa

- **Proveedor:** <nombre>
- **Plan:** <descripción del plan>
- **Día de pago:** 15 de cada mes
- **Referencia de pago:** <referencia que te pide el portal del proveedor, NO el número de cuenta>
- **Método:** débito automático / pago manual
- **Notas:** soporte 24/7, número de cliente XXXXX
```

## Regla de oro

Acá van **referencias para encontrar el pago en el portal del proveedor**. Nunca montos como objetivo de almacenamiento sensible.
