# Organigrama del Proyecto - Sistema de Gestión Hotelera

## Estructura Jerárquica del Equipo

```
                    ┌─────────────────────────┐
                    │   GERENTE DE PROYECTO   │
                    │   (Project Manager)     │
                    └────────────┬────────────┘
                                 │
        ┌────────────────────────┼────────────────────────┐
        │                        │                        │
┌───────▼──────┐      ┌─────────▼────────┐      ┌───────▼──────┐
│   ANÁLISIS   │      │   DESARROLLO     │      │   CALIDAD    │
│              │      │                  │      │              │
└──────┬───────┘      └─────────┬────────┘      └──────┬───────┘
       │                        │                      │
┌──────▼───────┐      ┌─────────▼────────┐      ┌──────▼───────┐
│ Analista     │      │ Arquitecto       │      │ QA Lead      │
│ Funcional    │      │ Software         │      │              │
└──────────────┘      └─────────┬────────┘      └──────┬───────┘
                                │                      │
┌──────────────┐      ┌─────────▼────────┐      ┌──────▼───────┐
│ Analista     │      │ Desarrollador    │      │ QA Tester    │
│ Técnico      │      │ Senior (2)       │      │              │
└──────────────┘      └─────────┬────────┘      └──────────────┘
                                │
                      ┌─────────▼────────┐
                      │ Desarrollador    │
                      │ Junior (2)       │
                      └─────────┬────────┘
                                │
                      ┌─────────▼────────┐
                      │ UX/UI Designer   │
                      └─────────┬────────┘
                                │
                      ┌─────────▼────────┐
                      │ DevOps Engineer  │
                      └──────────────────┘
```

## Departamentos y Responsabilidades

### 🎯 **DIRECCIÓN DEL PROYECTO**
- **Gerente de Proyecto**: Liderazgo general, coordinación entre equipos, gestión de stakeholders

### 📊 **ÁREA DE ANÁLISIS**
- **Analista Funcional**: Levantamiento de requerimientos con usuarios de negocio
- **Analista Técnico**: Especificaciones técnicas y arquitectura de datos

### 💻 **ÁREA DE DESARROLLO**
- **Arquitecto de Software**: Diseño de arquitectura, patrones y estándares técnicos
- **Desarrolladores Senior**: Implementación de módulos críticos y mentoring
- **Desarrolladores Junior**: Implementación de funcionalidades bajo supervisión
- **UX/UI Designer**: Diseño de interfaces y experiencia de usuario
- **DevOps Engineer**: Infraestructura, CI/CD y deployment

### 🔍 **ÁREA DE CALIDAD**
- **QA Lead**: Planificación de testing y gestión de calidad
- **QA Tester**: Ejecución de pruebas funcionales y automatización

## Líneas de Reporte

| Rol | Reporta a | Supervisa |
|-----|-----------|-----------|
| Gerente de Proyecto | Dirección Ejecutiva | Todo el equipo |
| Analista Funcional | Gerente de Proyecto | - |
| Analista Técnico | Gerente de Proyecto | - |
| Arquitecto Software | Gerente de Proyecto | Desarrolladores |
| Desarrollador Senior | Arquitecto Software | Desarrolladores Junior |
| Desarrollador Junior | Desarrollador Senior | - |
| UX/UI Designer | Arquitecto Software | - |
| DevOps Engineer | Arquitecto Software | - |
| QA Lead | Gerente de Proyecto | QA Tester |
| QA Tester | QA Lead | - |

## Comités y Reuniones

### 🗓️ **Reuniones Regulares**
- **Daily Standup**: Diario, 15 min - Todo el equipo de desarrollo
- **Sprint Planning**: Cada 2 semanas - Equipo completo
- **Sprint Review**: Cada 2 semanas - Equipo + Stakeholders
- **Retrospectiva**: Cada 2 semanas - Equipo de desarrollo
- **Comité Directivo**: Semanal - PM + Líderes de área

### 📋 **Escalation Path**
1. **Nivel 1**: Desarrollador → Desarrollador Senior
2. **Nivel 2**: Desarrollador Senior → Arquitecto Software
3. **Nivel 3**: Arquitecto Software → Gerente de Proyecto
4. **Nivel 4**: Gerente de Proyecto → Dirección Ejecutiva