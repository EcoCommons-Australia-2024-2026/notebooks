## Don't change EcoCommons Notebooks list in README.md manually!

1. Add new notebook file `.ipynb` to `notebooks` directory.
2. Add new entry to `automation/notebooks-table-data.csv` file.
3. Run `automation/autogenerate_notebooks_table.py` script. EcoCommons Notebooks table in `README.md` will update 
automatically. 

```bash
python3 automation/autogenerate_notebooks_table.py
```

4. Commit changes to feature branch. Create PR.
