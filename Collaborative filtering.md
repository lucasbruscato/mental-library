It's a machine learning technique for building recommender systems, it relies on user ratings (or interactions interpreted as ratings) of items.

The end result of this methodology is to make a prediction of what would the user's rating be for a specific item.

The mathematical terms for this model are (using movies and users as an example):

![[Collaborative filtering mathematical terms.png]]

The formula to predict a rating is:

$$
w^{(j)}*x^{(i)} + b^{(j)}
$$

The [[cost function]] to learn the parameters of the algorithm is:

![[Collaborative filtering cost function.png]]

To learn the parameters we should apply the [[Gradient Descent]] and each partial derivative should be over each parameter to be learnt (w, b and x), thus repeating this until convergence:

$$
w^{(j)}_i = w^{(j)}_i - \alpha \frac{\partial}{\partial w^{(j)}_i} J(w, b, x)
$$
$$
b^{(j)} = b^{(j)} - \alpha \frac{\partial}{\partial b^{(j)}} J(w, b, x)
$$
$$
x^{(j)}_k = x^{(j)}_k - \alpha \frac{\partial}{\partial x^{(j)}_k} J(w, b, x)
$$

