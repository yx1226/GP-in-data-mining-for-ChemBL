# Genetic Programming (GP) in data mining for ChemBL

As part of my dissertation, I've referred the papers 
*[Calculation of Substructural Analysis Weights Using a Genetic Algorithm (2015)](http://eprints.whiterose.ac.uk/116212/)* and 
*[Ligand-based virtual screening using a genetic algorithm with data fusion (2018)](https://match.pmf.kg.ac.rs/electronic_versions/Match80/n3/match80n3_623-638.pdf)*
and this repository is my implementation. In this approach, I use 3 types of GP method, which are 
Symbolic Regressor, Cartesian GP and Linear GP, to find out the best result in GP and then compared 
with the result of Genetic Algorithm (GA) in the papers. 

By understanding what is GP and how it works,
I did discovery on GP by studying [gplearn Documentation](https://gplearn.readthedocs.io/en/stable/intro.html),
and [A Field Guide to Genetic Programming](http://www0.cs.ucl.ac.uk/staff/W.Langdon/ftp/papers/poli08_fieldguide.pdf).
When I started to hand on, I refer to [DEAP](https://deap.readthedocs.io/en/master/tutorials/advanced/gp.html#). Then,
The [modules](https://gplearn.readthedocs.io/en/stable/_modules/index.html) are refered from gplearn documentation.

## Objective
<li>Random generate an universal equation for all of various ChemBL drug with top 1% dataset.</li>
<li>Compare the GP result with GA result</li>

## Citation: 
<ol>
  <li>
    Holliday, J., Nor Sani, and Peter Willett.
    "Ligand-based virtual screening using a genetic algorithm with data fusion". 
    Match: Communications in Mathematical and in Computer Chemistry 80.3 (2018).
  </li>
  <li>
    Holliday, John D., Nor Sani, and Peter Willett. 
    "Calculation of substructural analysis weights using a genetic algorithm." 
    Journal of chemical information and modeling 55.2 (2015): 214-221.
  </li>
  <li>
    Kun-Hong Liu, Muchenxuan Tong, Shu-Tong Xie, Vincent To Yee Ng, 
    "Genetic Programming Based Ensemble System for Microarray Data Classification", 
    Computational and Mathematical Methods in Medicine, vol. 2015, Article ID 193406, 11 pages, 2015. 
  </li>
</ol>
