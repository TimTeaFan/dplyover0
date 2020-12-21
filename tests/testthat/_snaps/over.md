# over() gives meaningful messages

    `over()` must only be used inside dplyr verbs

---

    Problem with `summarise()` input `..1`.
    x Problem with `over()` input `.fns`.
    i Input `.fns` must be a function, a formula, or a list of functions/formulas.
    i Input `..1` is `over(1, 42)`.

---

    Problem with `mutate()` input `..1`.
    x Problem with `over()` inside `mutate()`.
    i `over`() is not supported in `mutate()` calls which set the `.keep` argument to "used" or "unused".
    x `over`() was called inside `mutate(..., .keep = "used").
    i Either drop the `.keep` argument or set it to "all" (default) or "none".
    i Input `..1` is `over(1, mean)`.

---

    Problem with `mutate()` input `..1`.
    x Problem with `over()` inside `mutate()`.
    i `over`() is not supported in `mutate()` calls which set the `.keep` argument to "used" or "unused".
    x `over`() was called inside `mutate(..., .keep = "unused").
    i Either drop the `.keep` argument or set it to "all" (default) or "none".
    i Input `..1` is `over(1, mean)`.

---

    Problem with `mutate()` input `..1`.
    x Problem with `over()`.
    i Output must not contain existing column names.
    x `over()` tried to create the following existing column names: 'Sepal.Length'.
    i If you want to transform existing columns try using `across()`.
    i If you want to change the output names use the `.names` argument.
    i Input `..1` is `over("Sepal.Length", paste)`.

---

    Problem with `summarise()` input `..1`.
    x Problem with `over()`  input `.names`.
    i When more than one element is provided to `.names` its length must equal the number of new columns.
    x 3 elements provided to `.names`, but the number of new columns is 6.
    i Input `..1` is `over(...)`.
    i The error occured in group 1: x = 1.

---

    Problem with `summarise()` input `..1`.
    x Problem with `over()`  input `.names`.
    i When more than one element is provided to `.names` its length must equal the number of new columns.
    x 7 elements provided to `.names`, but the number of new columns is 6.
    i Input `..1` is `over(...)`.
    i The error occured in group 1: x = 1.

---

    Problem with `summarise()` input `..1`.
    x Problem with `over()` input `.names`.
    i When more than one element is provided to `.names` all elements must be unique.
    x The following names are not unique: 'one', 'two', 'three'.
    i Input `..1` is `over(...)`.
    i The error occured in group 1: x = 1.
