what are they? what are the differences? when will you choose the L1 and when L2? what do you expect after that?

L1 is absolute sum of weights while L2 is square sum of weights.
They are both used to prevent overfitting, by 'punishing' coefficient fit perfectly. And L2 punishes large values (much) more than L1. L1 can yield sparse models while L2 can't. In other words, L1 tends to generate/cause many coefficient with zero or very small value (because they are not 'important') while L2 does not. And this property cause L1 has build-in feature selection while L2 does not. L1 is not smooth while L2 is. L1 is like Laplace while L2 is like gaussian. 

In practice, we use L2 over L1.
