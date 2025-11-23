# Análisis de Desempeño Académico con Reglas de Asociación

## Descripción del Proyecto
Análisis de datos educativos utilizando el algoritmo Apriori para identificar patrones asociados con el alto desempeño académico en estudiantes.

## Objetivo
Identificar combinaciones de factores (características demográficas, preparación, recursos) que se asocian con alto rendimiento académico.

## Dataset
- **Fuente:** StudentsPerformance.csv
- **Registros:** 1,000 estudiantes
- **Variables:** Género, etnia, educación parental, almuerzo, curso preparatorio, calificaciones

## Tecnologías Utilizadas
- Python 3.x
- Pandas
- Scikit-learn
- Mlxtend (Apriori)
- Matplotlib/Seaborn
- Google Colab

## Métricas de Asociación
- Soporte
- Confianza  
- Lift

## Instalación y Uso
```bash
git clone https://github.com/tu-usuario/Analisis-Desempeno-Academico-Reglas-Asociacion.git
cd Analisis-Desempeno-Academico-Reglas-Asociacion
pip install -r requirements.txt
jupyter notebook ImplementaciondeModeloAsociacion.ipynb
