<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->

<a id="readme-top"></a>

<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://lse.posgrados.fi.uba.ar/posgrados/especializaciones/inteligencia-artificial">
    <img src="readme/logoFIUBA.jpg" alt="Logo" width="500">
  </a>

<h3 align="center">Procesamiento de Lenguaje Natural</h3>

  <p align="center">
    Especializacion en Inteligencia Artificial
  </p>
</div>

<!-- ABOUT THE PROJECT -->

## About

[![Product Name Screen Shot][product-screenshot]](https://example.com)

El proyecto consiste en cutro desafios realizados para el curso de procesamiento de lenguaje natural en el contexto de la carrera de especializacion en inteligencia artificial de la Universidad de Buenos Aires.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Challenges

<strong>Vectorizador + Naive bayes:</strong>

<em><p>
El primer desfío consta de explorar la vectorización de documentos, con un enfoque clásico (utilizando temas TF-IDF), para empezar a visualizar la similitud entre documentos de forma matemática, utilizando usualmente la similitud de coseno. También es una primera aproximación a un simple modelo del lenguaje como lo es <ins>Naive Bayes</ins>, donde se analiza sus puntos fuertes así también como sus puntos débiles en comparación con <ins>Complement NB</ins> para la clasificación de documentos.
</p></em>

- ✅ [link al notebook][desafio1-notebook-url]

<strong>Embeddings con Gensim:</strong>

<em><p>
El segundo desfío toma un enfoque más complejo e introduce el térmio de <ins>embeddings</ins>, el cual es una mejora a la primera vectorización. En este sentido, se analizan nuevamente medidas de distancias en las distintas dimensiones de estos embeddings creados con la librería de Gensim. Se exploran analogías y visualizaciones en espacios de dimensiones reducidos, mediante técnicas como PCA o T-SNE, utilizando el lore del Señor de los Anillos.
</p></em>

- ✅ [link al notebook][desafio2-notebook-url]

<strong>Modelo del lenguaje:</strong>

<em><p>
El tercer desafío introduce formalmente las primeras lineas de investigación en modelos del lenguaje utilizando "deep learning". Se nombran térmios como tokenización y corpus, explorando en profundidad el proceso de tokenización, el cual es importante para entender como funcionan los grandes modelos del lenguaje, que si bien utilizan una tokenización disitinta actualmente, el enfoque no ha cambiado. En este desafío, también se analizan estructuras que en su tiempo fueron estado del arte, como las celdas de Elman (unidades recurrentes), o capas LSTM/GRU.
</p></em>

- ✅ [link al notebook][desafio3-notebook-url]

<strong>BOT QA:</strong>

<em><p>
En este cuarto desafío, se intenta resolver un problema específico: crear un bot QA basando en "deep learning", utilizando capas LSTM y embeddings. En este sentido, se analizan los clasicos problemas que tienen estas arquitecturas de aprendizaje profundo, donde el "overfitting" o el "vanishing gradients" son temas que siempre están presentes. También se obtienen conclusiones interesantes desde el punto de vista de utilzar fine-tuning o la potencia de los embeddings pre-entrenados.
</p></em>

- ✅ [link al notebook][desafio4-notebook-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[desafio1-notebook-url]: TPs/TP1/challenge_1.ipynb
[desafio2-notebook-url]: TPs/TP2/src/challenge_2.ipynb
[desafio3-notebook-url]: TPs/TP3/src/challenge_3.ipynb
[desafio4-notebook-url]: TPs/TP4/src/challenge_4.ipynb
