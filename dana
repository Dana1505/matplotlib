import matplotlib.pyplot as plt

# Datos
anemia = [70.4, 59.4, 58.3, 54.2, 51.9, 49.5, 46.3, 43.9, 43.1]
desnutricion = [26.1, 21.7, 19.9, 18.2, 16.3, 14.1, 14.5, 10.3, 11.5]
suplemento = [45.7, 42.9, 31.4, 29.5, 30.8, 28.5, 24.3, 23.4, 32.0]

# Etiquetas para las barras
departamentos = ['Puno', 'Ucayali', 'Madre de Dios', 'Huancavelica', 'Loreto', 'Amazonas', 'Apurímac', 'Ica', 'Total']

# Crear el gráfico
plt.figure(figsize=(10, 6))
plt.bar(departamentos, anemia, label='Anemia')
plt.bar(departamentos, desnutricion, label='Desnutrición Crónica')
plt.bar(departamentos, suplemento, label='Consumo de Suplemento de Hierro')

# Agregar etiquetas y título
plt.xlabel('Departamento')
plt.ylabel('Tasa (%)')
plt.title('Anemia y Desnutrición Crónica en Niños en Perú')
plt.legend()

# Mostrar el gráfico
plt.show()
