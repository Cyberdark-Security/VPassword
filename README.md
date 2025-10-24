# Ciberseguridad Inteligente: Herramientas para la Vida Diaria

Este proyecto es un sitio web educativo diseñado para talleres y presentaciones sobre ciberseguridad. Su objetivo es concienciar y capacitar a usuarios técnicos y no técnicos sobre prácticas esenciales para proteger su información y vida digital cotidiana.

## Características principales

- Generador de contraseñas seguras, personalizable en longitud y complejidad.
- Evaluador de credenciales que ofrece recomendaciones y verifica exposición en brechas conocidas usando la API pública de [Have I Been Pwned](https://haveibeenpwned.com/API/v3).
- Explicación y simulación básica de autenticación multifactor (MFA).
- Ejercicio interactivo para reconocer correos electrónicos de phishing.

## Tecnologías

- HTML, CSS y JavaScript puro para máxima compatibilidad y facilidad de despliegue.
- API pública de Have I Been Pwned para verificar contraseñas comprometidas.
- Librería jsSHA para cálculo criptográfico SHA-1 en cliente.
  
## Uso

- Clona este repositorio.
- Abre el archivo `index.html` en cualquier navegador moderno para pruebas locales.
- Puedes alojar el sitio directamente en GitHub Pages o desplegar en Vercel para acceso remoto.

## Seguridad

- Este sitio es para fines educativos y no almacena ni transmite información personal ni contraseñas.
- El chequeo de contraseñas con Have I Been Pwned utiliza un mecanismo seguro de anonimato (k-Anonymity) para proteger la privacidad.
- No se debe usar para manejar datos sensibles reales ni como solución de producción sin implementar una capa backend segura.

## Contribuciones

Se aceptan sugerencias y mejoras para pedagogía, accesibilidad y funcionalidades (por favor abre issues o pull requests).

## Licencia

Este proyecto está bajo licencia MIT. Consulta el archivo LICENSE para más detalles.

---

Hecho con propósito educacional para fortalecer la cultura de ciberseguridad.


