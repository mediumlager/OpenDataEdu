## OpenDataEdu

To use C++ with Jupyter Notebook (with MyBinder):
  - create file readthedocs.yml, which contains:
              conda:
              file: docs/environment.yml
  - create file environment.yml:
              name: xeus-cling
              channels:
                - QuantStack
                - conda-forge
              dependencies:
                - xeus-cling=0.4.5
                - notebook
