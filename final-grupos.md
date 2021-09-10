# Final de teoría de grupos.

## Transfer.

La idea es a partir de un subgrupo de Sylow $Q$ de un grupo $G$ construirnos un complemento normal $K$. La idea es que queremos conseguirnos un morfismo de grupos tal que tenga como núcleo a este tal $K$. A estos morfismos los vamos a llamar el <u>transfer</u> de $K$.

Formalmente la definición es la siguiente. Sea $Q$ un subgrupo de índice finito  $n$ en un grupo $G$ luego el transfer es la siguiente función $V:G \to Q/Q'$, definida como 
$$
V(g)=\prod_{i=1}^{n} x_i Q'
$$
$\{ l_1, \dots, l_n \}$ es un transversal a izquierda de $Q$ en $G$ tal que $gl_i=l_jx_i.$ 

Moralmente que caiga en el cociente por el conmutador nos permite trabajar en un grupo abeliano para poder ver que esto es un morfismo y que aparte vale que no depende los transversales que elijamos.

## El segundo grupo de cohomología.

Dado un subgrupo $K \le G$ un <u>transversal</u> es dar un representante de cada clase de cosets de $K$ en $G$. En particular tengamos en mente el siguiente caso:

* Si $G$ es un producto semidirecto y $Q$ es un complemento de $K$ luego $Q$ es un transversal de $K$ en $G$.

## Transgresiones.

## Teorema de Schur.

> Todo grupo finito $Q$ tiene un cubrimiento $U$ que es una extensión central de $M(Q)$ por medio de $Q$.

## Extensiones centrales.

Recordemos primero que es un extensión de un grupo $K$ por $Q$. Si $G$ es una extensión tal luego tiene que encajar en la siguiente sucesión exacta corta,
$$
1 \to K \to G \to Q \to 1
$$
por lo tanto los productos semidirectos resultan ser un caso especial de estas extensiones. 

Una extensión central de un grupo $K$ por $Q$ es una extensión $G$ de $K$ por $Q$ tal que $K \le Z(G)$. 

Esto es que $G=K \rtimes Q$ y en particular si estamos diciendo que tiene que ser central se puede verificar que $G= K \times Q$.

## Multiplicador de Schur.

Si $Q$ es un grupo su multiplicador de Schur es el siguiente grupo abeliano $H^2(Q,\C^*)$. En particular está bueno saber que dado un grupo finito $Q$ su multiplicador de Schur es un grupo abeliano tal que $\exp(M(Q))$ divide a $|Q|$. 

* *Demo.*

Lo interesante es el corolario que vamos a usar más en adelante que un $p$ grupo  finito tiene multiplicador de Schur un p grupo finito abeliano.

### Representaciones proyectivas.

Para entender un poco de donde sale todo esta historia tenemos que partir de un problema en principio diferente. Dado un grupo $Q$ una <u>representación proyectiva</u> es un morfismo de grupos $\rho:Q \to PGL_n(\C)$, donde caen en el espacio de automorfismos del espacio proyectivo. 

## Cubrimientos.

## Demostración del teorema.





