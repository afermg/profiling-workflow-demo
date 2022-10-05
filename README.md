This repository was created from the `cytomining/profiling-template` template repository. The `README.md` of that repository and that of `cytomining/profiling-recipe` contain instructions 
- for creating a data repository
- for welding `profiling-recipe` to the data repository
- for creating the folder structure and populating them with the necessary files
- for modifying the `config.yml` file
- for running the profiling recipe

To reproduce the profiles in this repo, clone the repo 

```bash
git clone git@github.com:niranjchandrasekaran/profiling-workflow-demo.git
```

and then run the following command

```bash
python profiling-recipe/profiles/profiling_pipeline.py --config config_files/config.yml
```