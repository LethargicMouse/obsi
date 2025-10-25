An induction principle for paths.
If for *all* points $a, b: A$ and paths $p: a = b$ there is a type $C(a, b, p) : \cal U$, if for *any* $x : A$ there is $c(x) : C(x, x, \text{refl}_x)$, then there is also $f(a, b, p) : C(a, b, p)$ such that $f(x, x, \text{refl}_x) \equiv c(x)$ for all $x: A$.

 Given $A : \cal U$, a fibration
$$
C : \prod_{a, b: A} a = b \to \cal U
$$
and a function
$$
c : \prod_{x: A} C(x, x, \text{refl}_x)
$$
there is a function
$$
f : \prod_{a, b : A} \prod_{p : a = b} C(a, b, p)
$$
such that for each $x: A$
$$
f(x, x, \text{refl}_x) \equiv c(x)
$$

$$
\text{ind}_= : \prod_{A: \cal U} \prod_{C : \prod_{a, b: A} a = b \to \cal U} (\prod_{x: A} C(x, x, \text{refl}_x)) \to \prod_{a, b : A} \prod_{p: a = b} C(a, b, p)
$$
