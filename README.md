
## install
* cd into project directory
```
poetry install
poetry shell
echo QUARTO_PYTHON=$(poetry env info --path) > .env
```
* project directory should now contain a `.env` file that will tell quarto to use the python installation that is managed by poetry, with dependencies defined in `pyproject.toml`.
* open RStudio & knit qmd documents as desired
