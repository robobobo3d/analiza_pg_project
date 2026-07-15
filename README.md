# data analysis project
resources:
- employee dataset

## generate report
```bash
# run all cells in `analysis.ipynb`
# then convert to pdf
python3 -m nbconvert --to pdf analysis.ipynb
# or convert to html
python3 -m nbconvert --to html analysis.ipynb
```