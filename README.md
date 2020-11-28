Replication material: *"Food imports, international prices, and violence in Africa"*    
Submitted: 2015.02.01  
Accepted: 2016.01.13  
URL: https://academic.oup.com/oep/article/68/3/758/1752956    

Data and code to replicate results as reported in the paper. 
Data processing and analysis were carried out in R.
For issues replicating the results contact me via email: vanweezel (at) pm.me.

#### Description
`code`
* `clean.R`: prepares the data for the regression analysis;
* `functions.R`: contains all the functions used for the analysis;
* `estimation.R`: replication of main estimation as presented in the paper;
* `cross_validation.R`: cross-validation exercise as presented in the paper;
* `robustness.R`: robustness checks as presented in the suporting material. 

`tidy_data`
* `allData.Rdata`:dataset used for the main estimation and the various robustness checks;
* `ous.Rdata`:dataset for the cross-validation

#### BibTeX
```
@article{vanweezel2016,
  title={Food imports, international prices, and violence in Africa},
  author={Van Weezel, Stijn},
  journal={Oxford Economic Papers},
  volume={68},
  number={3},
  pages={758--781},
  year={2016},
  publisher={Oxford University Press}
}
```