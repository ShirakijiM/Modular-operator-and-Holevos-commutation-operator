## Representation on \(\mathfrak{H}\otimes\mathfrak{H}\)
We can identify the Hilbert-Schmidt space \(\mathfrak{H}_2=\mathfrak{N}=M_n(\mathbb{C})\) on \(\mathfrak{H}=\mathbb{C}^n\) with \(\mathfrak{H}\otimes\mathfrak{H}\)
by a unitary operator satisfying 
$$
v(e_je_k^T)=e_j\otimes e_k
$$
where \(e_j=(\delta_{j1},\delta_{j,2},...,\delta_{j,n})^T\) with the Kronecker delta \(\delta_{j,l}\). 
For \(\psi=\sum_j \lambda_j e_j\) and \(\phi=\sum_k \mu_k e_k\)
we have
$$
\begin{split}
v(\psi\phi^\ast)&=\sum_{j,k}\lambda_j\bar{\mu}_k v(e_je_k^T)\\
&=\sum_{j,k}\lambda_j\bar{\mu}_k e_j\otimes e_k={\psi}\otimes \overline{\phi}.
\end{split}
$$
 </p>

 <p>
For \(A\in \mathfrak{N}\), \(\ell(A)\) is represented as \(\tilde{\ell}(A)=A\otimes I_n\) on \(\mathbb{C}^n\otimes \mathbb{C}^n\).
In fact
 $$
 \begin{split}
 v(\ell(A)e_je_k^T)&=v(Ae_je_k^T)=Ae_j\otimes e_k\\
 &= (A\otimes I_n)e_k\otimes  e_j=\tilde{\ell}(A)v(e_je_k^T),
 \end{split} 
 $$
 and hence \(\ell(A)=v^{\ast}\tilde{\ell}(A)v\). 
On the other hand, \(r(A):\mathfrak{N}\in X \to XA\ni\mathfrak{N}\) is 
represented as \(\tilde{r}(A)=I_n\otimes A^T\) on \(\mathbb{C}^n\otimes \mathbb{C}^n\).
In fact
 $$
 \begin{split}
 v(r(A)e_je_k^T)&=v(e_je_k^TA)=v(e_j(A^\ast e_k)^\ast)=e_j\otimes \overline{A^\ast e_k}\\
 &= e_j \otimes A^T e_k= (I_n\otimes A^T)e_j\otimes  e_k=\tilde{r}(A)v(e_je_k^T),
 \end{split} 
 $$
 and hence \(r(A)=v^{\ast}\tilde{r}(A) v\). 
</p>
</section>

