# Instala y carga el paquete OpenAir
#install.packages("openair")

#Libreria usada para la plicacion de eel analisis de eel aire 
library(openair)

# Carga los datos de calidad del aire (Datos dee prueba dados por la libreria)
data <- importAURN()

# Visualización básica: histograma de concentración de NO2
hist(data$nox, main = "Histograma de concentración de NO2", xlab = "Concentración de NO2")

# Visualización más avanzada: gráfico de serie temporal
timePlot(data, pollutant = "nox", smooth = TRUE)

