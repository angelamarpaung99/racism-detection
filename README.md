<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Dataset](#dataset)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Contributing](#contributing)
* [Contact](#contact)


<!-- ABOUT THE PROJECT -->
## About The Project

This is Racism Detection System that was built to detect racism on Indonesian tweets text. 
This project uses Long Short-Term Memory Network (LSTM) using Python programming language. 

### Dataset
Dataset is collected from Twitter.
Dataset contains three columns of data: number, tweets, label. 
Data collected is 686 tweets, in which each of the tweets is labelled manually. 
Labelled tweets resulted in 511 tweets for class Non_R (Non Racism)  and 175 tweets for class R (Racism). 
Since this dataset is imbalanced, you can do under-sampling to create balanced dataset.

### Built With
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.
* Python

<!-- GETTING STARTED -->
## Getting Started

You can get dataset from file "dataset_racism.csv".
You can run either the python notebook file "Racism Detection.ipynb" or "Racism Detection.py"


### Prerequisites

You can run the python notebook file "Racism Detection.ipynb" locally on Jupyter Notebook or Google Colaboratory.
You can run the python script file "Racism Detection.py"

### Installation

1. Clone the repo
```sh
git clone https://github.com/angelamarpaung99/racism-detection.git
```
2. Enter your own location path of dataset in
`Racism Detection.py` or `Racism Detection.ipynb` in this line of code
``` 
df = pd.read_csv(<FILE PATH LOCATION>, sep=',') 
```

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b <add-your-new-branch-name>`)
3. Commit your Changes (`git commit -m 'commit message'`)
4. Push to the Branch (`git push origin <add-your-branch-name>`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact

Angela Marpaung - angelamarpaung99@gmail.com

Project Link: [https://github.com/angelamarpaung99/course-on-demand.git](https://github.com/angelamarpaung99/course-on-demand.git)



