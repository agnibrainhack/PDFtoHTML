# Objective

Convert PDF to HTML for downstream text analysis.

## Installation

```bash
First 
apt install ./pdf2htmlEX.deb(attached in the repo nbk) or 

Build from source here: 
https://github.com/pdf2htmlEX/pdf2htmlEX/wiki/Download-Debian-Archive
[Available in debian, macos]

Then:
clone the repo https://github.com/airtonix/unilex-transcript
```

## Usage
Create a .env file and push the base location 
```bash
!touch .env
!echo DATA_DIR = /content/ > .env
```
Create a folder named "PDF" and put your file 
```
!mkdir /content/PDF  
```

## Output

2 separate folders by the name HTML and HTM will be generated at the base location. Visualize the HTM or the HTML file  output for processing downstream NLP jobs.
