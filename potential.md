[Back to all lessons](.)

# Electric Force, Electric Field, Electric Potential Energy, Electric Potential?

Read about Electric Force ($F_E$), Electric Field ($E$), Electric Potential Energy ($PE_E$ or $U$), and Potential Difference ($\Delta V$), and it will become clearer.


## Electric Force - Coulomb's Law, Electric Field

*Coulomb's Law* states that the Electric Force ($F_E$) between two charged particles (with charges $q_1$ and $q_2$), separated by a distance ($r$) is:

$$F_E = \frac{kq_1 q_2}{r^2}$$

Distance is measured in *meters* ($m$), charge is measured in *coulombs* ($C$), and Force is measured in *newtons* ($N$). The constant $k$ is equal to $9\times 10^9 \frac{Nm^2}{C^2}$.

<img src="coulomb1.jpg" width="200" alt="force"/>

Newton's Third Law tells us that for every force there is an equal and opposite force. We see that the force on particle 2 ($F_{12}$) is equal in magnitude and opposite in direction to the force on particle 1 ($F_{21}$).

If we write coulomb's law slightly differently, we can see that the force on a particle is proportional to its own charge:

$$F_{12} = \frac{kq_1}{r^2} \times q_2$$

and so

$$F_{12}\propto q_2$$

That is, if we *double* $q_2$, we *double* $F_{12}$; if we *triple* $q_2$, we *triple* $F_{12}$, etc..

If we think separately about the effect of particle 1 at distance $r$, and particle 2's charge, we see:


$\underbrace{F_{12}}\_\text{Force on particle 2} =  \underbrace{\frac{kq_1}{r^2}}\_\text{effect of particle 1 at distance $r$} \times q_2$

We call the effect of particle 1 at distance $r$ the *electric field* due to particle 1,

$$E_1 = \underbrace{\frac{kq_1}{r^2}}_{\text{effect of particle 1 at distance $r$}}$$

which allows us to refer to the force on particle 2 ($F_{12}$) as:

$$
\begin{align\*}
F_{12} &= \frac{kq_1}{r^2} &\times q_2 \\\\
&= \underbrace{E_1}_\text{effect of particle 1 at distance $r$} &\times q_2 \\\\
\end{align\*}
$$

This gives the equation

$$F = Eq$$

where $E$ depends on *charge somewhere*, but $q$ refers to the charge of the particle experiencing the force.

We can also rearrange this as

$$ E = \frac{F}{q}$$

to **characterize Electric Field as *Force per unit charge* **.

Force has units *newtons* ($N$), charge has units *coulombs* ($C$), and electric field has units *newtons per coulomb* ($\frac{N}{C}$).

### Video on Electric Field (watch it!)

* 1:20-2:30 is about $E=\frac{F}{q}$
* 2:30-6:00 is an **excellent** explanation of *electric field lines*
* 6:00-6:45 introduces capacitors
* 6:45-7:50 explains why **the electric field inside a conductor is $0$**.


<iframe width="560" height="315" src="https://www.youtube.com/embed/mdulzEfQXDE?rel=0&amp;start=80" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

## What is Electric Potential?

### Video on Electric Potential (cool British woman))

* 0:52-1:33 What is a capacitor?
* 1:33-2:27 **Potential energy** of a particle in a uniform electric field (between plates of capacitor)
* 2:27-3:01 **Electric Potential** and $V = \frac{\Delta PE}{q} = Ed$ (See **&hearts;Note**)
* 3:01- Calculating $V$
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZrMltpK6iAw?start=51" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

**&hearts;Note**: We know does $V = \frac{\Delta PE}{q}$, but why does $V = Ed$ as well?

$$
\begin{align\*}
V &= \frac{\Delta PE}{q}\\\\
\\\\
&= \frac{\overbrace{W}^{W=\Delta E}}{q}\\\\
\\\\
&= \frac{\overbrace{Fd}^{W=Fd}}{q}\\\\
\\\\
&= \frac{F}{q}d\\\\
\\\\
&= \overbrace{E}^{E=\frac{F}{q}}d
\end{align\*}
$$
thus, we see $V=Ed$.

#### Units of Electric Field: $V/m$ or $N/C$?

We can rearrange $V=Ed$ to $E=\frac{V}{d}$...but we already know $E=\frac{F}{q}$!

Let's compare $\underbrace{E}\_\text{$V/m$}=\frac{\overbrace{V}^\text{Volts ($1V = 1J/C$)}}{\underbrace{d}\_\text{meters ($m$)}}$ to $\underbrace{E}\_\text{$N/C$}=\frac{\overbrace{F}^\text{Newtons ($N$)}}{\underbrace{q}\_\text{Coulombs ($C$)}}$.

(Remember that $1V = 1J/C = \frac{1J}{1C} = \frac{1Nm}{1C} = \frac{(1N)(1m)}{1C}$)

$$
\begin{align\*}
1 V/m &= \frac{1V}{1m}\\\\
&=(1V)\times \frac{1}{1m}\\\\
&= \frac{(1N)(1m)}{1C}\times \frac{1}{1m}\\\\
&= \frac{(1N)(\cancel{1m})}{1C} \times \frac{1}{\cancel{1m}}\\\\
&= \frac{1N}{1C}\\\\
&= 1N/C
\end{align\*}
$$

So, $1V/m = 1 N/C$, and both measure the exact same thing - *electric field*.

## Videos

### Visual Analogy to Gravitational Potential (which depends on height and is realized through "falling")
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Rb9guSEeVE?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

### Blackboard Explanation

<iframe width="560" height="315" src="https://www.youtube.com/embed/wT9AsY79f1k?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


<script type="text/x-mathjax-config">
MathJax.Hub.Register.StartupHook("TeX Jax Ready",function () {
  MathJax.Hub.Insert(MathJax.InputJax.TeX.Definitions.macros,{
    cancel: ["Extension","cancel"],
    bcancel: ["Extension","cancel"],
    xcancel: ["Extension","cancel"],
    cancelto: ["Extension","cancel"]
  });
});
</script>
