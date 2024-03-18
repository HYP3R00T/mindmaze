# Mindmaze

It is my `second brain` that leverages the power of Obsidian and Material for MkDocs. 

## Why?

After spending hours surfing the internet, I stumbled upon tons of interesting stuff that I wanted to keep track of. But I couldn't remember it all, no matter how hard I tried to organize my bookmarks. So, I decided to use Obsidian to link my notes together and make sense of it all. And to share my findings with others easily, I turned it into a website using mkdocs. So here it is, my online treasure trove for everyone to explore! 

## Usage

### Open in Obsidian

* To open this project in Obsidian, first clone it to your local machine.
    ```sh
    git clone https://github.com/HYP3R00T/mindmaze
    ```
* Open Obsidian and click on the `Open` button next to `Open folder as vault`.
* Navigate to the cloned copy of this repo and open the `mindmaze` folder (the inner one).

### Open in mkdocs

* Prerequisites:
   * `python` with `pip`
   * Visual Studio Code - Optional
* First clone it to your local machine.
    ```sh
    git clone https://github.com/HYP3R00T/mindmaze
    ```
* Open the local copy of the repo in `vscode`.
* Open a terminal within `vscode` create a python virtual environment.
    ```sh
    python -m venv .venv
    ```
* Activate the virtual environment
    ```sh
    # Windows
    .\.venv\Scripts\Activate.ps1
    # Linux
    source ./.venv/bin/activate
    ```
* Install python packages
    ```sh
    pip install -r requirements.txt
    ```
* To see the live preview, just run `mkdocs serve`.

## References

### [Obsidian.md](https://obsidian.md/)

**Plugins**
* [Excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin)
* [Style Settings](https://github.com/mgmeyers/obsidian-style-settings)
* [admonitions](https://github.com/javalent/admonitions)
* [file-hider](https://github.com/Oliver-Akins/file-hider) - To hide custom stylesheets folder in Obsidian
* [sort-and-permute-lines](https://github.com/Vinzent03/obsidian-sort-and-permute-lines)

**Theme**
* [Catppuccin for Obsidian](https://github.com/catppuccin/obsidian)

### [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/)

**Plugins**
* [mkdocs-callouts](https://pypi.org/project/mkdocs-callouts/)
* [mkdocs-roamlinks-plugin](https://pypi.org/project/mkdocs-roamlinks-plugin/)