# The introduction to Gravel algorithm
Author: Tzu-Hsiang Lin, 林子翔 

The presented iterative  algorithm, GRAVEL, is proposed by M. Matzka in 1994.[1]
(Interestingly, there is no detailed description about the principle of this algorithm)
The equations[2] is described as

<img src='https://github.com/ShawnTHLIN/Neutron_unfolding/blob/main/unfolding_gif/Gravel_equation1.png' width='700'>

When the end equation below is equal to 1, the iterative process will be terminated.

<img src='https://github.com/ShawnTHLIN/Neutron_unfolding/blob/main/unfolding_gif/Gravel_equation2.png' width='400'>

where n is the degree of freedom.


# The iterative process of GRAVEL  algorithm for resolving Cf-252 spectrum
To examine the ability of this unfolding algorithm, initial guess is given a flat spectrum.

This is a demonstration. Actually, the iterative process would be terminated when the iterative number arrived 8 due to the end equation is almost equal to 1.

![unfolding_process](https://github.com/ShawnTHLIN/Neutron_unfolding/blob/main/unfolding_gif/GRAVEL_Cf-252.gif)

# The iterative process of GRAVEL algorithm for resolving AmBe spectrum

![unfolding_process](https://github.com/ShawnTHLIN/Neutron_unfolding/blob/main/unfolding_gif/GRAVEL_AmBe.gif)


# The iterative process of GRAVEL algorithm for resolving 30-MeV cyclotron-based fast neutron spectrum

![unfolding_process](https://github.com/ShawnTHLIN/Neutron_unfolding/blob/main/unfolding_gif/cyclotron-base%20neutron%20spectrum%20unfolding.gif | width=200)


[1]M. Matzke, “Unfolding of pulse height spectra: the hepro program system,” SCAN-9501291, Tech. Rep., 1994.

[2]H.Zhu, <I>et al.</I> "A Hierarchical Bayesian Approach to Neutron Spectrum Unfolding with Organic Scintillators
", IEEE Trans. Nucl. Sci. ,2019.
