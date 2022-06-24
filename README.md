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
