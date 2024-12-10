---
{"dg-publish":true,"permalink":"/undergraduate-set-theory/untitled/","tags":["gardenEntry"]}
---




## Chapter 1

## Sets

## 1. Introduction to Sets

The central concept of this book, that of a set, is, at least on the surface. extremely simple. A set is any collection, group, or conglomerate. So we have the set of all students registered at the City University of New York in February 1998, the set of all even natural numbers, the set of all points in the plane $\pi$ exactly 2 inches distant from a given point $P$, the set of all pink elephants.

Sets are not objects of the real world, like tables or stars; they are created by our mind, not by our hands. A heap of potatoes is not a set of potatoes. the set of all molecules in a drop of water is not the same object as that drop of water. The human mind possesses the ability to abstract, to think of a variety of different objects as being bound together by some common property. and thus to form a set of objects having that property. The property in question may be nothing more than the ability to think of these objects (as being) together. Thus there is a set consisting of exactly the numbers $2,7,12,13,29,34$, and 11,000 , although it is hard to see what binds exactly those numbers together, besides the fact that we collected them together in our mind. Georg Cantor, a German mathematician who founded set theory in a series of papers published over the last three decades of the nineteenth century, expressed it as follows: "Unter einer Menge verstehen wir jede Zusammenfassung M von bestimmten wohlunterschiedenen Objekten in unserer Anschauung oder unseres Denkens (welche die Elemente von M genannt werden) zu einem ganzen." |A set is a collection into a whole of definite, distinct objects of our intuition or our thought. The objects are called elements (members) of the set.]

Objects from which a given set is composed are called elements or members of that set. We also say that they belong to that set.

In this book, we want to develop the theory of sets as a foundation for other mathematical disciplines. Therefore, we are not concerned with sets of people or molecules, but only with sets of mathematical objects, such as numbers, points of space, functions, or sets. Actually, the first three concepts can be defined in
set theory as sets with particular properties, and we do that in the following chapters. So the only objects with which we are concerned from now on are sets. For purposes of illustration, we talk about sets of numbers or points even before these notions are exactly defined. We do that, however, only in examples. exercises and problems, not in the main body of theory. Sets of mathematical objects are, for example:

### 1.1 Example

(a) The set of all prime divisors of 324 .
(b) The set of all numbers divisible by 0.
(c) The set of all continuous real-valued functions on the interval $[0,1]$.
(d) The set of all ellipses with major axis 5 and eccentricity 3.
(e) The set of all sets whose elements are natural numbers less than 20.

Examination of these and many other similar examples reveals that sets with which mathematicians work are relatively simple. They include the set of natural numbers and its various subsets (such as the set of all prime numbers), as well as sets of pairs, triples, and in general $n$-tuples of natural numbers. Integers and rational numbers can be defined using only such sets. Real numbers can then be defined as sets or sequences of rational numbers. Mathematical analysis deals with sets of real numbers and functions on real numbers (sets of ordered pairs of real numbers), and in some investigations, sets of functions or cven sets of sets of functions are considered. But a working mathematician rarely encounters objects more complicated than that. Perhaps it is not surprising that uncritical usage of "sets" remote from "everyday experience" may lead to contradictions.

Consider for example the "set" $R$ of all those sets which are not elements, of themselves. In other words, $R$ is a set of all sets $x$ such that $x \notin x(\in$ reads "belongs to," $\notin$ reads "does not belong to"). Let us now ask whether $R \in R$. If $R \in R$, then $R$ is not an element of itself (because no element of $R$ belongs t o itself), so $R \notin R$; a contradiction. Therefore, necessarily $R \notin R$. But then $R$ is a set which is not an element of itself, and all such sets belong to $R$. We conclude that $R \in R$; again, a contradiction.

The argument can be briefly summarized as follows: Define $R$ by: $r \in R$ if and only if $x \notin x$. Now consider $x=R$; by definition of $R, R \in R$ if and only if $R \notin R$; a contradiction.

A few comments on this argument (due to Bertrand Russell) might be helpful. First, there is nothing wrong with $R$ being a set of sets. Many sets whose elements are again sets are legitimately employed in mathematics - see Example 1.1 - and do not lead to contradictions. Second, it is easy to give examples of elements of $R$; e.g., if $x$ is the set of all natural numbers, then $x \notin x$ (the set of all natural numbers is not a natural number) and so $x \in R$. Third, it is not so easy to give examples of sets which do not belong to $R$, but this is irrelevant. The foregoing argument would result in a contradiction even if there were no sets which are elements of themselves. (A plausible candidate for a set which is an element of itself would be the "set of all sets" $V$; clearly $V \in V$. However.
the "set of all sets" leads to contradictions of its own in a more subtle way see Exercises 3.3 and 3.6.)

How can this contradiction be resolved? We assumed that we have a set $R$ defined as the set of all sets which are not elements of themselves, and derived a contradiction as an immediate consequence of the definition of $R$. This can only mean that there is no set satisfying the definition of $R$. In other words. this argument proves that there exists no set whose members would be precisely the sets which are not elements of themselves. The lesson contained in Russell's Paradox and other similar examples is that by merely defining a set we do not prove its existence (similarly as by defining a unicorn we do not prove that unicorns exist). There are properties which do not define sets; that is, it is not possible to collect all objects with those properties into one set. This observation leaves set-theorists with a task of determining the properties which do define sets. Unfortunately, no way how to do this is known, and some results in logic (especially the so-called Incompleteness Theorems discovered by Kurt Gödel) seem to indicate that a complete answer is not even possible.

Therefore, we attempt a less lofty goal. We formulate some of the relatively simple properties of sets used by mathematicians as axioms, and then take care to check that all theorems follow logically from the axioms. Since the axioms are obviously true and the theorems logically follow from them, the theorems are also true (not necessarily obviously). We end up with a body of truths about sets which includes, among other things, the basic properties of natural. rational, and real numbers, functions, orderings, etc.. but as far as is known. no contradictions. Experience has shown that practically all notious used in contemporary mathematics can be defined, and their mathematical properties derived, in this axiomatic system. In this sense, the axiomatic set theory serves as a satisfactory foundation for the other branches of mathematics.

On the other hand, we do not claim that every true fact about sets can be derived from the axioms we present. The axiomatic system is not complete in this sense, and we return to the discussion of the question of completeness in the last chapter.

## 2. Properties

In the preceding section we introduced sets as collections of objects having some property in common. The notion of property merits some analysis. Some properties commonly considered in everyday life are so vague that they can hardly be admitted in a mathematical theory. Consider. for example. the "set of all the great twentieth century American novels." Different persons' judgments as to what constitutes a great literary work differ so much that there is no generally accepted way how to decide whether a given book is or is not an element of the "set."

For an even more startling example, consider the "set of those naturai numbers which could be written down in decimal notation" (by "could" we mean that someone could actually do it with paper and pencil). Clearly. 0 can be so
written down. If number $n$ can be written down, then surely number $n+1$ can also be written down (imagine another, somewhat faster writer, or the person capable of writing $n$ working a little faster). Therefore, by the familiar principle of induction, every natural number $n$ can be written down. But that is plainly absurd; to write down say $10^{10^{16}}$ in decimal notation would require to follow 1 by $10^{10}$ zeros, which would take over 300 years of continuous work at a rate of a zero per second.

The problem is caused by the vague meaning of "could." To avoid similar difficulties, we now describe explicitly what we mean by a property. Only clear. mathematical properties are allowed; fortunately, these properties are sufficient for expression of all mathematical facts.

Our exposition in this section is informal. Readers who would like to see how this topic can be studied from a more rigorous point of view can consult some book on mathematical logic.

The basic set-theoretic property is the membership property: "... is an element of ...," which we denote by $\in$. So " $X \in Y$ " reads " $X$ is an element of $Y$ " or " $X$ is a member of $Y$ " or " $X$ belongs to $Y$."

The letters $X$ and $Y$ in these expressions are variables; they stand for (denote) unspecified, arbitrary sets. The proposition " $X \in Y$ " holds or does not hold depending on sets (denoted by) $X$ and $Y$. We sometimes say " $X \in Y$ " is a property of $X$ and $Y$. The reader is surely familiar with this informal way of speech from other branches of mathematics. For example, " $m$ is less than $n$ " is a property of $m$ and $n$. The letters $m$ and $n$ are variables denoting unspecified numbers. Some $m$ and $n$ have this property (for example, " 2 is less than 4 " is true) but others do not (for example, " 3 is less than 2 " is false).

All other set-theoretic properties can be stated in terms of membership with the help of logical means: identity, logical connectives, and quantifiers.

We often speak of one and the same set in different contexts and find it convenient to denote it by different variables. We use the identity sign " $=$ " to express that two variables denote the same set. So we write $X=Y$ if $X$ is the same set as $Y[X$ is identical with $Y$ or $X$ is equal to $Y]$.

In the next example, we list some obvious facts about identity:
2.1 Example
(a) $X=X$.
(b) If $X=Y$, then $Y=X$.
(c) If $X=Y$ and $Y=Z$, then $X=Z$.
( $X$ is identical with $X$.)
(If $X$ and $Y$ are identical, then $Y$ and $X$ are identical.)
(If $X$ is identical with $Y$ and $Y$ is identical with $Z$, then $X$ is identical with $Z$.)
(d) If $X=Y$ and $X \in Z$, then $Y \in Z$. (If $X$ and $Y$ are identical and $X$ belongs to $Z$, then $Y$ belongs to $Z$.)
(e) If $X=Y$ and $Z \in X$, then $Z \in Y$. (If $X$ and $Y$ are identical and $Z$ belongs to $X$, then $Z$ belongs to $Y$.)

Logical connectives can be used to construct more complicated properties from simpler ones. They are expressions like "not ...," "... and ...," "if .... then ...," and "... if and only if ...."

### 2.2 Example

(a) " $X \in Y$ or $Y \in X$ " is a property of $X$ and $Y$.
(b) "Not $X \in Y$ and not $Y \in X$ " or, in more idiomatic English, " $X$ is not an element of $Y$ and $Y$ is not an element of $X$ " is also a property of $X$ and $Y$.
(c) "If $X=Y$, then $X \in Z$ if and only if $Y \in Z$ " is a property of $X, Y$ and $Z$.
(d) " $X$ is not an element of $X$ " (or: "not $X \in X$ ") is a property of $X$.

We write $X \notin Y$ instead of "not $X \in Y$ " and $X \neq Y$ instead of "not $X=Y$."
Quantifiers "for all" ("for every") and "there is" ("there exists") provide additional logical means. Mathematical practice shows that all mathematical facts can be expressed in the very restricted language we just described, but that this language does not allow vague expressions like the ones at the beginning of the section.

Let us look at some examples of properties which involve quantifiers.

### 2.3 Example

(a) "There exists $Y \in X$."
(b) "For every $Y \in X$, there is $Z$ such that $Z \in X$ and $Z \in Y$."
(c) "There exists $Z$ such that $Z \in X$ and $Z \notin Y$."

Truth or falsity of (a) obviously depends on the set (denoted by the variable) $X$. For example, if $X$ is the set of all American presidents after 1789, then (a) is true; if $X$ is the set of all American presidents before 1789, (a) becomes false. [Generally, (a) is true if $X$ has some element and false if $X$ is empty.] We say that (a) is a property of $X$ or that (a) depends on the parameter $X$. Similarly, (b) is a property of $X$, and (c) is a property of $X$ and $Y$. Notice also that $Y$ is not a parameter in (a) since it does not make sense to inquire whether (a) is true for some particular set $Y$; we use the letter $Y$ in the quantifier only for convenience and could as well say, "There exists $W \in X$," or "There exists some element of $X$." Similarly, (b) is not a property of $Y$, or $Z$, and (c) is not a property of $Z$.

Although precise rules for determining parameters of a given property can easily be formulated, we rely on the reader's common sense, and limit ourselves to one last example.

### 2.4 Example

(a) " $Y \in X$."
(b) "There is $Y \in X$."
(c) "For every $X$, there is $Y \in X$."

Here (a) is a property of $X$ and $Y$; it is true for some pairs of sets $X, Y$ and false for others. (b) is a property of $X$ (but not of $Y$ ), while (c) has no parameters. (c) is, therefore, either true or false (it is, in fact, false). Properties
which have no parameters (and are, therefore, either true or false) are called statements; all mathematical theorems are (true) statements.

We sometimes wish to refer to an arbitrary, unspecified property. We use boldface capital letters to denote statements and properties and, if convenient. list some or all of their parameters in parentheses. So $\mathbf{A}(X)$ stands for any property of the parameter $X$, e.g.. (a). (b), or (c) in Example 2.3. E ( $X . Y$ ) is a property of parameters $X$ and $Y$, e.g., (c) in Example 2.3 or (a) in Example 2.4 or
(d) " $X \in Y$ or $X=Y$ or $Y \in X$."

In general, $\mathrm{P}(X, Y, \ldots, Z)$ is a property whose truth or falsity depends on parameters $X, Y, \ldots, Z$ (and possibly others).

We said repeatedly that all set-theoretic properties can be expressed in our restricted language, consisting of membership property and logical means. However, as the development proceeds and more and more complicated theorems are proved, it is practical to give names to various particular properties, i.e.. to de. fine new properties. A new symbol is then introduced (defined) to denote the property in question; we can view it as a shorthand for the explicit formulation. For example, the property of being a subset is defined by
2.5 $X \subseteq Y$ if and only if every element of $X$ is an element of $Y$.
" $X$ is a subset of $Y$ " $(X \subseteq Y)$ is a property of $X$ and $Y$. We can use it in more complicated formulations and, whenever desirable, replace $X \subseteq Y$ by its definition. For example, the explicit definition of

$$
\text { "If } X \subseteq Y \text { and } Y \subseteq Z \text {, then } X \subseteq Z . "
$$

would be
"If every element of $X$ is an element of $Y$ and every element of $Y$ is an element of $Z$, then every element of $X$ is an element of $Z$."

It is clear that mathematics witlout definitions would be possible. but exceedingly clumsy.

For another type of definition, consider the property $\mathbf{P}(X)$ :
"There exists no $Y \in X$ "
We prove in Section 3 that
(a) There exists a set $X$ such that $\mathbf{P}(X)$ (there exists a set $X$ with no elements).
(b) There exists at most one set $X$ such that $\mathbf{P}(X)$, i.e., if $\mathbf{P}(X)$ and $\mathbf{P}\left(X^{\prime}\right)$. then $X=X^{\prime}$ (if $X$ has no elements and $X^{\prime}$ has no elements, then $X$ and $X^{\prime}$ are identical).
(a) and (b) together express the fact that there is a unique set $X$ with the property $\mathbf{P}(X)$. We can then give this set a name, say $\emptyset$ (the empty set). and use it in more complicated expressions.

The full meaning of " $\emptyset \subseteq Z$ " is then "the set $X$ which has no elements is a subset of $Z$." We occasionally refer to $\emptyset$ as the constant defined by the property P.

For our last example of a definition, consider the property $\mathbf{Q}(X, Y, Z)$ of $X$, $Y$, and $Z$ :

$$
\text { "For every } U, U \in Z \text { if and only if } U \in X \text { and } U \in Y . "
$$

We see in the next section that
(a) For every $X$ and $Y$ there is $Z$ such that $\mathbf{Q}(X, Y, Z)$.
(b) For every $X$ and $Y$, if $\mathbf{Q}(X, Y, Z)$ and $\mathbf{Q}\left(X, Y, Z^{\prime}\right)$, then $Z=Z^{\prime}$. [For every $X$ and $Y$, there exists at most one $Z$ such that $\mathbf{Q}(X, Y, Z)$.]
Conditions (a) and (b) (which have to be proved whenever this type of definition is used) guarantee that for every $X$ and $Y$ there is a unique set $Z$ such that $\mathbf{Q}(X, Y, Z)$. We can then introduce a name, say $X \cap Y$, for this unique set $Z$. and call $X \cap Y$ the intersection of $X$ and $Y$. So $\mathbf{Q}(X, Y, X \cap Y)$ holds. We refer to $\cap$ as the operation defined by the property $\mathbf{Q}$.

## 3. The Axioms

We now begin to set up our axiomatic system and try to make clear the intuitive meaning of each axiom.

The first principle we adopt postulates that our "universe of discourse" is not void, i.e., that some sets exist. To be concrete. we postulate the existence of a specific set, namely the empty set.

The Axiom of Existence There exists a set which has no elements.
A set with no elements can be variously described intuitively, e.g.. as the set of all U.S. Presidents before 1789, the set of all real numbers $x$ for which $x^{2}=-1$, etc. All examples of this kind describe one and the same set, namely the empty, vacuous set. So, intuitively, there is only one empty set. But we cannot yet prove this assertion. We need another postulate to express the fact that each set is determined by its elements. Let us see another example:
$X$ is the set consisting exactly of numbers 2,3 , and 5 .
$Y$ is the set of all prime numbers greater than 1 and less than 7.
$Z$ is the set of all solutions of the equation $x^{3}-10 x^{2}+31 x-30=0$.
Here $X=Y, X=Z$, and $Y=Z$, and we have three different descriptions of one and the same set. This leads to the Axiom of Extensionality.

The Axiom of Extensionality If every element of $X$ is an element of $Y$ and every element of $Y$ is an element of $X$, then $X=Y$.

Briefly, if two sets have the same elements, then they are identical. We can now prove Lemma 3.1.
3.1 Lemma There exists only one set with no elements.

Proof. Assume that $A$ and $B$ are sets with no elements. Then every element of $A$ is an element of $B$ (since $A$ has no elements, the statement " $a \in A$ implies $a \in B$ " is an implication with a false antecedent, and thus automatically true). Similarly, every element of $B$ is an element of $A$ (since $B$ has no elements). Therefore, $A=B$, by the Axiom of Extensionality.
3.2 Definition The (unique) set with no elements is called the empty set and is denoted $\emptyset$.

Notice that the definition of the constant $\emptyset$ is justified by the Axiom of Existence and Lemma 3.1.

Intuitively, sets are collections of objects sharing some common property, so we expect to have axioms expressing this fact. But, as demonstrated by the paradoxes in Section 1, not every property describes a set; properties " $X \notin X$ " or " $X=X$ " are typical examples.

In both cases, the problem seems to be that in order to collect all objects having such a property into a set, we already have to be able to perceive all sets. 'The difficulty is avoided if we postulate the existence of a set of all objects with a given property only if there already exists some set to which they all belong.

The Axiom Schema of Comprehension Let $\mathbf{P}(x)$ be a property of $x$. For any set $A$, there is a set $B$ such that $x \in B$ if and only if $x \in A$ and $\mathbf{P}(x)$.

This is a schema of axioms, i.e., for each property $\mathbf{P}$, we have one axiom. For example, if $\mathbf{P}(x)$ is " $x=x$," the axiom says:

For any set $A$, there is a set $B$ such that $x \in B$ if and only if $x \in A$ and $x=x$. (In this case, $B=A$.)

If $\mathbf{P}(x)$ is " $x \notin x$ ", the axiom postulates:
For any set $A$, there is a set $B$ such that $x \in B$ if and only if $x \in A$ and $x \notin x$.

Although the supply of axioms is unlimited, this causes no problems, since it is easy to recognize whether a particular statement is or is not an axiom and since every proof uses only finitely many axioms.

The property $\mathbf{P}(x)$ can depend on other parameters $p, \ldots q$; the corresponding axiom then postulates that for any sets $p, \ldots q$ and any $A$, there is a set $B$ (depending on $p, \ldots, q$ and, of course, on $A$ ) consisting exactly of all those $x \in A$ for which $\mathbf{P}(x, p, \ldots, q)$.
3.3 Example If $P$ and $Q$ are sets, then there is a set $R$ such that $x \in R$ if and only if $x \in P$ and $x \in Q$.

Proof. Consider the property $\mathbf{P}(x, Q)$ of $x$ and $Q$ : " $x \in Q$." Then, by the Comprehension Schema, for every $Q$ and for every $P$ there is a set $R$ such that $x \in R$ if and only if $x \in P$ and $\mathbf{P}(x, Q)$, i.e., if and only if $x \in P$ and $x \in Q$. ( $P$ plays the role of $A, Q$ is a parameter.)
3.4 Lemma For every $A$, there is only one set $B$ such that $x \in B$ if and only if $x \in A$ and $\mathbf{P}(x)$.

Proof. If $B^{\prime}$ is another set such that $x \in B^{\prime}$ if and only if $x \in A$ and $\mathbf{P}(x)$, then $x \in B$ if and only if $x \in B^{\prime}$, so $B=B^{\prime}$, by the Axiom of Extensionality.

We are now justifed to introduce a name for the uniquely determined set $B$.

### 3.5 Definition $\{x \in A \mid \mathbf{P}(x)\}$ is the set of all $x \in A$ with the property $\mathbf{P}(x)$.

3.6 Example The set from Example 3.3 could be denoted $\{x \in P \mid x \in Q\}$.

Our axiomatic system is not yet very powerful; the only set we proved to exist is the empty set, and applications of the Comprehension Schema to the empty set produce again the empty set: $\{x \in \emptyset \mid \mathbf{P}(x)\}=\emptyset$ no matter what property $\mathbf{P}$ we take. (Prove it.) The next three principles postulate that some of the constructions frequently used in mathematics yield sets.

The Axiom of Pair For any $A$ and $B$, there is a set $C$ such that $x \in C$ if and only if $x=A$ or $x=B$.

So $A \in C$ and $B \in C$, and there are no other elements of $C$. The set $C$ is unique (prove it); therefore, we define the unordered pair of $A$ and $B$ as the set having exactly $A$ and $B$ as its elements and introduce notation $\{A, B\}$ for the unordered pair of $A$ and $B$. In particular, if $A=B$, we write $\{A\}$ instead of $\{A, A\}$.

### 3.7 Example

(a) Set $A=\emptyset$ and $B=\emptyset$; then $\{\emptyset\}=\{\emptyset, \emptyset\}$ is a set for which $\emptyset \in\{\emptyset\}$, and if $x \in\{\emptyset\}$, then $x=\emptyset$. So $\{\emptyset\}$ has a unique element $\emptyset$. Notice that $\{\emptyset\} \neq \emptyset$, since $\emptyset \in\{\emptyset\}$, but $\emptyset \notin \emptyset$.
(b) Let $A=\emptyset$ and $B=\{\emptyset\}$; then $\emptyset \in\{\emptyset,\{\emptyset\}\}$ and $\{\emptyset\} \in\{\emptyset,\{\emptyset\}\}$, and $\emptyset$ and $\{\emptyset\}$ are the only elements of $\{\emptyset,\{\emptyset\}\}$.
Note that $\emptyset \neq\{\emptyset,\{\emptyset\}\},\{\emptyset\} \neq\{\emptyset,\{\emptyset\}\}$.

The Axiom of Union For any set $S$, there exists a set $U$ such that $x \in U$ if and only if $x \in A$ for some $A \in S$.

Again, the set $U$ is unique (prove it); it is called the union of $S$ and denoted by $\bigcup S$. We say that $S$ is a system of sets or a collection of sets when we want to stress that elements of $S$ are sets (of course, this is always true - all our
objects are sets - and thus the expressions "set" and "system of sets" have the same meaning). The union of a system of sets $S$ is then a set of precisely those $x$ which belong to some set from the system $S$.

### 3.8 Example

(a) Let $S=\{0,\{0\} ; x \in \bigcup S$ if and only if $x \in A$ for some $A \in S$, i.e.. if and only if $x \in \emptyset$ or $x \in\{\emptyset\}$. Therefore, $x \in \bigcup S$ if and only if $x=\emptyset$ : $U S=\{\emptyset\}$.
(b) $\cup \emptyset=\emptyset$.
(c) Let $M$ and $N$ be sets; $x \in \bigcup\{M, N\}$ if and only if $x \in M$ or $x \in N$

The set $\bigcup\{M, N\}$ is called the union of $M$ and $N$ and is denoted $M \cup N$
So we finally introduced one of the simple set-theoretic operations with which the reader is surely familiar. The Axiom of Pair and the Axiom of Union are necessary to define union of two sets (and the Axiom of Extensionality is needed to guarantee that it is unique). The union of two sets has the usual meauing: $x \in M \cup N$ if and only if $x \in M$ or $x \in N$.
3.9 Example $\{\{0\}\} \cup\{\emptyset,\{0\}\}=\{\emptyset,\{\emptyset\}\}$.

The Axiom of Union is, of course, much more powerful; it enables us to form unions of not just two, but of any, possibly infinite, collection of sets.

If $A, B$, and $C$ are sets, we can now prove the existence and uniqueness of the set $P$ whose elements are exactly $A, B$, and $C$ (see Exercise 3.5). $P$ is denoted $\{A, B, C\}$ and is called an unordered triple of $A, B$, and $C$. Analogously, we could define an unordered quadruple or 17 -tuple.

Before introducing the last axiom of this section, we define another simple concept.
3.10 Definition $A$ is a subset of $B$ if and only if every element of $A$ belongs, to $B$. In other words, $A$ is a subset of $B$ if, for every $x, x \in A$ implies $x \in B$.

We write $A \subseteq B$ to denote that $A$ is a subset of $B$.

### 3.11 Example

(a) $\{\emptyset\} \subseteq\{\emptyset,\{\emptyset\}\}$ and $\{\{\emptyset\}\} \subseteq\{\emptyset,\{\emptyset\}\}$.
(b) $\emptyset \subseteq A$ and $A \subseteq A$ for every set $A$.
(c) $\{x \in A \mid \mathbf{P}(x)\} \subseteq A$.
(d) If $A \in S$, then $A \subseteq \bigcup S$.

The next axiom postulates that all subsets of a given set can be collected into one set.

The Axiom of Power Set For any set $S$, there exists a set $P$ such that $X \in P$ if and only if $X \subseteq S$.

Since the set $P$ is again uniquely determined, we call the set of all subsets of $S$ the power set of $S$ and denote it by $\mathcal{P}(S)$.

### 3.12 Example

(a) $\mathcal{P}(\emptyset)=\{\emptyset\}$.
(b) $\mathcal{P}(\{a\})=\{\emptyset,\{a\}\}$.
(c) The elements of $\mathcal{P}(\{a, b\})$ are $\emptyset,\{a\}$, $\{b\}$, and $\{a, b\}$.

We conclude this section with another notational convention. Let $\mathbf{P}(x)$ be a property of $x$ (and, possibly, of other parameters).

If there is a set $A$ such that, for all $x, \mathbf{P}(x)$ implies $x \in A$. then $\{x \in A \mid$ $\mathbf{P}(x)\}$ exists, and, moreover, does not depend on $A$. That means that if $A^{\prime}$ is another set such that for all $x, \mathbf{P}(x)$ implies $x \in A^{\prime}$, then $\left\{x \in A^{\prime} \mid \mathbf{P}(x)\right\}=$ $\{x \in A \mid \mathbf{P}(x)\}$. (Prove it.)

We can now define $\{x \mid \mathbf{P}(x)\}$ to be the set $\{x \in A \mid \mathbf{P}(x)\}$, where $A$ is any set for which $\mathbf{P}(x)$ implies $x \in A$ (since it does not matter which such set $A$ we use). $\{x \mid \mathbf{P}(x)\}$ is the set of all $x$ urith the property $\mathbf{P}(x)$. We stress once again that this notation can be used only after it has been proved that some $A$ contains all $x$ with the property $\mathbf{P}$.

### 3.13 Example

(a) $\{x \mid x \in P$ and $x \in Q\}$ exists.

Proof. $\quad \mathbf{P}(x, P, Q)$ is the property " $x \in P$ and $x \in Q$ "; let $A=P$. Then $\mathbf{P}(x, P, Q)$ implies $x \in A$. Therefore, $\{x \mid x \in P$ and $x \in Q\}=\{r \in P \mid$ $x \in P$ and $x \in Q\}=\{x \in P \mid x \in Q\}$ is the set $R$ from Example 3.3.
(b) $\{x \mid x=a$ or $x=b\}$ exists; for a proof put $A=\{a, b\}$; also show that $\{x \mid x=a$ or $x=b\}=\{a, b\}$.
(c) $\{x \mid x \notin x\}$ does not exist (because of Russell's Paradox); thus in this instance the notation $\{x \mid \mathbf{P}(x)\}$ is inadmissible.

Although our list of axioms is not complete, we postpone the introduction of the remaining postulates until the need for them arises. Quite a few concepts can be introduced and some theorems proved from the postulates we now have available. The reader may have noticed that we did not guarantee existence of any infinite sets. This deficiency is removed in Chapter 3. Other axioms are introduced in Chapters 6 and 8. The complete list of axioms can be found in Section 1 of Chapter 15. This axiomatic system was essentially formulated by Ernst Zermelo in 1908 and is often referred to as the Zermelo-Fraenkel axiomatic: system for set theory.

## Exercises

3.1 Show that the set of all $x$ such that $x \in A$ and $x \notin B$ exists.
3.2 Replace the Axiom of Existence by the following weaker postulate:

Weak Axiom of Existence Some set exists.
Prove the Axiom of Existence using the Weak Axiom of Existence and the Comprehension Schema. [Hint: Let $A$ be a set known to exist: consider $\{x \in A \mid x \neq x\}$.]
3.3 (a) Prove that a "set of all sets" does not exist. [Hint: if $V$ is a set of all sets, consider $\{x \in V \mid x \notin x\}$.\}
(b) Prove that for any set $A$ there is some $x \notin A$.
3.4 Let $A$ and $B$ be sets. Show that there exists a unique set $C$ such that $x \in C$ if and only if either $x \in A$ and $x \notin B$ or $x \in B$ and $x \notin A$.
3.5 (a) Given $A, B$, and $C$, there is a set $P$ such that $x \in P$ if and only if $x=A$ or $x=B$ or $x=C$.
(b) Generalize to four elements.
3.6 Show that $\mathcal{P}(X) \subseteq X$ is false for any $X$. In particular, $\mathcal{P}(X) \neq X$ for any $X$. This proves again that a "set of all sets" does not exist. [Hint: Let $Y=\{u \in X \mid u \notin u\} ; Y \in \mathcal{P}(X)$ but $Y \notin X$.
3.7 The Axiom of Pair, the Axiom of Union, and the Axiom of Power Set can be replaced by the following weaker versions.
Weak Axiom of Pair For any $A$ and $B$, there is a set $C$ such that $A \in C$ and $B \in C$.
Weak Axiom of Union For any $S$, there exists $U$ such that if $X \in A$ and $A \in S$, then $X \in U$.
Weak Axiom of Power Set For any set $S$, there exists $P$ such that $X \subseteq S$ implies $X \in P$.
Prove the Axiom of Pair, the Axiom of Union, and the Axiom of Power Set using these weaker versions. [Hint: Use also the Comprehension Schema.]

## 4. Elementary Operations on Sets

The purpose of this section is to elaborate somewhat on the notions introduced in the preceding section. In particular, we introduce simple set-theoretic operations (union, intersection, difference, etc.) and prove some of their basiproperties. The reader is certainly familiar with them to some extent and we leave out most of the details.

Definition 3.10 tells us what it means that $A$ is a subset of $B$ (included in $B), A \subseteq B$. The property $\subseteq$ is called inclusion. It is easy to prove that, for any sets $A, B$, and $C$,
(a) $A \subseteq A$.
(b) If $A \subseteq B$ and $B \subseteq A$, then $A=B$.
(c) If $A \subseteq B$ and $B \subseteq C$, then $A \subseteq C$.

For example, to verify (c) we have to prove: If $x \in A$, then $x \in C$. But if $x \in A$. then $x \in B$, since $A \subseteq B$. Now, $x \in B$ implies $x \in C$, since $B \subseteq C$. So $x \in A$ implies $x \in C$.

If $A \subseteq B$ and $A \neq B$, we say that $A$ is a proper subset of $B$ ( $A$ is property contained in $B$ ) and write $A \subset B$. We also write $B \supseteq A$ instead of $A \subseteq B$ and $B \supset A$ instead of $A \subset B$.

Most of the forthcoming set-theoretic operations have been mentioned before. The reader probably knows how they can be visualized using Venn diagrams (see Figure 1).
![](https://cdn.mathpix.com/cropped/2024_12_10_4738f1950fba6436e0abg-030.jpg?height=886&width=529&top_left_y=611&top_left_x=775)

Figure 1: Venn diagrams. (a) Intersection: The shaded part is $A \cap B$. (b) Union: The shaded part is $A \cup B$. (c) Difference: The shaded part is $A-B$. (d) Symmetric difference: The shaded part is $A \triangle B$. (e) Distributive law: The shaded part obviously represents both $A \cap(B \cup C)$ and $(A \cap B) \cup(A \cap C)$.
4.1 Definition The intersection of $A$ and $B, A \cap B$, is the set of all $x$ which belong to both $A$ and $B$. The union of $A$ and $B, A \cup B$, is the set of all $x$ which belong in either $A$ or $B$ (or both). The difference of $A$ and $B, A-B$, is the set of all $x \in A$ which do not belong to $B$. The symmetric difference of $A$ and $B$, $A \triangle B$, is defined by $A \triangle B=(A-B) \cup(B-A)$. (See Examples 3.3 and 3.8 and Exercises 3.1 and 3.4 for proofs of existence and uniqueness.)

As an exercise, the reader can work out proofs of some simple properties of these operations.

$$
\begin{aligned}
& \text { Commutativity } \quad A \cap B=B \cap A \\
& A \cup B=B \cup A \\
& \text { Associativity } \quad(A \cap B) \cap C=A \cap(B \cap C) \\
& (A \cup B) \cup C=A \cup(B \cup C)
\end{aligned}
$$

So forgetting the parentheses we can write simply $A \cap B \cap C$ for the intersection
of sets $A, B$, and $C$. Similarly, we do not need parentheses for the union and for more than three sets.

$$
\begin{array}{ll}
\text { Distributivity } & A \cap(B \cup C)=(A \cap B) \cup(A \cap C) \\
& A \cup(B \cap C)=(A \cup B) \cap(A \cup C) \\
& \\
\text { DeMorganLaws } & C-(A \cap B)=(C-A) \cup(C-B) \\
& C-(A \cup B)=(C-A) \cap(C-B)
\end{array}
$$

Some of the properties of the difference and the symmetric difference are

$$
\begin{aligned}
& A \cap(B-C)=(A \cap B)-C \\
& A-B=\emptyset \text { if and only if } A \subseteq B \\
& A \triangle A=\emptyset \\
& A \triangle B=B \triangle A \\
& (A \triangle B) \triangle C=A \triangle(B \triangle C)
\end{aligned}
$$

Drawing Venn diagrams often helps one discover and prove these and similar relationships. For example, Figure 1 (e) illustrates the distributive law $A \cap(B)$ $C)=(A \cap B) \cup(A \cap C)$. The rigorous proof proceeds as follows: We have to prove that the sets $A \cap(B \cup C)$ and $(A \cap B) \cup(A \cap C)$ have the same elements. That requires us to show two facts:
(a) Every element of $A \cap(B \cup C)$ belongs to $(A \cap B) \cup(A \cap C)$.
(b) Every element of $(A \cap B) \cup(A \cap C)$ belongs to $A \cap(B \cup C)$.

To prove (a), let $a \in A \cap(B \cup C)$. Then $a \in A$ and also $a \in B \cup C$. Therefore, either $a \in B$ or $a \in C$. So $a \in A$ and $a \in B$ or $a \in A$ and $a \in C$. This means that $a \in A \cap B$ or $a \in A \cap C$; hence, finally, $a \in(A \cap B) \cup(A \cap C)$.

To prove (b), let $a \in(A \cap B) \cup(A \cap C)$. Then $a \in A \cap B$ or $a \in A \cap C$. In the first case, $a \in A$ and $a \in B$, so $a \in A$ and $a \in B \cup C$. and $a \in A \cap\left(B \cup C^{\circ}\right)$. In the second case, $a \in A$ and $a \in C$, so again $a \in A$ and $a \in B \cup C$. and finally. $a \in A \cap(B \cup C)$.

The exercises should provide sufficient material for practicing similar olementary arguments about sets.

The union of a system of sets $S$ was defined in the preceding section. We now define the intersection $\bigcap S$ of a nonempty system of sets $S: x \in \bigcap S$ if and only if $x \in A$ for all $A \in S$. Then intersection of two sets is again a special case of the more general operation: $A \cap B=\bigcap\{A, B\}$. Notice that we do not define $\cap \emptyset$; the reason is that cvery $x$ belongs to all $A \in \emptyset$ (since there is un such $A$ ), so $\cap \emptyset$ would have to be a set of all sets. We postpone more detailed investigation of general unions and intersections until Chapter 2, where a more wieldy notation becomes available.

Finally, we say that sets $A$ and $B$ are disjoint if $A \cap B=\emptyset$. More generally. $S$ is a system of mutually disjoint sets if $A \cap B=\emptyset$ for all $A, B \in S$ such that $A \neq B$.

## Exercises

4.1 Prove all the displayed formulas in this section and visualize them using Venn diagrams.
4.2 Prove:
(a) $A \subseteq B$ if and only if $A \cap B=A$ if and only if $A \cup B=B$ if and only if $A-B=\emptyset$.
(b) $A \subseteq B \cap C$ if and only if $A \subseteq B$ and $A \subseteq C$.
(c) $B \cup C \subseteq A$ if and only if $B \subseteq A$ and $C \subseteq A$.
(d) $A-B=(A \cup B)-B=A-(A \cap B)$.
(e) $A \cap B=A-(A-B)$.
(f) $A-(B-C)=(A-B) \cup(A \cap C)$.
(g) $A=B$ if and only if $A \triangle B=\emptyset$.
4.3 For each of the following (false) statements draw a Venn diagram in which it fails:
(a) $A-B=B-A$.
(b) $A \cap B \subset A$.
(c) $A \subseteq B \cup C$ implies $A \subseteq B$ or $A \subseteq C$.
(d) $B \cap C \subseteq A$ implies $B \subseteq A$ or $C \subseteq A$.
4.4 Let $A$ be a set; show that a "complement" of $A$ does not exist. (The "complement" of $A$ is the set of all $x \notin A$.)
4.5 Let $S \neq \emptyset$ and $A$ be sets.
(a) Set $T_{1}=\{Y \in \mathcal{P}(A) \mid Y=A \cap X$ for some $X \in S\}$, and prove $A \cap \bigcup S=\bigcup T_{1}$ (generalized distributive law).
(b) Set $T_{2}=\{Y \in \mathcal{P}(A) \mid Y=A-X$ for some $X \in S\}$, and prove

$$
\begin{aligned}
& A-\bigcup S=\bigcap_{T} \\
& A-\bigcap S=\bigcup^{T}
\end{aligned}
$$

(generalized De Morgan laws).
4.6 Prove that $\cap S$ exists for all $S \neq \emptyset$. Where is the assumption $S \neq \emptyset$ used in the proof?