For the experimental results, the code is organized according to the section structure of the latest version of the manuscript. 
For example, running the code in `exp_5_2_1` reproduces the results reported in Section 5.2.1.

The `main_XXX.py` files are directly executable and include the required parameter settings, dataset paths, and other configurations.

OALC_all_github/
├── data/                      
├── data_multi/                
├── exp_5_2_1/
│   ├── __init__.py
    ├── draw_Fig7.py           # code for Fig. 7
│   ├── main_Table4.py         # experiment for Table 4
│   ├── main_Table5_Table6.py  # experiments for Tables 5 and 6
│   ├── main_Table8.py         # experiment for Table 8
│   └── res_Table4.csv         # results for Table 4
├── exp_5_3/
├── exp_5_4/
├── exp_5_5_1/
├── exp_5_5_2/
├── exp_5_5_3/
├── exp_5_6_1/
├── exp_5_6_2/
├── __init__.py
├── BaseQuery.py               # base class of query strategies
├── data_load.py               # dataset loading
├── OALC_.py
├── OALC_learner.py            # online learner
├── Query.py                   # query strategies
├── run_OALC.py                # main entry to run OALC
└── utils.py                   # utility functions
