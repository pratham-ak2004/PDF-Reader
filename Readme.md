
# PDF text to audio and Read

This python projects is made to extract text from a pdf file , convert it into audio file and read the same to the user. it includes functionalities like play/pause , read speed , voice - male/female and file (book) selection.

## Features

- Play/Pause
- Voice selection
- file selection
- speech speed modification


## Prerequisite

To run this project, you will need a `python evnironment` with `jupyter` installed . A bunch of other dependencies are also required for the project.



## Installation

The required environment can be set using terminal itself. 

Check python installed in you setup.
Note: this step can be skipped.

```bash
where python
```

Create a local environment

```bash
  python -m venv env_name_
```
You can also create specific environment by mentioning the python path.

```bash
python_path -m venv env_name_
```

Install the necessary libraries using pip.

```bash
pip install PyPDF2
pip install pyttsx3
pip install pygame      ## for playing the audio
pip install notebook    ## if jupyter notebook is not installed
pip install ipykernel   ## for installing python kernel
```

Setup your environment. If you are using VS code, the editor itself sets up your kernel. you can just select the python environment created as your kernel for the notebook.

```bash
python -m ipykernel install --user --name=env_name_
.\env_name\scripts\activate   ##activate your environment
```


## Working

The projects can be run after setting up the evironments by the help of the notebook.



## Drawbacks

The project has some drawbacks.

- can not skip particular pages
- audio length can be for hours depending on the number of pages.
- the speech is not natural
- limited to few languages only
- only `.wav` format worked for the project



## Support

- Email : pratham20442@gamil.com 
- github : https://github.com/pratham-ak2004
- linkedin : https://www.linkedin.com/in/pratham-a-kadekar-8397a7249/
