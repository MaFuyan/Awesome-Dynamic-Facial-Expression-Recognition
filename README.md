# Awesome Dynamic Facial Expression Recognition

- [Awesome Dynamic Facial Expression Recognition](#awesome-dynamic-facial-expression-recognition)
  - [DFEW Benchmark [ACM MM 2021]](#dfew-benchmark-acm-mm-2021)
  - [FERV39k Benchmark [CVPR 2022]](#ferv39k-benchmark-cvpr-2022)
    - [Basic DFER](#basic-dfer)
    - [Cross-Scenario Challenge](#cross-scenario-challenge)
  - [MAFW Benchmark [ACM MM 2022]](#mafw-benchmark-acm-mm-2022)
    - [11-Class Uni-Modal Single Expression Classification](#11-class-uni-modal-single-expression-classification)
    - [11-Class Multi-Modal Single Expression Classification](#11-class-multi-modal-single-expression-classification)
  - [CAER Benchmark [ICCV 2021]](#caer-benchmark-iccv-2021)
  - [AFEW Benchmark [IEEE Multimedia 2012]](#afew-benchmark-ieee-multimedia-2012)
  - [Referances](#referances)

## [DFEW Benchmark](https://dfew-dataset.github.io/) [ACM MM 2021]

<table>
<thead>
  <tr>
    <th rowspan="2">Methods</th>
    <th colspan="7">Accuracy of Each Emotion (%)</th>
    <th colspan="2">Metrics (%)</th>
  </tr>
  <tr>
    <th>Happy</th>
    <th>Sad</th>
    <th>Neutral</th>
    <th>Anger</th>
    <th>Surprise</th>
    <th>Disgust</th>
    <th>Fear</th>
    <th>UAR</th>
    <th>WAR</th>
  </tr>
</thead>
<tbody>
  <tr>
    <th>3DR18</th>
    <th>76.32</th>
    <th>50.21</th>
    <th>64.18</th>
    <th>62.85</th>
    <th>47.52</th>
    <th>0.00</th>
    <th>24.56</th>
    <th>46.52</th>
    <th>58.27</th>
  </tr>
  <tr>
    <th>R18+LSTM</th>
    <th>83.56</th>
    <th>61.56</th>
    <th>68.27</th>
    <th>65.29</th>
    <th>51.26</th>
    <th>0.00</th>
    <th>29.34</th>
    <th>51.32</th>
    <th>63.85</th>
  </tr>
  <tr>
    <th>R18+GRU</th>
    <th>82.87</th>
    <th>63.83</th>
    <th>65.06</th>
    <th>68.51</th>
    <th>52.00</th>
    <th>0.86</th>
    <th>30.14</th>
    <th>51.68</th>
    <th>64.02</th>
  </tr>
  <tr>
    <th>EC-STFL<sup>[1]</sup></th>
    <th>79.18</th>
    <th>49.05</th>
    <th>57.85</th>
    <th>60.98</th>
    <th>46.15</th>
    <th>2.76</th>
    <th>21.51</th>
    <th>45.35</th>
    <th>56.51</th>
  </tr>
  <tr>
    <th>Former-DFER<sup>[2]</sup></th>
    <th>84.05</th>
    <th>62.57</th>
    <th>67.52</th>
    <th>70.03</th>
    <th>56.43</th>
    <th>3.45</th>
    <th>31.78</th>
    <th>53.69</th>
    <th>65.70</th>
  </tr>
  <tr>
    <th>EST<sup>[3]</sup></th>
    <th>86.87</th>
    <th>66.58</th>
    <th>67.18</th>
    <th>71.84</th>
    <th>47.53</th>
    <th>5.52</th>
    <th>28.49</th>
    <th>53.43</th>
    <th>65.85</th>
  </tr>
  <tr>
    <th>STT<sup>[4]</sup></th>
    <th>87.36</th>
    <th>67.90</th>
    <th>64.97</th>
    <th>71.24</th>
    <th>53.10</th>
    <th>3.49</th>
    <th>34.04</th>
    <th>54.58</th>
    <th>66.65</th>
  </tr>
  <tr>
    <th>NR-DFERNet<sup>[5]</sup></th>
    <th>88.47</th>
    <th>64.84</th>
    <th>70.03</th>
    <th>75.09</th>
    <th>61.60</th>
    <th>0.00</th>
    <th>19.43</th>
    <th>54.21</th>
    <th>68.19</th>
  </tr>
</tbody>
</table>

## [FERV39k Benchmark](https://wangyanckxx.github.io/Proj_CVPR2022_FERV39k.html) [CVPR 2022]

### Basic DFER

<table>
<thead>
  <tr>
    <th rowspan="2">Methods</th>
    <th colspan="7">Accuracy of Each Emotion (%)</th>
    <th colspan="2">Metrics (%)</th>
  </tr>
  <tr>
    <th>Happy</th>
    <th>Sad</th>
    <th>Neutral</th>
    <th>Anger</th>
    <th>Surprise</th>
    <th>Disgust</th>
    <th>Fear</th>
    <th>UAR</th>
    <th>WAR</th>
  </tr>
</thead>
<tbody>
  <tr>
    <th>R18+LSTM</th>
    <th>61.91</th>
    <th>31.95</th>
    <th>61.70 </th>
    <th>45.93 </th>
    <th>14.26 </th>
    <th>0.00 </th>
    <th>0.70 </th>
    <th>30.92 </th>
    <th>42.59</th>
  </tr>
  <tr>
    <th>VGG13+LSTM</th>
    <th>66.26 </th>
    <th>51.26 </th>
    <th>53.22 </th>
    <th>37.93 </th>
    <th>13.64 </th>
    <th>0.43 </th>
    <th>4.18 </th>
    <th>32.42 </th>
    <th>43.37</th>
  </tr>
  <tr>
    <th>C3D</th>
    <th>48.20 </th>
    <th>35.53 </th>
    <th>52.71 </th>
    <th>13.72 </th>
    <th>3.45 </th>
    <th>4.93 </th>
    <th>0.23 </th>
    <th>22.68 </th>
    <th>31.69</th>
  </tr>
  <tr>
    <th>3DR18</th>
    <th>57.64 </th>
    <th>28.21 </th>
    <th>59.60 </th>
    <th>33.29 </th>
    <th>4.70 </th>
    <th>0.21 </th>
    <th>3.02 </th>
    <th>26.67 </th>
    <th>37.57</th>
  </tr>
  <tr>
    <th>Two C3D<sup>[6]</sup></th>
    <th>54.85 </th>
    <th>52.91 </th>
    <th>60.67 </th>
    <th>31.34 </th>
    <th>5.96 </th>
    <th>2.36 </th>
    <th>6.96 </th>
    <th>30.72 </th>
    <th>41.77</th>
  </tr>
  <tr>
    <th>Two R18+LSTM<sup>[6]</sup></th>
    <th>59.00 </th>
    <th>45.87 </th>
    <th>61.90 </th>
    <th>40.15 </th>
    <th>9.87 </th>
    <th>1.71 </th>
    <th>0.46 </th>
    <th>31.28 </th>
    <th>43.2</th>
  </tr>
  <tr>
    <th>Two VGG13+LSTM<sup>[6]</sup></th>
    <th>69.65 </th>
    <th>47.31 </th>
    <th>52.55 </th>
    <th>47.88 </th>
    <th>7.68 </th>
    <th>1.93 </th>
    <th>2.55 </th>
    <th>32.79 </th>
    <th>44.54</th>
  </tr>
  <tr>
    <th>Former-DFER<sup>[2]</sup></th>
    <th>67.57</th>
    <th>44.16</th>
    <th>51.81</th>
    <th>48.93</th>
    <th>25.09</th>
    <th>10.80</th>
    <th>9.80</th>
    <th>36.88</th>
    <th>45.72</th>
  </tr>
  <tr>
  <th>NR-DFERNet<sup>[5]</sup></th>
  <th>69.18</th>
  <th>54.77</th>
  <th>51.12</th>
  <th>49.70</th>
  <th>13.17</th>
  <th>0.00</th>
  <th>0.23</th>
  <th>33.99</th>
  <th>45.97</th>
  </tr>
</tbody>
</table>

### Cross-Scenario Challenge

## [MAFW Benchmark](https://mafw-database.github.io/MAFW/) [ACM MM 2022]

### 11-Class Uni-Modal Single Expression Classification

### 11-Class Multi-Modal Single Expression Classification

## [CAER Benchmark](https://caer-dataset.github.io/) [ICCV 2021]

## [AFEW Benchmark](https://cs.anu.edu.au/few/AFEW.html) [IEEE Multimedia 2012]

## [Referances]()
1. Jiang X, Zong Y, Zheng W, et al. Dfew: A large-scale database for recognizing dynamic facial expressions in the wild. ACM MM, 2020. [[Paper](https://doi.org/10.1145/3394171.3413620)]
2. Zhao Z, Liu Q. Former-dfer: Dynamic facial expression recognition transformer. ACM MM, 2021. [[Paper](https://doi.org/10.1145/3394171.3413620)] [[Code](https://github.com/zengqunzhao/Former-DFER)]
3. Liu Y, Wang W, Feng C, et al. Expression Snippet Transformer for Robust Video-based Facial Expression Recognition. arXiv, 2021. [[Paper](https://arxiv.org/abs/2109.08409)]
4. Ma F, Sun B, Li S. Spatio-Temporal Transformer for Dynamic Facial Expression Recognition in the Wild. arXiv, 2022. [[Paper](https://arxiv.org/abs/2205.04749)]
5. Li H, Sui M, Zhu Z. NR-DFERNet: Noise-Robust Network for Dynamic Facial Expression Recognition. arXiv, 2022.[[Paper](https://arxiv.org/abs/2206.04975)]
6. Wang Y, Sun Y, Huang Y, et al. FERV39k: A Large-Scale Multi-Scene Dataset for Facial Expression Recognition in Videos. CVPR, 2022.[[Paper](https://arxiv.org/abs/2203.09463)]



