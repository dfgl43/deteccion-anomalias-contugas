# Detección de Anomalías en Consumo de Gas - Contugas

Sistema de detección de anomalías para el análisis del consumo de gas natural en clientes industriales de Contugas S.A.C., filial del Grupo Energía Bogotá en Perú.

## 📋 Descripción del Proyecto

Este proyecto desarrolla una solución de análisis de datos avanzada para detectar comportamientos atípicos en el consumo de gas natural de clientes industriales. Utilizando técnicas de machine learning, el sistema identifica anomalías en tiempo real considerando las variables operativas clave: **presión**, **temperatura** y **volumen** de gas.

### Contexto del Negocio

Contugas S.A.C. es la empresa encargada de la distribución y comercialización de gas natural en la región de Ica, Perú. Con más de 74,000 clientes y 1,836 kilómetros de redes de distribución, la empresa enfrenta el desafío de detectar anomalías que pueden tener múltiples orígenes:

- Corrosión y fugas en tuberías
- Fallas en medidores
- Daños estructurales
- Intervenciones externas
- Problemas de oxidación

## 🎯 Objetivos

El sistema desarrollado busca:

1. **Visualizar** datos históricos de consumo por cliente
2. **Generar** resúmenes descriptivos del comportamiento histórico
3. **Identificar** consumos anómalos y variaciones atípicas
4. **Alertar** sobre comportamientos críticos en tiempo real
5. **Proporcionar** una interfaz amigable para usuarios operativos

## 🔧 Tecnologías Utilizadas

- **Python**: Lenguaje principal de desarrollo
- **Machine Learning**: Modelos de detección de anomalías
- **Dashboard**: Visualización interactiva de resultados
- **Procesamiento de Datos**: Manejo de mediciones horarias

## 📊 Datos del Proyecto

El sistema procesa mediciones horarias que incluyen:
- **Presión** [bar]
- **Temperatura** [°C] 
- **Volumen de gas** [m³]
- Variables de identificación del cliente

## 🚀 Funcionalidades Principales

### 1. Análisis Exploratorio
- Visualización de series temporales por cliente
- Estadísticas descriptivas del consumo histórico

### 2. Detección de Anomalías
- Modelos de machine learning para detección en tiempo real
- Sistema de alertas por criticidad

### 3. Dashboard Interactivo
- Monitoreo en tiempo real del consumo
- Visualizaciones por cliente industrial
- Reportes de anomalías detectadas
- Interfaz intuitiva para equipos operativos

## 📁 Estructura del Repositorio

```
deteccion-anomalias-contugas/
├── LICENSE
├── README.md
├── tabla_requerimientos/
│   └── tabla_requerimientos.xlsx
├── docs/
│   └── documento_tecnico_experimentos.pdf
│   └── manual_usuario.docx
├── codigo/
│   ├── Calidad_datos y etiquetas_manuales.ipynb
│   ├── Modelo_anomalias.ipynb
│   ├── modelo_isolation_cluster_0.pkl
│   ├── modelo_isolation_cluster_1.pkl
│   ├── modelo_isolation_cluster_2.pkl
│   ├── modelo_isolation_cluster_3.pkl
├── data/
│   ├── raw/
│       └── datos.xlsx
```

## 💼 Impacto Empresarial

Este proyecto forma parte de la iniciativa estratégica del Grupo Energía Bogotá para modernizar sus procesos operativos mediante analítica de datos, con el objetivo de:

- Reducir costos operativos de monitoreo
- Mejorar la detección temprana de problemas
- Optimizar el mantenimiento predictivo
- Aumentar la confiabilidad del servicio

## 🏆 Resultados Esperados

El producto mínimo viable (MVP) debe cumplir con métricas de desempeño que generen un retorno económico positivo, integrándose efectivamente en los flujos de trabajo operativos de Contugas.

## 📈 Estado del Proyecto

**Finalizado** - Proyecto académico de la Maestría en Inteligencia Analítica de Datos (MIAD) de la Universidad de los Andes de Colombia .

---

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🤝 Colaboradores

Proyecto desarrollado como parte del programa MIAD de la Universidad de los Andes en colaboración con el equipo de innovación del Grupo Energía Bogotá.

**Nota**: Este es un proyecto académico desarrollado con fines educativos y de investigación.
