<img src="https://raw.githubusercontent.com/ElizaLo/NLP-Natural-Language-Processing/master/img/Corpus.png" width="1050" height="150"/>

**Types of data:**

- Synthetic data

# 🔹 Synthetic data

Synthetic data is information that's artificially generated rather than produced by real-world events. Typically created using algorithms, synthetic data can be deployed to validate mathematical models and to train machine learning models. Data generated by a computer simulation can be seen as synthetic data.

While data augmentation can be a powerful tool for improving the performance and robustness of NLP models, there are also some potential downsides to using synthetic data, including:

1. **Quality concerns:** The quality of the synthetic data generated through data augmentation can be variable, depending on the specific techniques used and the characteristics of the original data set. Poor quality synthetic data can introduce noise and inaccuracies into NLP models.
2. **Overfitting to synthetic data:** If the synthetic data generated through data augmentation is too similar to the original data, NLP models can overfit to the synthetic data and perform poorly on new, unseen data.
3. **Lack of diversity:** Some data augmentation techniques may generate synthetic data that is not diverse enough, resulting in models that are biased or that perform poorly on certain types of data.
4. **Increased computational requirements:** Generating synthetic data can be computationally intensive, particularly when dealing with large data sets, which can increase the time and resources required to train NLP models.
5. **Ethical concerns:** There may be ethical concerns associated with generating synthetic data, particularly if the data is used to train models for applications such as surveillance, predictive policing, or other potentially sensitive areas.
6. **Reduced interpretability:** Synthetic data may be more difficult to interpret than real-world data, which can make it harder to understand how NLP models are making predictions.
7. **Domain Dependence:** Data augmentation techniques may not generalize well across different domains or applications, requiring additional domain-specific augmentation techniques.
8. **Lack of real-world accuracy:** Synthetic data is not always an accurate representation of the real-world data, which can lead to overfitting and poor performance of machine learning models when deployed in the real world.
9. **Bias:** Synthetic data may inherit biases from the data used to generate it, which can lead to biased machine learning models.
10. **Limited application:** Synthetic data is not suitable for all applications, especially in cases where the data being modeled has complex and unpredictable real-world variations.
11. **Validation:** The validation of synthetic data can be challenging because there is no ground truth to compare it to. In other words, it may be difficult to assess the quality of synthetic data, as there is no real-world data to compare it to. This can lead to uncertainty about the effectiveness of the synthetic data for training machine learning models. Furthermore, synthetic data may not capture the complexity of real-world data, leading to over-optimistic results when tested on synthetic data, but poor performance when deployed in the real world. Therefore, it is important to validate synthetic data carefully, using techniques such as cross-validation or testing on real-world data when available, to ensure that the synthetic data accurately represents the real-world data and can be used effectively for training machine learning models.

## 📄 Papers

| Title | Description, Information |
| :---:         |          :--- |
|[Benchmarking Unsupervised Outlier Detection with Realistic Synthetic Data](https://arxiv.org/pdf/2004.06947.pdf)|Benchmarking unsupervised outlier detection is difficult. Outliers are rare, and existing benchmark data contains outliers with various and unknown characteristics. Fully synthetic data usually consists of outliers and regular instance with clear characteristics and thus allows for a more meaningful evaluation of detection methods in principle. Nonetheless, there have only been few attempts to include synthetic data in benchmarks for outlier detection. This might be due to the imprecise notion of outliers or to the difficulty to arrive at a good coverage of different domains with synthetic data. In this work we propose a generic process for the generation of data sets for such benchmarking. The core idea is to reconstruct regular instances from existing real-world benchmark data while generating outliers so that they exhibit insightful characteristics. This allows both for a good coverage of domains and for helpful interpretations of results. We also describe three instantiations of the generic process that generate outliers with specific characteristics, like local outliers. A benchmark with state-of-the-art detection methods confirms that our generic process is indeed practical.|
|[Generative Adversarial Networks for Realistic Synthesis of Hyperspectral Samples](https://arxiv.org/abs/1806.02583)|This work addresses the scarcity of annotated hyperspectral data required to train deep neural networks. Especially, we investigate generative adversarial networks and their application to the synthesis of consistent labeled spectra. By training such networks on public datasets, we show that these models are not only able to capture the underlying distribution, but also to generate genuine-looking and physically plausible spectra. Moreover, we experimentally validate that the synthetic samples can be used as an effective data augmentation strategy. We validate our approach on several public hyper-spectral datasets using a variety of deep classifiers.|

## 📰 Articles

- [Evaluating Synthetic Data using Machine Learning](https://towardsai.net/p/l/evaluating-synthetic-data-using-machine-learning)
- [The use of Synthetic Data in Financial Services](https://www.datomize.com/resources/the-use-of-synthetic-data-in-financialservices/)

---

# 🖼️ Presentations

- [NLP without a readymade labeled dataset](https://rpubs.com/vbsowmya/tmls2021), workshop @ Toronto Machine Learning Summit, 2021