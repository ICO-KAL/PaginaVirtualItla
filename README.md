# CONTROL-SOPORTE-CODEX

Sistema de gestión de tickets y soporte técnico del Instituto Tecnológico de Las Américas (ITLA).

##  Características

- ✅ Portal separado para Estudiantes
- ✅ Portal separado para Administradores
- ✅ Sistema de autenticación
- ✅ Gestión completa de tickets
- ✅ Sistema de roles y categorías
- ✅ Reportes y estadísticas
- ✅ Interfaz moderna y responsiva
- ✅ Almacenamiento en memoria (Next.js) o Base de datos MySQL (PHP)

## 📋 Requisitos

- Node.js 18 o superior
- npm o pnpm
- (Opcional) PHP 7.4+ y MySQL para la versión con base de datos

##  Instalación

```bash
# Instalar dependencias
npm install

# Ejecutar en modo desarrollo
npm run dev
```

##  URLs de Acceso

- **Página Principal**: http://localhost:3000
- **Portal Estudiante**: http://localhost:3000/estudiante
- **Portal Admin**: http://localhost:3000/admin

##  Credenciales de Prueba

**Estudiante:**
- Email: `juan.perez@itla.edu.do`
- Password: `Itla2024!`

**Admin:**
- Email: `supremo@itla.edu.do`
- Password: `Itla2024!`

## Documentación

Para más detalles, consulta:
- `EJECUCION_COMPLETA.md` - Guía completa de ejecución
- `GUIA_DE_INSTALACION.md` - Guía de instalación detallada
- `INICIO_RAPIDO.md` - Inicio rápido

##  Estructura del Proyecto

```
itlasoporteestudiantil/
├── app/                    # Páginas Next.js
│   ├── admin/             # Portal de administración
│   ├── estudiante/        # Portal de estudiantes
│   └── page.tsx           # Página principal
├── components/            # Componentes React
│   ├── admin/            # Componentes del portal admin
│   ├── student/          # Componentes del portal estudiante
│   └── ui/               # Componentes UI reutilizables
├── lib/                   # Utilidades y tipos
├── itla-soporte-estudiantil/  # Aplicación Vite + PHP (Alternativa)
│   ├── backend/       # Backend PHP
│   └── services/          # Cliente API
└── package.json          # Dependencias Node.js
```

##  Licencia

Este proyecto es propiedad de AXEL Y STARLIN

##  Contribuidores

- ITLA Development Team

##  Contacto

Para más información, contacta a: AXSTechnology@proton.me
