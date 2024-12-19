# Model Diagram Generator

This project provides an easy way to generate a database diagram for the Guide Model using ERAlchemy.

## Features
- **Generate database diagrams**: Quickly visualize the relationships between tables in a database.
- **Simple setup**: Minimal dependencies with step-by-step setup instructions.
- **Customizable**: Easily edit the ER file to suit your database needs.

---

## Example Command to Generate the Diagram

```bash
eralchemy -i 'guides.er' -o guides.png

```
## Installation
python3 -m venv myenv
source myenv/bin/activate

pip install pygraphviz eralchemy

![Alt Text](https://github.com/Timjini/diagram-generator/blob/main/guides.png?raw=true)


---