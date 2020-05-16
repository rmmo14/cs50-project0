# C1

## Real Line

### Types of Numbers
The number line consists of all real numbers ($\mathbf{R}$), which can be broken down into four groups. 

1. Natural Numbers ($\mathbf{N}$): aka the counting numbers are $1, 2, 3, 4, .....,\infty$
1. Integers($\mathbf{Z}$): includes the natural's ($\mathbf{N}$), their negative counterparts, and zero: $-\infty,...,-2, -1, 0, 1, 2, ...,\infty$
1. Rationals ($\mathbf{Q}$): are numbers that can be expressed as a quotient of two integers, where the denominator is not equal to zero, in other words: $\frac{p}{q}$ where $p,q\in\mathbf{Z}$ and $q\neq 0$. Rationals emcompass the integers ($\mathbf{Z}$) and thus the naturals ($\mathbf{N}$) as well. ex: $\frac{1}{2}, -35, \frac{17}{30}, 2.75,$ etc. are $\mathbf{Q}$'s.
1. Irrationals: these are numbers that cannot be expressed as a rational. Examples can be like non-repeating decimals (like $\pi$ or $e$) or square roots of non-perfect squares (like $\sqrt{2}, \sqrt{15},$ etc.)

### Arithmetic Laws
With the above group of numbers we have the following laws: (assume $a,b,c\in\mathbf{R}$)

**Commutativity**

* *of addition*: you can add numbers in any order $a+b=b+a$

* *of multiplication*: you can multiply numbers in any order $ab=ba$

**Associativity**

* *of addition*: grouping doesn't matter in addition $(a+b)+c=a+(b+c)$

* *of multiplication*: grouping doesn't matter in multiplication $(ab)c=a(bc)$

## Algebra with Real Numbers

#### Recall PEMDAS
Always respect the order of operations, following the acronym as **Parenthesis, Exponent, Multiplication or Division, Add or Subtract**. Notice MD and AS have an "or", this is because you must do whichever one comes first from left to right. 
For example:

$$9\div 3(2)-4+3$$

If done *incorrectly* you might do something like 

$$9\div 3(2)-4+3$$
$$9\div 6-1$$
$$1.5-1$$
$$0.5$$

But when following order from left to right you get the *correct* answer of (by first dividing 9 by 3): 

$$9\div 3(2)-4+3$$ 
$$3(2)-4+3$$  
$$6-4+3$$
$$2+3$$
$$5$$

### Recall: Distributive Property

The distributive property, or in other words, backwards factoring.

$$a(b+c)=ab+ac$$

I say *backwards factoring* because if written backwards:

$$ab+ac=a(b+c)$$

You are factoring the term they have in common, in this case the term "a".

The distributive property comes in handy for expanding products of sums, this method is sometimes referred to as **FOIL** with binomials. 

$$(a+b)(x+y)=ax+ay+bx+by$$

Where you multiply the **F**irst terms together ($a \cdot x$), multiply **O**uter terms ($a\cdot y$), multiply **I**nner terms ($b\cdot x$), multiply the **L**ast terms ($b\cdot y$), and ADD all of those together.  

#### Alternative method of Distributive Property

A current method used to expand binomials is by using area models or grids. 

<!-- Insert image of punnet square -->

### Recall: Arithmetic with Fractions

From here and onward you must get comfortable with fractions, being able to do the arithmetic mentally if possible by the time you are in calculus 1. You must be comfortable working with variables as well. 

#### Add/Subtract Fractions
To add (or subtract) fractions you must get the **Least Common Denominator (LCD)** of all the fractions being added. This means we must find the *least common multiple* of the denominators. 

$$\frac{a}{b} + \frac{x}{y}$$

In this case, we must find the least common multiple of $b$ and $y$. One of the multiples is always their product, $b\cdot y$. I look at each fraction and think, "what do I need to do to the denominator, $b$ in this case, to make it into $b\cdot y$?" Well, I can just multiply it by $y$. But, we must keep balance and multiply the numerator by $y$ as well:

$$\frac{y\cdot a}{y\cdot b} + \frac{x}{y}$$

Then for the other fraction I ask myself the same question, "what do I need to do to the denominator, $y$ in this case, to make it into $b\cdot y$?" This time I must multiply by $b$, both in the numerator and denominator to maintain balance. 

$$\frac{y\cdot a}{y\cdot b} + \frac{x\cdot b}{y\cdot b}$$

Since multiplication is *commutative* I can write it as:

$$\frac{ay}{by} + \frac{bx}{by}=\frac{ay+bx}{by}$$

Once they have the same denomiator I can add the numerators and put the sum over the LCD (DO NOT add/sub the denominators!)

#### Multiplying Fractions
Any number has an invisible 1 as its denominator. In that case, you can multiply a fraction by a fraction and a fraction by a whole number and more. 

$$\frac{a}{b}\cdot \frac{x}{y}$$

Multiplication of fractions requires the least amount of work because you simply multiply straight across: 

$$\frac{a}{b}\cdot \frac{x}{y}=\frac{ax}{by}$$

#### Dividing Fractions
Any number has an invisible 1 as its denominator. In that case, you can divide a fraction by a fraction, a fraction by a whole number, a whole number by a fraction, and so on:

$$\frac{\frac{a}{b}}{\frac{x}{y}}=\frac{a}{b}/ \frac{x}{y}=\frac{a}{b}\div \frac{x}{y}$$

To divide fractions think: "keep, change, flip". You keep the first fraction as it is, change the division to multiplication, and then take the reciprocal of the second fraction (from left to right or top to bottom).

$$\frac{a}{b}\div \frac{x}{y}=\frac{a}{b}\cdot \frac{y}{x}=\frac{ay}{bx}$$

## Inequalities, Intervals, and Absolute Values
A number is **positive** if it is to the right of 0 on the number line, common notation to describe positive is: $x>0$

A number is negative if it is to the left of 0 on the number line, common notation to describe negative is $x<0$

#### Recall: Sum and Products of Positives and Negatives

* positive $+$ positive $=$ positive
* negative $+$ negative $=$ negative
* positive $*$ positive $=$ positive
* negative $\div$ negative $=$ positive
* positive $\div$ negative $=$ negative $\div$ positive $=$ negative

### Inequalities
A number $a$ is less than a number $b$ if $a$ is to the left of $b$ on the number line, it is represented as $a<b$. 

A number $a$ is less than or equal to a number $b$ if $a<b$ OR $a=b$, it is represented as $a\leq b$.

A number $b$ is greater than a number $a$ if $b$ is to the right of $a$ on the number line, it is represented as $b>a$. 

A number $a$ is less than or equal to a number $b$ if $a<b$ OR $a=b$, it is represented as $a\leq b$. A number $b$ is greater than or equal to a number $a$ if $b>a$ OR $b=a$, it is represented as $b\geq a$.

It may help to differentiate these if you consider the inequality symbol as an arrow. If it points **L**eft, then it is a **L**ess than. If it points **R**ight it is a g**R**eate**R** than!

#### Mult/Div with Inequalities
Remember that if you EVER multiply or divide to either side of the inequality you **MUST** flip the inequality symbol $>$ or $<$ !
### Intervals
A **set** is a collection of things. In mathematics, there may be sets with a collection of numbers both finite and infinite. An **interval** is a set of real numbers that contains all numbers between any two numbers in the set. 

+ open interval $(a,b)$ is the set of numbers between a and b, not including a or b. In inequality notation $(a,b)=\lbrace x:a<x<b \rbrace$
+ closed interval $[a,b]$ is the set of numbers between a and b, including a and b. In inequality notation $[a,b]=\lbrace x:a\leq x\leq b \rbrace$
+ half-open intervals $(a,b]$ or $[a,b)$ represent the intervals $\lbrace x:a<x\leq b \rbrace$ and $\lbrace x:a\leq x<b \rbrace$ respectively

#### Intervals Extended Infinitely
Interval Notation|Inequality notation|description
-----------------|--------------------|-----------
$(a,\infty)$|$\lbrace x:x>a\rbrace$| the set of numbers greater than a
$[a,\infty)$|$\lbrace x:x\geq a\rbrace$| the set of numbers greater than or equal to a
$(-\infty,a]$|$\lbrace x:x<a\rbrace$| the set of numbers less than a
$(-\infty,a]$|$\lbrace x:x\leq a\rbrace$| the set of numbers less than or equal to a

**Notice**: neither of the infinites have a bracket. They never do! Since we do not know how large or far this interval goes, we cannot include it!

The **union** of two sets is the set of objects that is in at least one of the sets. Think of it as a combination of all the elements of each set. For example:

$[-2,1)\cup[1,3)$

This represents the following set of integers: $\lbrace -2,-1,0\rbrace\cup\lbrace1,2\rbrace =\lbrace -2,-1,0,1,2\rbrace$. In other words, this union of integers can be represented as $[-2,3)$

### Absolute Values
The definition of absolute value is: the distance a number is from zero. Remember that! This is represented as:

<!-- DONT KNOW HOW TO DO PIECEWISE ON HERE -->

\[ \begin{cases}
    b & \text{if} b\geq 0\\
    -b & \text{if} b\leq 0
    \end{cases}
\]

#### How to solve inqualities
For an inequality problem like 

$$|x+a|<b$$

Notice this is a **less** than (can be $\leq$), which becomes a "between" inequality:

$$|x+a|<b= -b<x+a<b$$

Then you would isolate the x by adding the inverse of a to each part of the inequality as such:

$$-b+(-a)<x+a+(-a)<b+(-a)$$
$$-b-a<x<b-a$$

Which implies that $x$ is a number between the interval $(-b-a,b-a)$

For an inequality problem like 

$$|x+a|>b$$

Notice this is a **greater** than (can be $\geq$), which becomes an "or" inequality:

$$|x+a|>b\hspace{0.5cm} = \hspace{0.5cm}x+a>b \hspace{1cm}\text{or}\hspace{1cm}x+a<-b$$

Then you work with each inequality separately, and isolate x by getting rid of the a as so:

$$x+a>b \hspace{1cm}\text{or}\hspace{1cm}x+a<-b$$
$$x+a+(-a)>b+(-a) \hspace{1cm}\text{or}\hspace{1cm}x+a+(-a)<-b+(-a)$$
$$x>b-a\hspace{1cm}\text{or}\hspace{1cm}x<-b-a$$
Which implies that x is a number greater than b-a or $(b-a,\infty)$ **OR** x is a number less than -b-a or $(-\infty, -b-a)$. This can be represented as the union $(-\infty, -b-a)\cup (b-a,\infty)$

#C2