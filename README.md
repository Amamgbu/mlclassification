# Image Classification of Hotels and Non-Hotels

This project is carried out for the purpose of building a machine learning model for classifying images of Hotes from Non-hotels

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Project Structure

```
.
├── datasets
│   ├── test_set
│   │   ├── hotels
│   │   └── not-hotels
│   │            
│   │             
│   └── training_set
├       ├── hotels
├       └── not-hotels
├── model
│   └── default_model.h5
│   
│   
├── env
├── utils
├── requirements.txt
├── app.py
└── README.md
```

### Prerequisites

Python distribution

```
Anaconda
```

### Installing

Install Anaconda python distribution on your system

If there is an app folder skip this step

```
python -m venv app
```

Activate the virtual environment (VENV)

```
LINUX/Mac: source app/bin/activate

Windows: app\Scripts\activate.bat
```

Install dependencies in VENV using requirements file

```
pip3 install -r  env/requirements.txt
``` 

## Deployment

Start app (Make sure to enter a valid path to a file or a folder)


Example of valid commands

```
python app.py predict --path kimono-1986491_640.jpg
python app.py predict --path predict
```

### Train App

Make sure you have a dataset folder with the below structure in the root folder of the app

A trained model weight file can be found [here](https://drive.google.com/drive/folders/1rYweIKMNjQiKC-D92BPEcK7CSPd_jDPb?usp=sharing), download and put it in the models folder.

Download and extract this [file](https://drive.google.com/file/d/15ExWHHPnzdqzQDM7ROxBdwohbxa5b_Lx/view?usp=sharing) to the root folder of the project or you can train your own model by providing a dataset folder in the root folder of the project with  below structure.

```
.
├── datasets
│   ├── test_set
│   │   ├── valid_case
│   │   └── not_valid_case
│   │            
│   │             
│   └── training_set
├       ├── valid_case
├       └── not_valid_case
```

```
python3 train_model.py

```


## Built With

* [Anaconda](https://www.anaconda.com/distribution/) - The python distribution used
* [VS Code](https://code.visualstudio.com/) - The IDE used

## Documentation

Read documentation [here](https://docs.google.com/document/d/1rmpzDJTY0VO4IIhxTE0HqCEoa4yUMz3GCE-KlVNshTY/edit?usp=sharing)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
