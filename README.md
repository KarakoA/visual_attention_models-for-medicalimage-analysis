# Visual Attention Models for Medical Image Analysis

# Own results
| Model                          |   Error |      Dataset        |
|:-------------------------------|:--------:|:------------------:|
| 6 glimpses, 8x8, 3 scales  | 0.78 % | MNIST               | 
| 6 glimpses, 12x12, 3 scales| 1.34 %   | Transformed MNIST   | 
| 6 glimpses, 12x12, 5 scales| 63.6 % | Augmented Medical MNIST | 

# Baselines

| Model                          |   Error |      Dataset        | Author |
|:-------------------------------|:--------:|:------------------:| :------:|
| RAM, 7 glimpses, 8 × 8, 1 scale | 1.07 % | MNIST               | Mnih et. al. 
| RAM, 8 glimpses, 12 × 12, 3 scales | 1.22 %   | Transformed MNIST   | Mnih et. al. 

