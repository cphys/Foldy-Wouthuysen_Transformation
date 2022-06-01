# Foldy-Wouthuysen Transformation Strong Magnetic Fields
This project applies the non-commutative algebra package [NCAlgebra](www.github.com/NCAlgebra/NC) to calculate the Foldy-Wouthuysen (FW) Transformation Strong Magnetic Fields.

Method uses itterative form of FW Transformation [1] to recreate known values of the H<sub>FW</sub> up to order α<sup>6</sup> [2-3]

## Included files
* fwTransformation.nb -- a mathematica notebook which uses [NCAlgebra](www.github.com/NCAlgebra/NC) package to carry out Foldy-Wouthuysen Transformation Strong Magnetic Fields.

## Dependencies
This notebook relies on [NCAlgebra](www.github.com/NCAlgebra/NC) package 

## α<sup>6</sup> Output
Below we show the sample output for H<sup>(i)</sup> for i={2,3,4,5,6}. Values are equivalent to those found in the literature [2,3].
![](/images/sixthOrder.png)

## Future Improvements
Expand to higher orders in FW-Transformation. Compare to Hamiltonians derived elsewhere [4-5]

Values for H are not unique. and different value for S will result in different Hamiltonians which are equivalent up to a transformation [2]. Functionality exploring different S's could be added.

## External References
[1] [Itzykson, Claude, and Jean-Bernard Zuber.](https://books.google.com/books?hl=en&lr=&id=CxYCMNrUnTEC&oi=fnd&pg=PP1&dq=C.+Itzykson+and+J.+B.+Zuber,+Quantum+Field+Theory&ots=am1wZ5kf9F&sig=oEFME-hWa_5-GvPntgNimvnIFDM#v=onepage&q&f=false)
    Quantum field theory. Courier Corporation, 2012.

[2] [Zatorski, Jacek, and Krzysztof Pachucki.](https://www.fuw.edu.pl/~krp/papers/zatorski.ps.gz)
    "Electrodynamics of finite-size particles with arbitrary spin." 
    Physical Review A 82, no. 5 (2010): 052520.

[3] [Pachucki, Krzysztof.](https://arxiv.org/pdf/physics/0411168)
    "Higher-order effective Hamiltonian for light atomic systems." 
    Physical Review A 71, no. 1 (2005): 012503.
    
[4] [Mei, Xue-Song, Wan-Ping Zhou, and Hao-Xue Qiao.](https://arxiv.org/pdf/2003.10068.pdf)
    "Nonrelativistic quantum electrodynamic approach to polarizabilities of light atoms." 
    Journal of Physics B: Atomic, Molecular and Optical Physics 52, no. 22 (2019): 225005.
    
[5] [Mei, Xue-Song, Shu-Min Zhao, and Hao-Xue Qiao.](http://cpl.iphy.ac.cn/EN/article/downloadArticleFile.do?attachType=PDF&id=60018)
    "Calculation of Higher-Order Foldy-Wouthuysen Transformation Hamiltonian." 
    Chinese Physics Letters 31, no. 6 (2014): 063102.


