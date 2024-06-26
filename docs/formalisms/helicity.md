# Helicity formalism

```{warning}
These pages are **under development**.
```

:::{todo}

- Lorentz-invariance of helicity operator

- Types

  - Two-body decay amplitude
  - Sequential two-body decay amplitude

- Definition of angles

  - Production angle
  - Helicity angle
  - Treiman-Yang angle
  - Overview of kinematic variables

- Dynamics:

  - Wigner-D functions
  - Clebsch-Gordan coefficients

- Kinematic variables
- An example

:::

<!-- Two particle states are the key element here. With these one can construct
states of total spin $J$ and projection $M$.

The probability amplitude of a state with spin J and projection M decaying into
two particles 1 and 2 with helicities $\lambda_i$ and momentum $\vec{p}$ in the
cms frame is given by {cite}`chungSpinFormalismsUpdated2014`, p.16.

$$
two body decay amplitude here
$$

In the helicity formalism sequential two body decays are easy to handle

$$
seq two body decay amplitude here
$$

Then show explicitly what ComPWA implements and which components correspond to
what part in the equation. So we would refer in the Doxygen docs to

- the Wigner-$D$ functions

- the Kinematics class

- the IntensityBuilderXML with the two functions createSequentialAmplitudeFT
  createHelicityDecayFT

- the dynamical functions

- the phase space element calculations?

[IntensityBuilderXML](https://compwa.github.io/ComPWA/classComPWA_1_1Physics_1_1IntensityBuilderXML.html)
-->

{cite}`Jacob:1959at`

## Canonical formulation

<!-- The canonical formalism gives access to the orbital angular momentum $L$ and
the coupled Spin $S$ arising from a two particle state.

There is a simple connection between the two formalism. Show that here

This expression is simply inserted into equation () and that is it!

The choice of the formalism depends on the physics process being analyzed. Give
an example here. -->

{cite}`Li:2022qff`

## Alignment problem

Recommended literature:

<!-- cspell:ignore aaij Dalitzplot Marangotto Threebody -->

- General introductions to helicity angles: <br>
  {cite}`kutschkeAngularDistributionCookbook1996, Richman:1984gh`
- Suggested solutions: <br>
  {cite}`Chen:2017gtx, Marangotto:2019ucc, Wang:2020giv, JPAC:2019ufm`
- LHCb study that led to these solution papers: <br>
  {cite}`LHCb:2015yax`
