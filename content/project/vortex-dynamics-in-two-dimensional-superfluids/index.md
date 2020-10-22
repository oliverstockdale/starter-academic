---
title: Vortex dynamics in two-dimensional superfluids
date: 2020-09-28T17:14:04.955Z
summary: A brief summary of my research into vortex dynamics.
draft: false
featured: false
image:
  filename: featured.png
  focal_point: Smart
  preview_only: false
  caption: "Credit: Dr. Chris Baker, UQ."
---
Superfluidity is a rich and unusual phenomenon that exhibits macroscopic quantum behaviour. Superfluids have *zero viscosity*, which means they can flow without loss of kinetic energy. This has very interesting and exiciting implications to future quantum technologies where this *dissipationless* property of superfluidity could be exploited to, for example, [build very low-energy electronic transistors](http://www.fleet.org.au).

However, superfluids can contain quantum vortices – tiny whirlpools that spin around and interact with one another (see the header figure). These vortices can be closely related to the emergence of dissipation in a superfluid. As such, we must study their dynamics to understand how we can predict their behaviour and even, perhaps, control it.

To study these vortices, we simulate their dynamics on a computer. Our starting point is the superfluid wave function, $\Psi(\mathbf{r},t)$, which describes the superfluid as a classic field. In the limit where the interactions between the superfluid atoms are weak, the dynamics follow the Gross-Pitaevskii equation

$$i\hbar\frac{\partial\Psi(\mathbf{r},t)}{\partial t} = \left\[-\frac{\hbar^2}{2m}\nabla^2+V(\mathbf{r})+g|\Psi(\mathbf{r},t)|^2\right]\Psi(\mathbf{r},t).$$

Here, $V(\mathbf{r})$ is the trapping potential of the superfluid, and $g$ describes the interactions between the superfluid atoms. By solving the Gross-Pitaevskii equation, we can either directly simulate an experiment to confirm our observations, or gain further information about observations that cannot be directly acccessed in an experiment.
