<a name="readme-top"></a>



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/BabyfaceDeveloper/Dog-Breed-Identification">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Dog Breed Classification</h3>

  <p align="center">
    Identifying the breed of a dog given an image of a dog.
    <br />
    <a href="https://github.com/BabyfaceDeveloper/Dog-Breed-Identification/blob/main/solution.ipynb"><strong>Explore the notebook »</strong></a>
    <br />
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

> When I'm sitting at the cafe and I take a photo of a dog, I want to know what breed of dog it is.

**Note**: [Kaggle's dog breed identification competition](https://www.kaggle.com/competitions/dog-breed-identification/overview)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Python][Python]][Python-url]
* ![Microsoft Excel]
* [![Pandas][Pandas]][Pandas-url]
* [![Numpy][Numpy]][Numpy-url]
* [![Matplotlib][Matplotlib]][Matplotlib-url]
* [![Scikit-learn][Scikit-learn]][Scikit-learn-url]
* [![Tensorflow][Tensorflow]][Tensorflow-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

Download [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) or use [Google Colab](https://colab.research.google.com/)

### Installation

1. Clone the repo
   ```bash
   git clone https://github.com/BabyfaceDeveloper/Dog-Breed-Identification.git
   ```
2. Open `Search` on Windows or Linux and type `Anaconda` and select the prompt
3. Create virtual environment and install tools
   1. From scratch
      ```bash
      conda create --prefix ./venv pandas numpy matplotlib scikit-learn
      ```
   2. From `environment.yml`
      ```bash
      conda create --prefix ./venv -f enviroment.yml
      ```
4. Activate virtual environment
   ```bash
   conda activate ./venv
   ```
5. Install library
   * Jupyter notebook 
      ```bash
      conda install jupyter
      ```
   * Visual Studio Code 
      ```powershell
      conda install ipykernel
      ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

- For Visual Studio Code user:
   ```powershell
   code 'Dog-Breed-Identification'
   ```
- For jupyter notebook user (conda prompt):
   ```sh
   jupyter notebook
   ```

_For more information about `Jupyter in Visual Studio Code` , please refer to the [Documentation](https://code.visualstudio.com/docs/datascience/jupyter-notebooks)_

_For more information about `Jupyter`, please refer to the [Documentation](https://jupyter.org/install)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- HELP -->
<!-- ## Help

Any advise for common problems or issues.
```
command to run if program contains helper info
```

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- CONTRIBUTING -->
<!-- ## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p> -->



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Nguyen - [@Nguyen Linkedin](https://www.linkedin.com/in/binhnguyennguyen/)

Project Link: [https://github.com/BabyfaceDeveloper/Dog-Breed-Identification](https://github.com/BabyfaceDeveloper/Dog-Breed-Identification)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)
* [Kaggle](https://www.kaggle.com/)
* [Zero To Mastery](https://zerotomastery.io/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

<!-- How to make badages Reference -->
<!-- https://github.com/Ileriayo/markdown-badges -->
<!-- https://javascript.plainenglish.io/how-to-make-custom-language-badges-for-your-profile-using-shields-io-d2aeaf016b6b -->

[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/linkedin_username

[product-screenshot]: images/screenshot.png

[Python]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/downloads/

[Pandas]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[Pandas-url]: https://pandas.pydata.org/

[Matplotlib]: https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black
[Matplotlib-url]: https://matplotlib.org/

[scikit-learn]: https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white
[scikit-learn-url]: https://scikit-learn.org/stable/

[NumPy]: https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white
[NumPy-url]: https://numpy.org/

[TensorFlow]: https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white
[TensorFlow-url]: https://www.tensorflow.org/

[Microsoft Excel]: https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white
