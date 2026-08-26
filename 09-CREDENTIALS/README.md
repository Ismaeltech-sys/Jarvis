# 09-CREDENTIALS

## Qué va aquí

**Solo referencias** a credenciales. Los valores reales viven en tu keychain del sistema (macOS Keychain, Bitwarden, 1Password, etc.).

Acá registras:
- Qué servicios usas
- Cómo se llama la entrada en tu keychain
- Email/usuario asociado
- Plan o tier contratado
- Fecha de renovación
- Para qué proyecto se usa

## Cuándo agregar algo

- Contrataste un servicio nuevo (API, SaaS, hosting).
- Cambiaste de cuenta o de plan en algo existente.
- Necesitas que tu asistente sepa qué credencial usar en qué proyecto.

## Cuándo NO agregar acá

- **NUNCA escribas tokens, passwords, API keys en estos archivos.** Si te encuentras a punto de pegar uno, párate y guárdalo en el keychain.

## Ejemplo genérico

`09-CREDENTIALS/mi-proveedor-de-hosting.md`

```
# mi-proveedor-de-hosting

- **Servicio:** Hosting cloud
- **Cuenta:** tu-email@ejemplo.com
- **Plan:** Tier básico ($X/mes)
- **Renovación:** mensual, día 15
- **Keychain entry:** `hosting-cloud-token`
- **Usado en:** proyecto-A, proyecto-B
- **Notas:** límite de 100GB/mes en este tier
```

## Cómo lee tu asistente este folder

Cuando necesite credenciales para un proyecto:
1. Lee el `.md` del servicio relevante.
2. Identifica el `Keychain entry`.
3. Pide al sistema operativo el valor por nombre de entry (nunca lo lee desde acá).
