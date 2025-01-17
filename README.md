# Reducción de Ruido en Audios

Este proyecto aborda la reducción de ruido en grabaciones de audio, utilizando técnicas tradicionales y modernas de procesamiento de señales. El objetivo es mejorar la calidad de grabaciones con ruido ambiental, específicamente en una entrevista televisiva grabada en un entorno doméstico.

## Contenido del Repositorio

- **`audio_v3.ipynb`**: Código fuente en Python para el procesamiento y análisis del audio.
- **`maicon_fialho_series_temporales.pdf`**: Informe detallado con la metodología, resultados y conclusiones del proyecto.

## Metodología

1. **Análisis del Audio Original**:
   - Visualización de la forma de onda.
   - Análisis de frecuencias mediante la Transformada de Fourier.

2. **Reducción de Ruido**:
   - Filtro por Media Móvil:
     - Atenúa variaciones rápidas en la señal.
     - Usa una ventana de tamaño 5.
   - Filtro Pasa-Banda:
     - Preserva frecuencias relevantes de la voz humana (50 Hz a 3400 Hz).
   - Algoritmo de Gating Espectral (`noisereduce`):
     - Reduce ruido sin comprometer la calidad de la voz.

3. **Evaluación**:
   - Comparación de formas de onda antes y después del procesamiento.

## Requisitos

- Python 3.12.2
- Bibliotecas:
  - `numpy`
  - `matplotlib`
  - `librosa`
  - `noisereduce`

Instale las dependencias con:
```bash
pip install -r requirements.txt
```

## Ejecución

1. Clone el repositorio:
```bash
git clone https://github.com/maiconfialho/series_teporales_audio.git
cd series_teporales_audio
```

2. Abra el archivo `audio_v3.ipynb` en Jupyter Notebook y ejecute las celdas en orden.

---

