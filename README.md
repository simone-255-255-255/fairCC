# On the feair use of the ColorChecker dataset for illuminant estimation

### Fair comparison procedure

### Fair CC performance (recovery angular error)
| Method                                           | Mean  | Med. | Tri-m. | B-25 | W-25 | 95-Q  | 99-Q  | Max   | Intra-patch | Inter-patches |
| :------------------------------------------------|------:|-----:|-------:|-----:|-----:|------:|------:|------:|------------:|--------------:|
| SoG [^EB]                                        | 4.07	| 2.70 | 3.14	  | 0.55 | 9.79	| 12.20	| 17.00	| 21.89	| 0.18%       | 2.11%         |
| GGW [^EB]                                        | 4.05	| 2.60 | 3.06	  | 0.56 | 9.78	| 12.30	| 16.97	| 21.16 | 0.00%       | 2.64%         |
| GE1 [^EB]                                        | 3.89	| 2.77 | 3.10	  | 0.78 | 8.83	| 11.09	| 14.57	| 22.60 | 0.00%       | 0.53%         |
| GE2 [^EB]                                        | 3.89	| 2.88 | 3.13	  | 0.75 | 8.80	| 10.90	| 14.02	| 23.10 | 0.35%       | 0.53%         |
| Cheng et al. [^PCA]                              | 4.03	| 2.49 | 2.92   |	0.52 | 9.89 | 12.70 | 16.78 | 28.21 | 0.00%       | 2.99%         |
| Funt et al. [^Funt96]                            | 3.28	| 2.53 | 2.72   |	0.92 | 6.80 |  8.68 | 11.49 | 15.37 | TBC         | TBC           |
| Corrected Moments <br /> (9 Edge Mom.)[^corrmom] | 2.84	| 2.00 | 2.23	  | 0.71 | 6.32 |  7.56	| 12.38	| 16.60 | 0.00%       | 2.29%         |
| Cheng et al. [^cheng]                            | 2.56	| 1.66 | 1.83   |	0.36 | 6.36	|  8.14 |	13.17	| 20.36 | 0.18%       | 5.11%         |
| FFCC (model j) [^ffcc]                           | 2.23 | 1.45 | 1.59   | 0.35 | 5.46 |  7.33 | 10.85 | 17.27 | 0.35%       | 5.46%         |
| FC<sup>4</sup> [^fc4]                            | 2.14 | 1.44 | 1.57   | 0.40 | 5.08 |  6.50 | 12.75 | 15.28 | 0.06%       | 4.28%         |
| Conv. Mean [^convmean]                           | 2.50	| 1.73 | 1.90   |	0.51 | 5.81 |  7.93 | 12.42 |	16.13 | 0.06%       | 3.81%         |
| QU [^QU]                                         | 3.26	| 2.07 | 2.38	  | 0.44 | 7.98 | 10.78 | 14.32	| 21.68 | TBC         | TBC           |
| QU+ft [^QU]                                      | 3.02 | 2.07 | 2.26   | 0.50 | 7.15 | 9.22  | 12.92 | 17.05 | TBC         | TBC           |

[^EB]: Van De Weijer, J., Gevers, T., & Gijsenij, A. (2007). Edge-based color constancy. IEEE Transactions on image processing, 16(9), 2207-2214.
[^PCA]: Cheng, D., Prasad, D. K., & Brown, M. S. (2014). Illuminant estimation for color constancy: why spatial-domain methods work and the role of the color distribution. JOSA A, 31(5), 1049-1058.
[^Funt96]: Funt, B., Cardei, V., & Barnard, K. (1996, November). Learning color constancy. In Fourth Color Imaging Conference: Color Science, Systems and Applications (pp. 58-60).
[^corrmom]: Finlayson, G. D. (2013). Corrected-moment illuminant estimation. In Proceedings of the IEEE International Conference on Computer Vision (pp.     1904-1911).
[^cheng]: Cheng, D., Price, B., Cohen, S., & Brown, M. S. (2015). Effective learning-based illuminant estimation using simple features. In Proceedings of     the IEEE conference on computer vision and pattern recognition (pp. 1000-1008).
[^ffcc]: Barron, J. T., & Tsai, Y. T. (2017). Fast fourier color constancy. In Proceedings of the IEEE conference on computer vision and pattern             recognition (pp. 886-894).
[^fc4]: Hu, Y., Wang, B., & Lin, S. (2017). Fc4: Fully convolutional color constancy with confidence-weighted pooling. In Proceedings of the IEEE             conference   on computer vision and pattern recognition (pp. 4085-4094).
[^convmean]: Gong, H. (2019, September). Convolutional Mean: A Simple Convolutional Neural Network for Illuminant Estimation. In British Machine Vision       Conference. BMVA Press.
[^QU]: Bianco, S., & Cusano, C. (2019). Quasi-unsupervised color constancy. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 12212-12221).


### Cite
If you use the code provided in this repository please cite our original work:
```
@inproceedings{TBD
}
```
