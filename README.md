# Laboratorio 11

# Finalidad del archivo `vercel.json`
El archivo `vercel.json` se utiliza para configurar el comportamiento de una aplicación en Vercel, como las rutas, funciones serverless, variables de entorno y la forma en que se construye y despliega la aplicación.

---

# Ventajas de desplegar en Vercel frente a un servidor tradicional

1. **Escalabilidad automática**: Los recursos se ajustan según la demanda, sin necesidad de gestionar servidores manualmente.
2. **Despliegue sencillo**: Integra fácilmente el código con plataformas como GitHub para realizar despliegues automáticos.
3. **Optimización de rendimiento**: Vercel ofrece una red global de entrega de contenido (CDN) y optimización automática de recursos estáticos.
4. **Funciones serverless**: Permite ejecutar funciones solo cuando se necesitan, reduciendo costos y simplificando la infraestructura.

---

# Propiedades necesarias en `vercel.json` para una aplicación Express

1. **`version`**: Define la versión de Vercel para el despliegue.
2. **`builds`**: Especifica cómo se debe construir la aplicación, usando generalmente `"@vercel/node"` para aplicaciones Express.
3. **`functions`**: Configura los recursos y tiempos de ejecución para las funciones serverless que manejan las solicitudes de Express.

## Jonathan Daniel Hernandez Godoy - 00015322
## Enlace al proyecto: https://00015322.vercel.app/
