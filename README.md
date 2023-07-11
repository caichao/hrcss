# hrcss
Sample code for various aerial acoustic communication systems


# Matlab sample codes for HRCSS
This code package provides a foundational implementation of the High-Rate Chirp Spread Spectrum (HRCSS) and its aerial acoustic communication (AAC) counterparts, such as Chirp Spread  Spectrum (CSS), Orthogonal Chirp Spread Spectrum (OCSS), Orthogonal Frequency Division 
Multiplexing (OFDM), and Orthogonal Chirp Division Multiplexing (OCDM). HRCSS is a robust method for AAC, offering high speed and long-range capabilities while effectively adapting to dynamic channels [1].



# Matlab scripts and functions:
Matlab Functions Description
chirp_up.m Generate up chirp signal
chirp_down.m Generate down chirp signal
Params.m Basic parameter settings
PreambleDetection.m Premable detection method with one chirp
PreambleDetectionTriple.m Premable detection method with three chirps in [1]
PreambleNormalization.m Preamble normalization method in [1]
RMS_filter.m RMS filter
CSS.m Baseline model of Chirp spread spectrum AAC scheme
OCSS.m Baseline model of Chirp spread spectrum AAC scheme
OCDM.m Baseline model of OCDM AAC scheme
OFDM.m Baseline model of OFDM AAC scheme
HRCSS.m Baseline model of HRCSS AAC scheme in [1]

# Remarks
1. The files CSS.m, OCSS.m, OCDM.m, OFDM.m, and HRCSS.m encompass the entire communication pipeline. By running these codes, quick simulations can be performed with different settings. Minor modifications would be necessary for these to be applicable in practical AAC
scenarios.
2. The provided codes offer straightforward implementations of various aerial acoustic communication (AAC) modulation schemes. Users have the flexibility to incorporate advanced modules into these base implementations, tailoring them to meet their unique requirements and 
application-specific demands. For example, adjustments can be made to incorporate features such as the addition of a Cyclic Prefix (CP), equalization, compensation etc.

# References
[1]. C. Cai, Z. Chen, J. Luo, H. Pu, M. Hu and R. Zheng, "Boosting Chirp Signal Based Aerial Acoustic Communication Under Dynamic Channel Conditions," in IEEE Transactions on Mobile Computing, vol. 21, no. 9, pp. 3110-3121, 1 Sept. 2022, doi: 10.1109/TMC.2021.3051665

If you find it useful, please cite our paper.
```
@ARTICLE{9325082,
  author={Cai, Chao and Chen, Zhe and Luo, Jun and Pu, Henglin and Hu, Menglan and Zheng, Rong},
  journal={IEEE Transactions on Mobile Computing}, 
  title={Boosting Chirp Signal Based Aerial Acoustic Communication Under Dynamic Channel Conditions}, 
  year={2022},
  volume={21},
  number={9},
  pages={3110-3121},
  doi={10.1109/TMC.2021.3051665}}

```
