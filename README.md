# Basic Data Science Environment

For use with Pipenv and Jupyter.

It creates a local dir .venv with the installed libraries.

To install packages in Pipfile:

    ./install.sh

To install new Python packages:

    ./install.sh <name-of-package>

Run once, after installing Jupyter:

    ./install-jupyter-kernel.sh

Start Jupyter Notebook with:

    ./run-jupiter.sh

Then go to "Change Kernel -> .venv"
