# Sets

a set is a collection of (unique) mathematical objects, in no particular order.

A set can be defined by **enumeration**:
$$
    S = \{1,2,3\}
$$

Or **set builder notation**:
$$
    S = \{m \in \mathbb{C}; m = a + bi; a, b \in \mathbb{Q}\}
$$

There is an empty set (ZFS):
$$ 
    empty = \empty = \{\}
$$

A **subset** of a set (the **superset**) is a set whose all elements are contained in another:
$$
    \N \sube \Z
$$

That is:
$$
    A \sube B \\
    \forall e \in A: e \in B
$$

A strict subset of a set is one, where the superset contains at least one more element
than the subset:
$$
    A \sub B \\
    \forall e \in A: e \in B \\
    \exists a \in B: a \not \in A 
$$

The **intersection** of two sets is the set of common elements: 
$$
    I=A \cap B \\
    I = \{a \in A: a \in B\}
$$

We use sets to reason about many values at once.