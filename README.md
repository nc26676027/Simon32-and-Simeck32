# Simon32-and-Simeck32
**`Title`**：Rotational-XOR Cryptanalysis on SIMON-like Block Ciphers  
**`Author`**: Jinyu Lu, Yunwen Liu, Tomer Ashur, Bing Sun and Chao Li   
**`Abstract`**：In this paper, we generalise the idea of rotational-XOR cryptanalysis to SIMON-like block ciphers, a class of AND-RX ciphers with a rotational-invariant round function. We analyse the theoretical evaluation of RX-differences passing through SIMON-like ciphers, and formulate an SMT model for searching rotational-XOR characteristics in SIMECK and SIMON. As an application, we find a 15-round
RX-characteristic in SIMECK32 with a probability 2 <sup>−16</sup> under 2 <sup>40</sup> weak keys, and a 16-round one for SIMECK48 with a probability 2 <suo>−20</sup> under 2 <sup>70</sup> weak keys. The characteristics can be further extended to 19/25 rounds for SIMECK32/SIMECK48, respectively. As far as we know, these RX-characteristics are the longest distinguishers found for SIMECK32 and SIMECK48, which cover more rounds than the best differential characteristics found by Liu et al. at FSE 2017 and the integral distinguishers by Wang et al. at ASIACRYPT 2019. And when the number of rounds equals, RX-characteristics require less data to detect. For SIMON32, the RX-characteristics we find cover up to 11 rounds with probability 2 <sup>−26</sup>. In addition, we study the impact of the key schedule on the RX-characteristics in SIMON-like ciphers. It appears that adopting the same structure in the round function and the
key schedule of SIMECK makes it more vulnerable to RX-cryptanalysis than its non-symmetric counterpart SIMON.
