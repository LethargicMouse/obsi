For $A: \cal U$ and $x, y: A$ there is a function
$$
p \mapsto p^{-1} : (x = y) \to (y = x)
$$
such that $\text{refl}_x^{-1} \equiv \text{refl}_x$ for each $x: A$.

*Proof.* By [[path induction|induction]] on $p$ we need
$$
\prod_{a: A} (a = a)
$$
We define it as $\text{refl}_a$. By [[path induction|conversion rule]] then we have
$$
\text{refl}_a^{-1} \equiv \text{refl}_a
$$
