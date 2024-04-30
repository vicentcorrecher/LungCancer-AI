<body>
<p align="center">
  <img src="APP GRADIO/Foto.jpeg" style="width: 250px;">
</p>

  <h1>Sistema de predicción de malignidad de cáncer de pulmón</h1>



  <p>Este repositorio contiene el código y los recursos relacionados a un proyecto propio en el que se ha desarrollado un sistema de predicción de malignidad de cáncer de pulmón. 
    El sistema se ha diseñado como una herramienta predictiva para ayudar en la toma de decisiones y seguimiento de la enfermedad, utilizando imágenes médicas y técnicas de clasificación.</p>

  <a href="https://drive.google.com/drive/folders/1-Tbos5aCdj8Qgy_Rz5d8T8tbtm-42TiF?usp=sharing">[Enlace al repositorio en Google Drive]</a>.
  Desde ahí se puede acceder a todo el repositorio y los modelos guardados para ejecutar directamente desde Google Colab.

  <h2>Datos</h2>

  <p>El conjunto de datos utilizado para este proyecto es la base de datos de <a href="https://luna16.grand-challenge.org/">Lung Cancer Analysis 2016</a>.
    Los datos se han procesado para obtener tres conjuntos diferentes: 
    un conjunto normal, otro tratado con técnicas de mejora del contraste y un tercer conjunto generado mediante técnicas de data augmentation.</p>

  <h2>Modelos</h2>
  
  <p>Se han entrenado varios modelos para abordar el problema de clasificación, incluyendo:</p>
  <ul>
    <li> Modelos basados en Convolutional Neural Networks (CNNs).</li>
    <li>  Modelos basados en la UNet clásica.</li>
    <li>  Modelos basados en la arquitectura Inception Net.</li>
  </ul>

  <h2>Aplicación</h2>

  <p>Además del código de los modelos, se ha desarrollado una aplicación utilizando Gradio. Esta aplicación permite cargar una imagen de una tomografía computarizada de baja dosis y obtener como resultado la imagen procesada con heatmaps y la predicción del modelo.</p>

  

  <h2>Estructura del Repositorio</h2>
  <pre>
    ├── data/                      # Directorio para almacenar los conjuntos de datos
    ├── models/                    # Directorio para almacenar los modelos entrenados
    ├── app/                       # Directorio de la aplicación Gradio
    ├── notebooks/                 # Notebooks de Jupyter utilizados para el desarrollo y análisis
    └── README.md                  # Este archivo README
  </pre>

  <h2>Contribución</h2>

  <p>Si deseas contribuir o preguntar cualquier duda sobre este proyecto, ¡Contacta por LinkedIn! Y siéntete libre de crear pull requests con tus contribuciones.</p>

  <h2>Créditos</h2>

  <p>Este proyecto ha sido desarrollado por <a href="#"> Vicent Muñoz Correcher </a>.</p>

  <h2>Licencia</h2>

  <p>Este proyecto está bajo la licencia <a href="#">MIT 2.0</a>.</p>
</body>
</html>
