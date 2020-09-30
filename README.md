# Data Visualization 2020

## Prerequisites

In order to take part in the course, please ensure that you have a Python version greater or equal to 3.6.1 , a working installation of [Poetry](https://python-poetry.org/docs/) and [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed.

The setup below is designed for \*nix systems, so on Windows you may be well advised to use the Linux subsystem for the setup. [Here](https://docs.microsoft.com/en-us/windows/wsl/install-win10) is a guide how to install the WSL.

## Setup

1. Clone this repository and move into the repo root

```
git clone https://github.com/wittenator/dataviz_course_2020.git
cd dataviz_course_2020
```

2. Install the dependencies in the repo root

```
poetry install
```

3. Start the Jupyter Lab server

```
poetry run jupyter lab
```

4. If the Juypterlab interface does not appear in a opened webbrowser, follow the instructions which are printed in the terminal.

5. Once you were able to open the interface, open the introductory notebook `Hello.ipynb` by selecting it in the left column and double clicking.

6. Run the whole notebook by executing `Kernel -> Restart Kernel and run all cells`.

7. If you arrived at this point and have no major warnings or errors popping up, you are ready for our course :)

For further information concerning Poetry, you may consult [this guide](https://python-poetry.org/docs/cli/).
