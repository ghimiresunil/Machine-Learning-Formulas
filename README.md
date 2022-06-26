# Machine-Learning-Formulas

1. Naive Bayes
$$ P (A | C) = \frac{P(C | A) \times P(A)}{P(C)} $$

2. Bayes Optimal Classifier
$$ arg \ max\sum p(x|T) \times P(T|D)$$

3. Naive Bayes Classifier 
$$ arg \ max P(Spo|Tot) \times \prod P(Soc|Spo) $$

4. Bayes Map (Maximum a posteriori)
$$ h_{map} = arg \ max P(c|a) \times P(a) $$

5. Maximum Likelihood
$$ h_{ML}  = arg \ max P(c|a) $$

6. Total probability
$$ Total P(B) = P(B|A) \times P(A) $$

7. Mixture Models
$$ P(B) = P(B|A) \times P(A)$$

8. Mixture of Guassians Anomaly Detection
$$ P(x|\bar{x}) = \frac{1}{\sqrt{2\pi\\sigma^2}} \times exp [-\frac{1}{2}(\frac{x - \bar{x}}{\sigma})^2]$$
$$ Z_{cs} = \frac{N_{A}C_{B} + N_{B}C_{A}}{N_{A} + C_{B}}$$
$$ P(Z_{cs}) \rightarrow  0.50$$

9. EM Algorithm
$$ E \ step \ P(\bar{x}|x) = \frac{P(\bar{x}) \times P(x|\bar{x})}{\sum P(x) \times P(\bar{x})} $$
$$ M \ step \ P(x^{\prime}) = \frac{P(\bar{x}|x)}{n}$$
$$ E \ step  \ P(\bar{x}|x) = Assign \ Value $$
$$ M \ step  \ P(x^{\prime}) = P(B = 1 | A = 1 , C = 0 )$$

10. Laplace Estimate (Small Samples)
$$ P(A) = \frac{A \ + \ 0.5}{A \ + B \ + \ 1 }$$

11. Bayesian Networks
$$ tuples \ \neg for \ y \ = \ 0 \ \land \ y \ = \ 1$$

12. Limits 
$$ \lim_{h \to 0} \frac{f(x + h) - f(x)}{h} $$
$$ h = \Delta{x} \ = \ x^{\prime} \ - \ x  $$

13. Derivatives
$$  \frac{d}{dx}{x}^n = n.x^{n-1} $$
$$ \frac{d}{dx}{y}^n = \frac{d{y}^n}{dy}.\frac{dy}{dx} $$

14. Product Rule
$$ \frac{d}{dx}f(x).g(x) = f^{\prime}(x).g(x) + f(x).g^{\prime}(x)$$
$$ \frac{d}{dx}\frac{f(x)}{g(x)} = \frac{ f^{\prime}(x).g(x) + f(x).g^{\prime}(x)}{g(x)^2}$$
$$ \frac{d}{dx}2f(x) = 2\frac{d}{dx}f(x) $$
$$ \frac{d}{dx}f(x)+g(x) = \frac{d}{dx}f(x) + \frac{d}{dx}g(x) $$
$$ \frac{d}{dx}f(x)+2g(x) = \frac{d}{dx}f(x) + 2\frac{d}{dx}g(x) $$

15. Chain Rule
$$ \frac{d}{dx}g(f(x)) = g^{\prime}(f(x)).f^{\prime}(x)$$

16. Variance
$$ var = \frac{\sum(x-\bar{x})^2}{n-1}$$

17. Standard Deviation
$$ \sigma = \sqrt{variance}$$

18. Covariance
$$ Cov = \frac{(x-\bar{x}).(y-\bar{y})}{n-1} $$

19. Confidence Interval
$$ x \ \textpm \ 1.96\frac{\sigma}{\sqrt{n}}$$

20. Chi Squared
$$ Chi = \frac{(\hat{y} - y)^2}{\sqrt{y}} = \frac{\delta^2}{\sqrt{y}} $$

21. R Squared
$$ R^2 = \frac{n\sum{xy} - \sum{x}.\sum{y}}{\sqrt{(n\sum{x}^2 - (\sum{x})^2).(n\sum{y}^2 - (\sum{y})^2)}}$$

22. Loss
$$ Loss = {Bais}^2 + {Variance}^2 + Noise$$

23. Sum of Squared Errors
$$ E|\overrightarrow{w}| = \frac{\sum{(\hat{y}-y)^2}}{2}$$

24. Cost Function
$$ J(\theta_j) = \theta_j - \eta.\frac{\sum{(\hat{y}-y)^2}}{2} $$

25. Number of examples
$$ m \geq \frac{log(N_H)+log(\frac{1}{\delta})}{\in} $$
where,
$$ \in = \frac{\hat{y}}{y}$$ and $$ \delta = y - \hat{y}$$
