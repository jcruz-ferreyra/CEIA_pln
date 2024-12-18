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

<strong>Embeddings con Gensim:</strong>

<em><p>
El segundo desfío toma un enfoque más complejo e introduce el térmio de <ins>embeddings</ins>, el cual es una mejora a la primera vectorización. En este sentido, se analizan nuevamente medidas de distancias en las distintas dimensiones de estos embeddings creados con la librería de Gensim. Se exploran analogías y visualizaciones en espacios de dimensiones reducidos, mediante técnicas como PCA o T-SNE, utilizando el lore del Señor de los Anillos.
</p></em>


<strong>Modelo del lenguaje:</strong>

<em><p>
El tercer desafío introduce formalmente las primeras lineas de investigación en modelos del lenguaje utilizando "deep learning". Se nombran térmios como tokenización y corpus, explorando en profundidad el proceso de tokenización, el cual es importante para entender como funcionan los grandes modelos del lenguaje, que si bien utilizan una tokenización disitinta actualmente, el enfoque no ha cambiado. En este desafío, también se analizan estructuras que en su tiempo fueron estado del arte, como las celdas de Elman (unidades recurrentes), o capas LSTM/GRU.
</p></em>

<strong>BOT QA:</strong>

<em><p>
En este cuarto desafío, se intenta resolver un problema específico: crear un bot QA basando en "deep learning", utilizando capas LSTM y embeddings. En este sentido, se analizan los clasicos problemas que tienen estas arquitecturas de aprendizaje profundo, donde el "overfitting" o el "vanishing gradients" son temas que siempre están presentes. También se obtienen conclusiones interesantes desde el punto de vista de utilzar fine-tuning o la potencia de los embeddings pre-entrenados.
</p></em>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[contributors-shield]: https://img.shields.io/github/contributors/brunomaso1/uba-ceia.svg?style=for-the-badge
[contributors-url]: https://github.com/brunomaso1/uba-ceia/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/brunomaso1/uba-ceia.svg?style=for-the-badge
[forks-url]: https://github.com/brunomaso1/uba-ceia/network/members
[stars-shield]: https://img.shields.io/github/stars/brunomaso1/uba-ceia.svg?style=for-the-badge
[stars-url]: https://github.com/brunomaso1/uba-ceia/stargazers
[issues-shield]: https://img.shields.io/github/issues/brunomaso1/uba-ceia.svg?style=for-the-badge
[issues-url]: https://github.com/brunomaso1/uba-ceia/issues
[license-shield]: https://img.shields.io/github/license/brunomaso1/uba-ceia.svg?style=for-the-badge
[license-url]: LICENCE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/brunomaso1
[product-screenshot]: ceia-nlp/resources/readme-portada.png
[download-python-url]: https://www.python.org/downloads/

[pytorch]: https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white
[pytorch-url]: https://pytorch.org/
[tensorflow]: https://img.shields.io/badge/tensorflow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white
[tensorflow-url]: https://www.tensorflow.org
[jupyter]: https://img.shields.io/badge/jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[jupyter-url]: https://jupyter.org/
[scikitlearn]: https://img.shields.io/badge/scikitlearn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white
[pandas]: https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[keras]: https://img.shields.io/badge/keras-D00000?style=for-the-badge&logo=keras&logoColor=white
[scipy]: https://img.shields.io/badge/scipy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white
[scikitlearn-url]: https://scikit-learn.org/
[pandas-url]: https://pandas.pydata.org/
[keras-url]: https://keras.io/
[scipy-url]: https://scipy.org/
[transformers]: https://img.shields.io/badge/huggingface-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black
[transformers-url]: https://huggingface.co/docs/transformers/index
[nltk]: https://img.shields.io/badge/nltk-0d97ca?style=for-the-badge
[gensim]: https://img.shields.io/badge/gensim-1938c0?style=for-the-badge
[seaborn]: https://img.shields.io/badge/seaborn-008ef4?style=for-the-badge
[nltk-url]: https://www.nltk.org/
[gensim-url]: https://radimrehurek.com/gensim/
[seaborn-url]: https://seaborn.pydata.org/
[desafio1-notebook-url]: ceia-nlp/Desafio%201.ipynb
[desafio2-notebook-url]: ceia-nlp/Desafio%202.ipynb
[desafio3-notebook-url]: ceia-nlp/Desafio%203.ipynb
[desafio4-notebook-url]: ceia-nlp/Desafio%204.ipynb
[desafio5-notebook-url]: ceia-nlp/Desafio%205.ipynb
