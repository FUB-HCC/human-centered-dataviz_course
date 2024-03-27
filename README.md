# Data Visualization 2023

## Prerequisites

In order to take part in the course, please ensure that you have a Python version greater or equal to 3.11.4 , a working installation of [Poetry](https://python-poetry.org/docs/) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed.

## Setup

1. Clone this repository and move it into the repo root

```
git clone git clone https://github.com/FUB-HCC/human-centered-dataviz_course.git
cd human-centered-dataviz_course
```

2. Install the dependencies in the repo root

```
poetry install
```

3. Start the Jupyter Lab server

```
poetry run jupyter lab
```

4. If the Juypterlab interface does not appear in an opened web browser, follow the instructions that are printed in the terminal.

5. Once you are able to open the interface, open the introductory notebook `Hello.ipynb` by selecting it in the left column and double-clicking.

6. Run the whole notebook by executing `Kernel -> Restart Kernel and run all cells`.

7. If you arrived at this point and have no major warnings or errors popping up, you are ready for our course :)

For further information concerning Poetry, you may consult [this guide](https://python-poetry.org/docs/cli/).

If you have problems installing Poetry and can't make it run, it is also possible (although bad style) to install the necessary packages globally by executing

```
pip3 install --user altair pandas numpy jupyterlab
```
