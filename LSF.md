# LRL Scientific Framework

> [!CAUTION]
> Usar Sistema Internacional de Unidades (SI).
>
> Mantener consistencia dimensional en procesos matemáticos.
>
> Estabilizar, aislar y limpiar el entorno de medición para no afectar las lecturas y registros.
>
> Leer etiquetas SGA, límites físicos y posibles reacciones químicas y cambios de estado de agregación en interfaces del experimento.

1. **Medir**
    1. Calibrar sensores.
    2. Realizar y medir el experimento reiteradamente (opcionalmente bajo diferentes condiciones iniciales).
    3. Estudiar y graficar.
        - **Cifras Significativas:** Dígitos de un número que aportan información válida sobre su grado de exactitud.
        - **Error**
            
            **Relativo:** Relación adimensional entre el error absoluto y el valor de referencia. Útil para determinar la influencia de factores externos sobre la medición.
            
            Error relativo de $A$ en función de $B$: $\left|\frac{\text{A}-\text{B}}{\text{B}}\right|\times100\%$
            
            **Absoluto:** Diferencia entre el valor real y el valor medido.
            
            $|A-B|$
            
            **Error estándar de la media:** Mide la precisión de la media muestral respecto a la verdadera media de toda la población.
            
            $EEM=\frac{\sigma}{\sqrt{n}}$
            
            **Propagación de Error:**
            
            $\sigma_f=\sqrt{\sum\left(\frac{\delta f}{\delta x_i}\sigma_{x_i}\right)^2}$
            
        - **Estadística**
            - **Frecuencias:** Absoluta, Acumulada, Relativa, Relativa Acumulada, Porcentual, Porcentual Acumulada
            - **Desviaciones:** Estándar, Media
            - **Primordiales:** Intervalo, Moda, Media, Mediana
            - **Otros:** Curva de Distribución Normal (Gauss)
        - **Métricas**
            
            $MAE=\frac{1}{n}\sum_{i=1}^n|y_i-\hat{y}_i|$
            
            $RMSE=\sqrt{\frac{1}{n}\sum_{i=1}^n(y_i-\hat{y}_i)^2}$
            
            $R^2=1-\frac{\sum_{i=1}^n(y_i-\hat{y}_i)^2}{\sum_{i=1}^n(y_i-\overline{\mu})^2}$
            
            Donde:
            
            - $n$ es el número total de muestras.
            - $y_i$ es el valor real de la muestra $i$.
            - $\hat{y}_i$ es el valor predicho para la medición $i$.
            - $\overline{\mu}$ es el promedio de todas las muestras: $\overline{\mu}=\frac{1}{n}\sum_{i=1}^ny_i$
    4. Comparar (si no es el primer experimento).
    5. Ajustar y repetir.
2. **Modelar**
    1. Hipótesis estructurada que, bajo ciertos supuestos, relaciona variables del sistema para explicar y predecir resultados contrastables con observaciones.
        - Vector de estado $\textbf{x}(t)\in\mathbb{R}^n$
        - Parámetros $\theta\in\mathbb{R}^p$
        - Entrada (si aplica) $\textbf{u}(t)$
        - Condiciones iniciales $\textbf{x}(0)$
    
    $\frac{d\textbf{x}}{dt}=f(\textbf{x},\textbf{u},\theta,t,\dots)$
    
3. **Integración en el tiempo**
4. **Tabla de datos**
5. **Exportación** (CSV, JSON, Binario…)
6. **Animación (si aplica Mecánica: Blender, Cinema 4D…)**
