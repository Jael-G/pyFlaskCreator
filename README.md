<p align="center">
![Output Image](https://github.com/Jael-G/pyFlaskCreator/blob/main/media/banner.png)
</p>


<h1 align="center">pyFlaskCreator </h1>
<h5 align="center">Generate simple Flask project template</h5>

# Installation

```
pip install pyflaskcreator
```

# Usage

```
pyflaskcreator [-h] -p PATH [-e ENV]

options:
  -h, --help            show this help message and exit
  -p PATH, --path PATH  Path of the app
  -e ENV, --env ENV     Python enviroment name
```
# Example
&nbsp;
**Running :** 
```
pyflaskcreator -p myApp
```

**Output**

![Output Image](https://github.com/Jael-G/pyFlaskCreator/blob/main/media/output.png)


**Project Structure**

```
/myApp
├── static/
│   ├── flask_icon.png
│   └── welcome.css
├── templates/
│   └── welcome.html
├── venv/
└── app.py
```

**Executing App**
```
cd myApp
python app.py
```

**Landing Page**

![Output Image](https://github.com/Jael-G/pyFlaskCreator/blob/main/media/landing_page.png)
