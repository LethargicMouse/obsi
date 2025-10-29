For $A: \cal U$,  $a, b, c, d: A$,  $p: a = b$,  $q: b = c$,  $r: c = d$ we have the following:
$$
(p \cdot q) \cdot r = p \cdot (q \cdot r)
$$
*Proof.* By [[path induction]] on $p, q, r$ we need
$$
\prod_{x: A} (\text{refl}_x \cdot \text{refl}_x) \cdot \text{refl}_x = \text{refl}_x \cdot (\text{refl}_x \cdot \text{refl}_x) 
$$
That is $\text{refl}_{\text{refl}_x}$ by conversion rule of [[path composition]].
