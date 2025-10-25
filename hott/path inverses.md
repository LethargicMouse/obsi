For $A: \cal U$,  $x, y: A$ and $p : x = y$ we have the following:
$$
\begin{align}
p^{-1} \cdot p &= \text{refl}_y \\
p \cdot p^{-1} &= \text{refl}_x
\end{align}
$$
*Proof.* We will prove the first one. By [[path induction|induction]] on $p$ we need
$$
\prod_{x: A} \text{refl}_x^{-1} \cdot \text{refl}_x = \text{refl}_x
$$
That is $\text{refl}_{\text{refl}_x}$ by the conversion rules of [[path composition]] and [[path inversion]].
