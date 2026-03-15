# Pygame for Kids

A collection of python based games for learning python and pygame. These are not tutorials I created and do not claim copyright. I'm only update tutorials that exist by adding readme's and config files around running the python code in a more modern way with VsCode and uv and modern python install tools.

## Install Arch:

Required on Arch: `yay sdl2_image pygame`

Test: `uv run python -c 'import pygame; print(pygame.get_sdl_version())'`

## Install Windows

- Install vscode and Git for Windows
- Use the Git Bash Terminal and ensure `python --version` is >= 3.13
- Test installing pygame and uv globally first `python -m pip install --user pygame uv`
- When running the commands for each game project ensure you're in the directory, ex: `cd rain_dodge` before running `python -m uv run main.py`