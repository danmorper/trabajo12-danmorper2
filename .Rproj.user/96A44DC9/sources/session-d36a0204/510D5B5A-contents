# Instalar la librería ggplot2 si es necesario
if (!require("ggplot2")) install.packages("ggplot2")
library(ggplot2)

# Datos
hours_played <- c(0, 15, 3, 5, 5, 0, 13, 8, 7, 17, 18, 10)
performance_scores <- c(4.00, 2.5, 4.0, 3.9, 3.75, 3.8, 2.9, 3.1, 3.25, 1.5, 1.75, 2.98)

# Crear Dataframe
data <- data.frame(hours_played, performance_scores)

# Diagrama de dispersión
ggplot(data, aes(x = hours_played, y = performance_scores)) +
  geom_point() + 
  theme_minimal() +
  labs(title = "Relación entre las horas de videojuego y el rendimiento académico",
       x = "Horas de videojuegos a la semana",
       y = "Rendimiento Académico") +
  geom_smooth(method = "lm", se = FALSE, color = "blue") # Regresión lineal (no se pide pero suele resultar útil en un diagrama de dispersión)



