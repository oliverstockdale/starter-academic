---
title: Vortex dynamics in two-dimensional superfluids
date: 2020-09-28T17:14:04.955Z
summary: A brief summary of my research into superfluid vortex dynamics.
draft: false
featured: false
external_link: https://www.google.com
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

Here, $V(\mathbf{r})$ is the trapping potential of the superfluid, and $g$ describes the interactions between the superfluid atoms. By numerically solving the Gross-Pitaevskii equation, we can either directly simulate an experiment to confirm our observations, or gain further information about observations that cannot be directly acccessed in an experiment.

### Thin-film superfluid helium

For instance, in one project we worked closely with the [Queensland Quantum Optics Lab](http://www.physics.uq.edu.au/QOlab/index.html) to study the dynamics of vortices in thin-film superfluid helium. This experiment uses superfluids to perform optomechanical experiments to work towards building ultra-precise quantum sensors. 

In their experiment, vortices were present and within the superfluid which led to some unexplained oberservations. Vortices in thin-film superfluid helium cannot be directly imaged, so we simulated their dynamics to gain insight into the experiment and understand their observations. As the Gross-Pitaevskii equation fails for superfluid helium, we used an approximate method called the *point vortex model* to simulate the vortex dynamics.

![Schematic of vortex dynamics in the superfluid helium experiment. Credit: Dr. Chris Baker, UQ.](f1.large.jpg)

Our collaboration led to the first observation of coherent vortex dynamics in a strongly-interacting superfluid in quasi-two-dimensions. Our results can be found [here](https://science.sciencemag.org/content/366/6472/1480?casa_token=wM3m7mt5wb0AAAAA:I5dlf4yfCKk-qqV5x2U9-Zcsif8Sh8QNpTEmNbE4Z1JfLY8iUhzJKe9pkX4wBXSczNjyLhjJwCu5rP56).

### Anomalous hydrodynamics

From these experiments, we began to observe some interesting properties about the dynamics of *chiral vortex clusters* (these are collections of same-sign vortices). We found that in a finite temperature superfluid, **all** distributions of chiral vortex clusters expanded