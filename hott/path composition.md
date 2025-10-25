For $A: \cal{U}$ and $x, y, z : A$ there is a function
$$
p, q \mapsto p \cdot q : (x = y) \to (y = z) \to (x = z) 
$$
such that $\text{refl}_x \cdot \text{refl}_x \equiv \text{refl}_x$ for each $x: A$.

*Proof.* by [[path induction|induction]] on $p$ we need
$$
\prod_{a: A} (a = z) \to (a = z)
$$
Now we can use $\text{id}$, but we want the [[path induction|conversion rule]] to be symmetric, so we will use induction on $q$ so that we need
$$
\prod_{a: A} (a = a)
$$
Now we use $\text{refl}_a$. A conversion rule then gives us
$$
\text{refl}_a \cdot \text{refl}_a \equiv \text{refl}_a
$$
