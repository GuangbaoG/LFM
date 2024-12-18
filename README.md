# LFM
Package: LFM

Type: Package

Title: Laplace Factor Model Analysis and Evaluation

Date: 2024-11-18

Version: 0.1.0

Authors@R: c(person(given = "Guangbao",
                        family = "Guo",
                        role = c("aut", "cre"),
                        email = "ggb11111111@163.com"),
                 person(given = "Siqi",
                        family = "Liu",
                        role = "aut"))
                        
Description: Enables the generation of Laplace factor models across diverse Laplace distributions and facilitates the application 
of Sparse Online Principal Component (SOPC), Incremental Principal Component (IPC), Parallel Principal Component (PPC), Sparse Approximate Principal Component (SAPC), 
Standard Principal Component (SPC), and Farm Test methods to these models. Evaluates the efficacy of these methods within the context of Laplace factor models by 
scrutinizing parameter estimation accuracy, mean square error, and the degree of sparsity.

License: MIT + file LICENSE

Encoding: UTF-8

RoxygenNote: 7.3.2

Imports: stats, FarmTest, MASS, SOPC, LaplacesDemon, matrixcalc,
        relliptical
        
NeedsCompilation: no

Language: en-US

Author: Guangbao Guo [aut, cre],
  Siqi Liu [aut]
  
Maintainer: Guangbao Guo <ggb11111111@163.com>

Depends: R (>= 3.5.0)

BuildManual: yes

Suggests: testthat (>= 3.0.0)

Config/testthat/edition: 3

Packaged: 2024-11-18 10:54:04 UTC; R7000

Repository: CRAN

Date/Publication: 2024-11-19 12:30:09 UTC
