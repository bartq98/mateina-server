<div align="center"><h2>mateina 🌿</h2></div>
<div align="center"><h3>server of <b>Mateina</b> - Zettelkasten inspired note taking app</h3></div>

Nowadays, our work requires the use of more and more information.
Effective management of such information is a very important thing.
The answer to these needs is **Mateina**.

Mateina is a web application which focuses of connecting information (represented by cards) whit each other.
It is inspired by [Wiki](https://en.wikipedia.org/wiki/Wiki) and [Zettelkasten](https://en.wikipedia.org/wiki/Zettelkasten).
You are able to create rich-text supported content and connect portions of information with links in an intuitive way.

## Setup

Mateina is written in Python 3 🐍 and FastAPI 🗲. Instructions below are intended for Linux. Commands for Windows or OSX may differ slightly.

<span>1. </span> clone this repository:

```
git clone https://github.com/bartq98/mateina-server
```
<span>2. </span> make Python virtual environment and activate it
```
python -m venv ./venv && source ./venv/bin/activate
```
<span>3. </span> install necessary dependencies:
```
pip install -r venv requirements.txt
```

Now you are able to run server-side Mateina:
```
uvicorn index:app --reload # for development
or
uvicorn index:app # for production
```
Detailed instruction of running FastAPI applications can be found [there](https://fastapi.tiangolo.com/tutorial/first-steps/).

## Configuration

*the settings file and frequently checked options* - *to be done*

