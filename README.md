# geochemical-levelling

In order to overcome the analytical variation that is inherent between geochemical surveys, and even between batches if different machines are used, presents a significant issue when combining multiple surveys together. To that and end this code was developed to level surface geochemistry data using a variety of methods as outlined in Main et al, in prep. The code has two main functions, the production of correction factors based upon population statistics of a single standard, or though linear regression using reanalysis. Future iterations of the code will allow for the use of multiple standards; however, until that point the median values for each standard can be used as the input for the linear regression to produce a correction factor. Once the correction factors are generated, the code can then be use to level the data. The files that are output from the first step should be used for this levelling. 