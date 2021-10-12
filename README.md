# Latar Belakang

A manager at the bank is disturbed with more and more customers leaving their credit card services. They would really appreciate if one could predict for them who is gonna get churned so they can proactively go to the customer to provide them better services and turn customers' decisions in the opposite direction

I got this dataset from a website with the URL as https://leaps.analyttica.com/home. I have been using this for a while to get datasets and accordingly work on them to produce fruitful results. The site explains how to solve a particular business problem.

Now, this dataset consists of 10,000 customers mentioning their age, salary, marital_status, credit card limit, credit card category, etc. There are nearly 18 features.

We have only 16.07% of customers who have churned. Thus, it's a bit difficult to train our model to predict churning customers.


# Metodologi

Untuk mengatasi jumlah data yang tidak seimbang, sehingga proyek ini membandingkan metode oversampling dan undersampling. Agar pengukuran performa tetap fair, proyek ini menggunakan kurva ROC untuk mengukur performa model yang datasetnya seimbang. Kurva ROC yang mendekati 1 artinya model yang dibangun memiliki performa yang bagus dengan nilai cutoff yang optimal dan terhindar dari high variance/overfitting

# Hasil

Oversampling menghasilkan kurva ROC yang lebih baik yaitu 0.94 dan memiliki akurasi sebesar 92% pada neural network. Sehingga hasil ini dinilai dapat membedakan mana nasabah yang berpindah layanan bank/menggunakan dua atau lebih layanan bank, mana nasabah yang tetap menggunakan layanan bank
