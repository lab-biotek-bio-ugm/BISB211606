# BISB211606 - Sequence Alignment Fundamentals, Algorithm, and Application

This repository is the companion activity for the [BISB211606 - Bioinformatics Practical Handbook](https://bisb211606.matinnu.org/) taught in the Academic Year 2025/2026 at the Undergraduate Biology Study Program, Faculty of Biology, Universitas Gadjah Mada.

## Running the activity using GitHub Codespace
Click on the button below to start a codespace using this repository as the template:

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/lab-biotek-bio-ugm/BISB211606)

You can create a new codespace or reuse existing ones.

Once your codespace is ready, follow these steps:

1. If this is a fresh codespace, initiate conda by typing `conda init` in the terminal. It will then give you a message like this:

    ```
    ==> For changes to take effect, close and re-open your current shell. <==
    ```

2. Open a new shell by clicking on the `+` button on the top right corner of the terminal. If conda is successfully set up then your terminal command line will start with `(base)`. This means you are at the `base` environment.

3. Install the necessary dependencies by creating a new environment from the recipe file:

    ```bash
    conda env create -f environment.yml
    ```

4. Once the installation is complete, activate the environment with:

    ```bash
    conda activate BISB211606
    ```

5. Then you can start a jupyter session with:

    ```bash
    jupyter lab
    ```

    Then follow the instruction on the terminal, which looks something like this:

    ```
    To access the server, open this file in a browser:
        file:/home/codespace/.local/share/jupyter/runtime/jpserver-10660-open.html
    Or copy and paste one of these URLs:
        http://localhost:8888/lab?token=a1465447bdfea61395e2610c41c90a20ac0d85b3eca05cfb
        http://127.0.0.1:8888/lab?token=a1465447bdfea61395e2610c41c90a20ac0d85b3eca05cfb
    ```

6. If it ask for the password or token, input the key shown at the terminal. On the example above, the token is = `a1465447bdfea61395e2610c41c90a20ac0d85b3eca05cfb`

7. PS: You can alos run the notebooks directly from the VS Code interface, but you need to install the right plugin and fight the right kernel
