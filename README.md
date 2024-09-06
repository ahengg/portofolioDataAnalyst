# Project Title (MENU UTAMA)

ini adalah brief deskripsi yang berisikan tentang penjualan e-commerce look 
<center>
<img src="https://github.com/ahengg/portofolioDataAnalyst/blob/main/123.jpeg" alt="Logo" />
</center>
 
# Table of Contents (Sub menu)
  1. Installation 
  2. Usage
  3. Insight
     
## Installation
Untuk memulai penggunaan program, install :
``` bash 
pip install pandas
pip install matplotlib
```
## Usage 
After install, teman-teman bisa langsung run all diconda environtment / google collab

``` python
import pandas
import numpy
```
## Insight
### Jumlah Customer perbulan
``` python
total_customers=df.groupby('month')['id'].nunique()
total_customers.plot(kind='line')
plt.xlabel('Bulan')
plt.ylabel('Jumlah Customer')
plt.title('Total Customer per Bulan') 
```
<img src="https://github.com/ahengg/portofolioDataAnalyst/blob/main/gambar1.png" alt="Logo" />

### Jumlah Customer perbulan
``` python
total_customers=df.groupby('month')['id'].nunique()
total_customers.plot(kind='line')
plt.xlabel('Bulan')
plt.ylabel('Jumlah Customer')
plt.title('Total Customer per Bulan')
```
<img src="https://github.com/ahengg/portofolioDataAnalyst/blob/main/gambar1.png" alt="Logo" />

## Kesimpulan 
Maka dari hasil analisa dapat disimpulkan bahwa data ini mempunyai 
1.
2.
3.
