Don't fear the Monad

- functions
- monoids
- functions
- monad

---

`int x;`

`x E ints`

`f : int --> int`

---

**Generic Type**

`x : a` (`x` is the type of `a`, `a` is any type)

`f : a —-> a` (`f` is the type of `a` that returns a type of `a`)

`g : a --> a` (`g` is the type of `a` that returns a type of `a`)

**Combining f and g**

`f(g(a))` or `g(f(a))`

**Without brackets**

`f(g a)` or `(f • g) a = f(g a)` or `(f • g) = h : a --> a`

**Monoid**: Have a way to get two things of the same type and creating another thing of the same type

---

Functional Composition is associative

`(f • g) • h = f • (g •  h) = f(g(h(a)))`

---

**Monad**

Bring the world of side effects under control: compositionality - the way to control complexity
