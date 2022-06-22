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
