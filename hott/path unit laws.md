For $A : \cal U$,  $a, b: A$ and $p: a = b$ we have the following:
$$
\begin{align}
p \cdot \text{refl}_b &= p \\
\text{refl}_a \cdot p &= p
\end{align}
$$
*Proof.* Let's provide the first path. By [[path induction|induction]] on $p$ we need
$$
\prod_{x: A} \text{refl}_x \cdot \text{refl}_x = \text{refl}_x
$$
That is $\text{refl}_{\text{refl}_x}$ by the conversion rule of [[path composition]]. The second path is provided similarly.
