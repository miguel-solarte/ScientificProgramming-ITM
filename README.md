# SCIENTIFIC COMPUTING

# Index

1. [Installing of Necesareis Libraries](#1-installing-of-necesareis-libraries)
   - [Enviroment env](#enviroment-env)
2. [Directory Structure](#2-directory-structure)
3. [Data Constellations mQAM](#3-data-constellations-m-qam)
4. [Preprocessing](#4-preprocessing)
5. [Analysis and Visualization](#5-analysis-and-visualization)
6. [Analysis of the computational complexity of Spectral Clustering](#6-analysis-of-the-computational-complexity-of-spectral-clustering)


   

# 1. Installing of Necesareis Libraries 

To work with this repository, you should follow the instructions below.

Note: These instructions are only applicable for Linux systems.

## Enviroment env

```sh
git clone
cd ScientificProgramming-ITM
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
# 2. Directory Structure 

```sh
miguel-solarte/ScientificProgramming-ITM
│
├── Data_contellations_m-QAM/
|   |
|   ├── Contellation_16QAM/
|   ├── ideal_contellation_16QAM.csv
│   ├── sintetic_data_16QAM_level90/
|   |   |
|   |   ├── data_16AQM_SNR_5_level90.csv
|   |   ├── data_16AQM_SNR_7_level90.csv
|   |   ├── data_16AQM_SNR_10_level90.csv
|   |   ├── data_16AQM_SNR_12_level90.csv
|   |   ├── data_16AQM_SNR_15_level90.csv
|   |   ├── data_16AQM_SNR_17_level90.csv
|   |   └── data_16AQM_SNR_20_level90.csv
|   |
│   ├── sintetic_data_16QAM_level100/
|   |   |
|   |   ├── data_16AQM_SNR_5_level100.csv
|   |   ├── data_16AQM_SNR_7_level100.csv
|   |   ├── data_16AQM_SNR_10_level100.csv
|   |   ├── data_16AQM_SNR_12_level100.csv
|   |   ├── data_16AQM_SNR_15_level100.csv
|   |   ├── data_16AQM_SNR_17_level100.csv
|   |   └── data_16AQM_SNR_20_level100.csv
|   |
│   ├──  sintetic_data_16QAM_level110/
|   |    |
|   |    ├── data_16AQM_SNR_5_level110.csv
|   |    ├── data_16AQM_SNR_7_level110.csv
|   |    ├── data_16AQM_SNR_10_level110.csv
|   |    ├── data_16AQM_SNR_12_level110.csv
|   |    ├── data_16AQM_SNR_15_level110.csv
|   |    ├── data_16AQM_SNR_17_level110.csv
|   |    └── data_16AQM_SNR_20_level110.csv
|   │
|   ├── Contellation_32QAM/
|   |
|   ├── ideal_contellation_32QAM.csv
│   ├── sintetic_data_32QAM_level90/
|   |   |
|   |   ├── data_32AQM_SNR_5_level90.csv
|   |   ├── data_32AQM_SNR_7_level90.csv
|   |   ├── data_32AQM_SNR_10_level90.csv
|   |   ├── data_32AQM_SNR_12_level90.csv
|   |   ├── data_32AQM_SNR_15_level90.csv
|   |   ├── data_32AQM_SNR_17_level90.csv
|   |   └── data_32AQM_SNR_20_level90.csv
|   |
│   ├── sintetic_data_32QAM_level100/
|   |   |
|   |   ├── data_32AQM_SNR_5_level100.csv
|   |   ├── data_32AQM_SNR_7_level100.csv
|   |   ├── data_32AQM_SNR_10_level100.csv
|   |   ├── data_32AQM_SNR_12_level100.csv
|   |   ├── data_32AQM_SNR_15_level100.csv
|   |   ├── data_32AQM_SNR_17_level100.csv
|   |   └── data_32AQM_SNR_20_level100.csv
|   |
│   └── sintetic_data_32QAM_level110/
|   |   |
|   |   ├── data_32AQM_SNR_5_level110.csv
|   |   ├── data_32AQM_SNR_7_level110.csv
|   |   ├── data_32AQM_SNR_10_level110.csv
|   |   ├── data_32AQM_SNR_12_level110.csv
|   |   ├── data_32AQM_SNR_15_level110.csv 
|   |   ├── data_32AQM_SNR_17_level110.csv
|   |   └── data_32AQM_SNR_20_level110.csv
│   |
|   ├── Contellation_64QAM/
|   |
|   ├── ideal_contellation_64QAM.csv
|   ├── sintetic_data_64QAM_level90/
|   |   |
|   |   ├── data_64AQM_SNR_5_level90.csv
|   |   ├── data_64AQM_SNR_7_level90.csv
|   |   ├── data_64AQM_SNR_10_level90.csv
|   |   ├── data_64AQM_SNR_12_level90.csv
|   |   ├── data_64AQM_SNR_15_level90.csv
|   |   ├── data_64AQM_SNR_17_level90.csv
|   |   └── data_64AQM_SNR_20_level90.csv
|   |
|   ├── sintetic_data_64QAM_level100/
|   |   |
|   |   ├── data_64AQM_SNR_5_level100.csv
|   |   ├── data_64AQM_SNR_7_level100.csv
|   |   ├── data_64AQM_SNR_10_level100.csv
|   |   ├── data_64AQM_SNR_12_level100.csv
|   |   ├── data_64AQM_SNR_15_level100.csv
|   |   ├── data_64AQM_SNR_17_level100.csv
|   |   └── data_64AQM_SNR_20_level100.csv
|   |
|   └── sintetic_data_64QAM_level110/
|       |
|       ├── data_64AQM_SNR_5_level110.csv
|       ├── data_64AQM_SNR_7_level110.csv
|       ├── data_64AQM_SNR_10_level110.csv
|       ├── data_64AQM_SNR_12_level110.csv
|       ├── data_64AQM_SNR_15_level110.csv
|       ├── data_64AQM_SNR_17_level110.csv
|       └── data_64AQM_SNR_20_level110.csv
|
|
├── Preprocessing/
|   |
|   └── Preprocessing.ipynb
|
├── Analysis/
|   |
|   ├── results_QAM/
|   └── Analysis.ipynb
|
├── Figures
|   |
|   └── data_64AQM_SNR_20_level110.csv
|
├── rerults_AQM
|
├── .gitignore
|
└── requirements.md

```

# 3. Data Constellations m-QAM

The dataset of QAM constellations was generated using the MATLAB Communications Toolbox with the purpose of obtaining a dataset containing constellations such as 16-QAM, 32-QAM, and 64-QAM. Non-linear noise was added to each constellation to emulate the conditions caused by light passing through a long optical channel. Additionally, each constellation was varied by adjusting inherent features like signal-to-noise ratio (SNR) with a range from 5 dB to 20 dB, and frequency offset, with values of -90, -100, and -110 dB/Hz at 1 MHz, for a transmission frequency of 10 GHz.Finally, it is important to note that each file with the .csv extension contains 100,000 symbols.


# 4. Preprocessing

In this section, `Preprocessing/preprocessing.ipynb`, you may find various data preprocessing steps, including:

- **Derivation of the image generated for the mQAM constellation**: The derivative was implemented for edge detection. Before applying edge detection, an erosion process is necessary to connect the points. Without erosion, the resulting image will be the same as if only edge detection had been performed.

- **The first part of the spectral clustering algorithm**: Spectral clustering consists of two stages. The first stage involves matrix operations to represent the data in a new space defined by eigenvectors. The second stage applies k-means clustering to the data in this eigenvector space. If k-means is applied directly in the original data space, it cannot properly separate the data. However, when k-means is applied in the eigenvector space, it effectively partitions the data.


# 5. Analysis and Visualization

For the section `Analysis/analysis.ipynb`, various analyses were performed, starting with data visualization using violin plots. This was followed by a statistical analysis of custom data, where ANOVA was conducted. Finally, a data separability analysis was performed by implementing the spectral clustering algorithm and evaluating the results with appropriate performance metrics, such as Bit Error Rate (BER).

In the `Analysis/` directory, there is a folder named `results_QAM`, where you can save the results obtained from performing spectral clustering and evaluating Bit Error Rate (BER).

# 6. Analysis of the computational complexity of Spectral Clustering

To explain the computational complexity of spectral clustering, we should analyze the main components that compose spectral clustering.

## Computational complexity of the affinity matrix $A$

- Let $S = {s_{1}, ..., s_{n}}$ in $\mathbb{R}^{l}$ be a data set that will be partitioned into $k$ groups, applying a radial basis function (RBF) kernel to build a symmetric matrix known as the affinity matrix $A \in \mathbb{R}^{n\times n}$. The RBF kernel includes a parameter $\sigma$ --referred to as kernel bandwidth-- that must be adjusted to achieve appropriate data clustering


$$A_{ij}=exp\left ( -\frac{\left \| s_{i} - s_{j} \right \|^{2}}{2\sigma ^{2}} \right )$$
if $i \neq j$ and $A_{ii} = 0$


```python
A = np.zeros((n,n)) 

def dist_euclidia(sx2, sx1, sy2, sy1, sigma):
   euclidean_dist = (sx2 - sx1) ** 2 + (sy2 - sy1) ** 2
   return np.exp(-(euclidean_dist / (2 * (sigma) ** 2)))

sigma = 1

for i in range(n): #for number 1
   for j in range(n):#for number 2
      if i == j:
         A[i,j] = 1e-10
      else:
         A[i,j] = dist_euclidia(toy_dataset[i,0], 
         toy_dataset[j,0], 
         toy_dataset[i,1],    
         toy_dataset[j,1], 
         sigma)
```

`for i in range(n)`: Time complexity of $O_{for_1}(n)$

`for j in range(n)`: Time complexity of $O_{for_2}(n)$

`if i == j`: Time complexity of $O(1)$

`A[i,j] = 1e-10`: Time complexity of $O(1)$

`A[i,j] = dist_euclidia(arg)`: Time complexity of $O(1)$

`dist_euclidia(sx2, sx1, sy2, sy1, sigma)`: Time complexity of $O(1)$

Since the first for loop and the second for loop are nested, we should multiply their complexities.:

$(O_{for_1}(n))\times(O_{for_2}(n)\times(O(1) + O(1) + O(1) + O(1))) = O(n^2)$ 

So, the computational complexity of the affinity matrix $A$ is $O(n^2)$.


## Computational complexity of the diagonal matrix $D$ and matrix $D$ renormalized

- Given the computed affinity matrix $A$, a diagonal matrix $D$ is defined, where their $(i,i)-elements$ represent the sum of the elements of the $i-th$ row of matrix $A$. Subsequently, the diagonal elements of matrix $D$ are normalized

$$D_{ii} = \sum_{j} A_{ij}$$


$$D^{-\frac{1}{2}} = \frac{1}{\sqrt{D_{ii}}}$$

```python
D = np.zeros((n,n))
D_inv = np.zeros((n,n))

for i in range(n): #for number 3
    for j in range(i, n): #for number 4
        D[i,i] = D[i,i] + A[i,j]
    D_inv[i,i] = 1 /  np.sqrt(D[i,i])
```

`for i in range(n)`: Time complexity of $O_{for_3}(n)$

`for j in range(n)`: Time complexity of $O_{for_4}(n)$

`D[i,i] = D[i,i] + A[i,j]`: Time complexity of $O(1)$

`D_inv[i,i] = 1 /  np.sqrt(D[i,i])`: Time complexity of $O(1)$

Since the first for loop and the second for loop are nested, we should multiply their complexities.:

$(O_{for_3}(n)\times O(1)) \times (O_{for_4}(n)\times(O(1))) = O(n^2)$ 

The computational complexity of diagonal matrix $D$ and matrix $D$ renormalized is $O(n^2)$.

## Computational complexity of the Laplacian matrix $L$, matirx of eigenvector $X$ and matrix $Y$

- The Laplacian matrix $L$ is constructed from the matrices $A$ and $D^{-1/2}$, and is denoted by $L = D^{-1/2} A D^{-1/2}$. The first $k$ eigenvectors $x_1, x_2, \ldots, x_k$ of the matrix $L$ will be used to partition the data set $S$ into $k$ mutually exclusive clusters. This process results in the building of the matrix $X = [x_1 \ x_2 \ \ldots \ x_k] \in \mathbb{R}^{n \times k}$. Subsequently, the matrix $X$ is renormalized following equation

$$ Y_{ij}=\frac{X_{ij}}{\left (\sum_{j}X_{ij}^{2}  \right )^\frac{1}{2}}$$

### Computational complexity of the Laplacian matrix $L$

The Laplacian matrix is computed using two matrix multiplications. First, we compute $C = D^{-1/2} \cdot A$, and then $L = C \cdot D^{-1/2}$. Below is the Python implementation for matrix multiplication and the associated computational complexity analysis:

```python
def mult_mat(size, matrix_1, matrix_2):
    one_x_two = np.zeros((size,size))

    for i in range(n): #for number 5
        for j in range(n): #for number 6
            for k in range(n): #for number 7
                flag = matrix_1[i,k] * matrix_2[k,j]
                one_x_two[i,j] = one_x_two[i,j] + flag

    return one_x_two

D_inv_A = mult_mat(n,D_inv,A)
L = mult_mat(n,D_inv_A,D_inv)
```

`for i in range(n)`: Time complexity of $O_{for_5}(n)$

`for j in range(n)`: Time complexity of $O_{for_6}(n)$

`for k in range(n)`: Time complexity of $O_{for_7}(n)$

`flag = matrix_1[i,k] * matrix_2[k,j]`: Time complexity of $O(1)$

`one_x_two[i,j] = one_x_two[i,j] + flag`: Time complexity of $O(1)$

Thus, the time complexity for a single matrix multiplication is:

$$O_{for_5}(n)\times O_{for_6}(n) \times (O_{for_7}(n) + O(1) + O(1))  = O(n^3)$$

Since calculating the Laplacian matrix involves two matrix multiplications:

$C = D^{-1/2} \cdot A$, with complexity $O(n^3)$

$L = C \cdot D^{-1/2}$, with complexity $O(n^3)$

The total computational complexity is:

$$L = O(n^3) + O(n^3) = 2O(n^3)$$

Asymptotically, this simplifies to:

$$L = O(n^3)$$

### Computational complexity of the matirx of eigenvector $X$

To obtain the eigenvector matrix $X$ from the Laplacian matrix $L$, we perform the Jacobi method. The computational complexity is explained below:

```python
theta = 0
eigenvec = np.identity(n)
for _ in range(10): #for number 8
  for i in range(n): #for number 9
      for j in range(i+1,n): #for number 10

         theta = np.arctan(2* (L[i,j] / (L[j, j] - L[i,i]))) / 2

         for m in range(n): #for number 11
            a = L[i,m] * cos(theta) + L[j,m] * (-sin(theta))
            b = L[i,m] * sin(theta) + L[j,m] * cos(theta)

            L[i,n] = a
            L[j,n] = b
            
                

         for m in range(n): #for number 12
            c = L[n,i] * cos(theta) + L[m,j] * (-sin(theta))
            d = L[m,i] * sin(theta) + L[m,j] * cos(theta)

            L[n,i] = c
            L[n,j] = d
            

         for m in range(n): #for number 13
            e = L[n][i] * cos(theta) + L[n][j] * (-sin(theta))
            f = L[n][i] * sin(theta) + L[n][j] * cos(theta)

            eigenvec[n][i] = e
            eigenvec[n][j] = f     
```

`for i in range(n)`: Time complexity of $O_{for_9}(n)$

`for j in range(i+1,n)`: Time complexity of $O_{for_{10}}(n)$

`for m in range(n)`: Time complexity of $O_{for_{11}}(n), O_{for_{12}}(n), O_{for_{13}}(n)$

Arithmetic operations (e.g., `a = L[i,m] * cos(theta) + L[j,m] * (-sin(theta))`): Time complexity $O(1)$

The total complexity for one outer iteration is:

$$ O_{for_9}(n) \times (O_{for_{10}}(n) \times ( O_{for_{10}}(n) + O_{for_{11}}(n) + O_{for_{12}}(n)))$$

$$O_{for_9}(n) \times O_{for_{10}}(n) \times 3O(n) = O(n^3)$$

If the Jacobi method is repeated for $iter$ iterations (corresponding to the loop, 'for number 9'), the total complexity becomes:

$$ iter \cdot O(n^3)$$

However, for a single iteration, the computational complexity of constructing the eigenvector matrix $X$ is $O(n^3)$. 

### Computational complexity of the matrix $Y$

The rows of matrix $Y$ are considered points in $\mathbb{R}^{k}$, and the data set is partitioned into $k$ clusters via the k-means algorithm. Accordingly, the initial point designated as $s_{i}$ is assigned to cluster $j$ strictly when the row $i$ of the matrix $Y$ has been allocated to cluster $j$. 

The computational complexity is analyzed as follows:

```python
Y = np.zeros((n,n))
suma = 0

for i in range(n): #for number 14
    for j in range(n): #for number 15
        for k in range(j, n): #for number 16

            suma = suma + (X[i,k]) ** 2

        Y[i,j] = X[i,j] / np.sqrt(suma)

        suma = 0
```

`for i in range(n)`: Time complexity of $O_{for_{14}}(n)$

`for j in range(i+1,n)`: Time complexity of $O_{for_{15}}(n)$

`for k in range(i+1,n)`: Time complexity of $O_{for_{16}}(n)$

Arithmetic operations (e.g., `suma = suma + (X[i,k]) ** 2`): Time complexity $O(1)$

The combined time complexity is computed as:

$$ O_{for_{14}}(n) \times (O_{for_{15}}(n) + O(1)) \times (O_{for_{16}}(n) + O(1))$$

Since the arithmetic operations are constant-time, they do not affect the asymptotic complexity. Therefore:

$$O_{for_{14}}(n) \times O_{for_{15}}(n) \times O_{for_{16}}(n) = O(n^3)$$

The computational complexity to obtain the matrix $Y$ is $O(n^3)$.

Finally, by summing all the computational complexities calculated previously, we obtain the general computational complexity of spectral clustering:

$$O_(n^2) + O_(n^2) + O_(n^3) + O_(n^3) + O_(n^3)$$

$$2O_(n^2) + 3O_(n^3) \approx O_(n^3)$$

Thus, the computational complexity of spectral clustering is $O(n^3)$.