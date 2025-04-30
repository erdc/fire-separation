# Fuelbreaks Graph Separation Project

This project aims to find where decision makers should place fire fuelbreaks. A basic strategy utilizing equal graph partitioning and quantum computing is used to determine the placements with speed and efficacy

## Requirements and Installation

This project uses conda environments to manage dependencies. The environment can be created using the following command:

``` conda env create --name fire_separation --file=environment_fire_separation.yml ```

You may need to remove the output on certain notebooks to make them small enough to commit to do this, use the following command:

``` jupyter nbconvert --clear-output --inplace <<notbook name>> ```


## Project Point of Contact

If you have any questions about either running this project or the project in general, feel free to contact Sam Dent at:
```Samuel.C.Dent@erdc.dren.mil```

## Project Structure
###

```
├── README.md          <- The top-level README for developers using this project (this file).
│
├── data*              <- Currently, all data is saved, intermediate data therefore, no subdirectories have been added
│   ├── intermediate   <- Intermediate saved data to be passed between notebooks.
│   └── results        <- Data used in the final results of the project.
│
├── notebooks          <- Jupyter notebooks
│
├── figures*           <- Generated analysis as HTML, PDF, LaTeX, etc.

```

`* Asterisk` indicates a directory's contents is gitignored.
