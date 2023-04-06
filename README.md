# fairCC

| Method               | Mean | Med. | Tri-m. | B-25 | W-25 | 95-Q  | 99-Q  | Max   | Intra-patch | Inter-patches |
| :------------------- | ----:|-----:|-------:|-----:|-----:|------:|------:|------:|------------:|--------------:|
| SoG [^1]             | 4.07	| 2.70 | 3.14	  | 0.55 | 9.79	| 12.20	| 17.00	| 21.89	| 0.18%       | 0.00%         |
| GGW [^1]             | 4.05	| 2.60 | 3.06	  | 0.56 | 9.78	| 12.30	| 16.97	| 21.16 | 0.00%       | 0.00%         |
| GE1 [^1]             | 3.89	| 2.77 | 3.10	  | 0.78 | 8.83	| 11.09	| 14.57	| 22.60 | 0.00%       | 0.00%         |
| GE2 [^1]             | 3.89	| 2.88 | 3.13	  | 0.75 | 8.80	| 10.90	| 14.02	| 23.10 | 0.00%       | 0.00%         |
| Cheng et al. [^X]    | 2.56	| 1.66 | 1.83   |	0.36 | 6.36	|  8.14 |	13.17	| 20.36 | tbc         | tbc           |
| FFCC (model j) [^2]  | 2.23 | 1.45 | 1.59   | 0.35 | 5.46 |  7.33 | 10.85 | 17.27 | 0.35%       | 5.46%         |
| FC4 [^3]             | 2.14 | 1.44 | 1.57   | 0.40 | 5.08 |  6.50 | 12.75 | 15.28 | 0.06%       | 4.28%         |
| Conv. Mean [^4]      | 2.50	| 1.73 | 1.90   |	0.51 | 5.81 |  7.93 | 12.42 |	16.13 | 0.06%       | 3.81%         |


[^1]: Van De Weijer, J., Gevers, T., & Gijsenij, A. (2007). Edge-based color constancy. IEEE Transactions on image processing, 16(9), 2207-2214.
[^2]: Barron, J. T., & Tsai, Y. T. (2017). Fast fourier color constancy. In Proceedings of the IEEE conference on computer vision and pattern recognition     (pp. 886-894).
[^X]: Cheng, D., Price, B., Cohen, S., & Brown, M. S. (2015). Effective learning-based illuminant estimation using simple features. In Proceedings of the     IEEE conference on computer vision and pattern recognition (pp. 1000-1008).
[^3]: Hu, Y., Wang, B., & Lin, S. (2017). Fc4: Fully convolutional color constancy with confidence-weighted pooling. In Proceedings of the IEEE conference   on computer vision and pattern recognition (pp. 4085-4094).
[^4]: Gong, H. (2019, September). Convolutional Mean: A Simple Convolutional Neural Network for Illuminant Estimation. In British Machine Vision             Conference. BMVA Press.
