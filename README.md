<div class="row">
  <div class="column"><img src="misc/fins.gif" width="100" height="100" border="1px" align="left"></div>
  <div class="column"><h1> Feature-Imitating-Networks (FINS) </h1></div>
</div>

[Sari Saba-Sadiya](https://cse.msu.edu/~sadiyasa/)<sup>1</sup>,
[Tuka Alhanai](https://talhanai.xyz/)<sup>2</sup>,
[Mohammad Ghassemi](https://ghassemi.xyz/)<sup>1</sup><br>
<sup>1</sup> Michigan State University <sup>2</sup> New York University Abu Dhabi

FINs for going deep (learning). Code for the paper ["Feature Imitating Networks"](https://github.com/sari-saba-sadiya/Feature-Imitating-Networks/blob/main/FINS_ICASSP22_arXiv.pdf) initially presented in the IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2022.

<br>

## Overview:
A FIN is a neural network with weights initialized to reliably approximate one or more closed-form statistical features (such as Shannon’s entropy, kurtosis, MFCC...). This work demonstrates that FINs (and FIN ensembles) can provide best-in-class performance for a variety of downstream signal processing and inference tasks, while using less data and requiring less fine-tuning compared to other networks of similar (or even greater) representational power.

<br>

## Youtube Demo
The recorded presentation contains a theoretical part and a demo that starts at 6:25s.
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/TY_-wGrt3lM/0.jpg)](https://youtu.be/TY_-wGrt3lM?t=387)


<br>

## Cite
```
@INPROCEEDINGS{FIN_ICASSP22,
  author={Saba-Sadiya, Sari and Alhanai, Tuka and Ghassemi, Mohammad M},
  booktitle={ICASSP 2022 - 2022 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)}, 
  title={Feature Imitating Networks}, 
  year={2022},
  volume={},
  number={},
  pages={4128-4132},
  doi={10.1109/ICASSP43922.2022.9746397}
}

```
