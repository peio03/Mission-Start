# Tareas Manuales Recurrentes – Estado Actual

## 1. Instalación de herramientas
- Instalar Node.js y npm
- Instalar Git
- Instalar VS Code y extensiones necesarias

## 2. Configuración inicial del proyecto
- Crear package.json (npm init -y)
- Crear scripts de build/start
- Crear estructura de carpetas (src/, docs/)

## 3. Trabajo diario
- Ejecutar build manualmente (npm run build)
- Formatear archivos manualmente con Prettier
- Ejecutar ESLint manualmente

## 4. Comprobaciones de versiones
- Revisar versiones de Node, npm y Git manualmente
- Verificar compatibilidad de dependencias

## 5. Observación
Todas estas tareas son repetitivas y **podrían ser automatizadas** mediante:
- Scripts de inicialización (`npm init`, copiar estructura)  
- Pre-configuración de VS Code (`settings.json`, extensiones)  
- Tareas automatizadas en package.json (`scripts`)  
- CI/CD básico para build y lint