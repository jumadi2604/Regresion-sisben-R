<img width="612" height="538" alt="image" src="https://github.com/user-attachments/assets/3d64ee5d-5e01-4263-ad47-e95a70cfa33b" />

- 🇬🇧 **English summary:** Multiple linear regression model to predict 
- socioeconomic scores (SISBÉN IV) for Colombian households. 
- Built with R using LASSO, Stepwise selection, and full 
- assumption diagnostics. R²=0.52 on real government data.

# Regresión Lineal Múltiple – Puntaje SISBÉN IV

Análisis estadístico completo en R para modelar el puntaje de 
focalización socioeconómica de hogares colombianos.

## ¿Qué incluye?
- Análisis descriptivo y matriz de correlaciones
- Selección de variables para parcimonia del modelo: Stepwise, LASSO, R² ajustado, Cp
- Verificación de supuestos: normalidad, homocedasticidad, VIF
- Diagnóstico de outliers e influencias (Cook's D, leverage)
- Modelo con variables indicadoras e interacciones
- Intervalos de confianza y predicción

## Herramientas
R · glmnet · car · leaps · ggplot2

## Impacto y aplicaciones

Este modelo permite estimar el puntaje SISBÉN de hogares 
no encuestados a partir de variables socioeconómicas observables, 
lo que puede apoyar a entidades públicas en la priorización 
de recursos y la identificación de poblaciones vulnerables 
en Colombia — reduciendo la dependencia de encuestas costosas.

## Conclusiones clave
- Las variables de vivienda y acceso a servicios públicos 
  explican la mayor parte de la variación en el puntaje (R²=0.52)
- El modelo cumple todos los supuestos de regresión clásica, 
  lo que garantiza inferencias válidas
- La selección de variables con LASSO y Stepwise redujo 
  la dimensionalidad sin sacrificar poder predictivo
