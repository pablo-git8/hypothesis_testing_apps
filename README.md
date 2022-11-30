# Hypothesis Testing (Permutation Test): Apps Project #

<p align="center">
	<img src="https://specifications-pro.com/wp-content/uploads/2019/12/%D9%85%D8%AA%D8%AC%D8%B1.jpg" alt="400" width="600"/>
</p>

In this notebook, I will show an example of hypothesis testing to determine if Apple Store receives better reviews than Google Play and if those reviews are statistically significant by using a Permutation Statistical Test.

I will use the data downloaded from here to analyze reviews made by users in different apps available in Google Play and Apple Store. I will use a basic Data Science Pipeline that will include:

- [x] Data intake (sourcing and loading)
- [x] Data processing and cleaning (ETL)
- [x] Statistical Modeling
- [x] Evaluation and Conclusion

## Results ##

The user's review means of 4.049697 and 4.191757 (Apple and Google respectively) don't **seem** all that different! Perhaps, with this result we can assume that: there's no significant difference between Google Play app reviews and Apple Store app reviews. We have an ***observed difference*** here: which is simply (4.191757 - 4.049697) = 0.14206. This is just the actual difference that we observed between the mean rating for apps from Google Play, and the mean rating for apps from the Apple Store. However, **is this difference statistically significant?**

Dive into this notebook to find out!

![python](http://ForTheBadge.com/images/badges/made-with-python.svg)
![jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
