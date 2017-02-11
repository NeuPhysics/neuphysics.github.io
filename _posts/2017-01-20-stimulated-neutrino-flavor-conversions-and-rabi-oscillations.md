---
title: "Stimulated Neutrino Flavor Conversions and Rabi Oscillations"
date: 2017-01-23
modified: 2017-01-23
author: OctoMiao
toc: true
comments: true
categories: neutrino
summary: Neutrino oscillations in matter is very different from oscillations in vacuum.
published: true
---

I'll talk about a very interesting phenomenon in neutrino oscillations, the stimulated neutrino flavor conversions, which might happen when neutrinos travel through dense medium, and how can we understand such behavior using Rabi oscillations.



## Background

Neutrinos are light but they have mass. What we know now is that there are probably three masses, the mass difference between the first two is quite small, and the third mass is quite different from the first two. The problem is we do not know whether the third mass is heavier of lighter. If it's heavier we call it normal hierarchy, otherwise it is inverted hierarchy.

Neutrinos oscillations are in fact neutrino flavor conversions. Suppose we have a electron neutrino here. It propagates and transforms into other flavors.

We can define the probability for each flavors and plot it out vs the distance that the neutrino traveled. Here in this plot, vertical axis is the probability for each flavors. In this example, we have electron neutrino in the beginning, as it travels we have a probability of detecting other flavors. And it has a periodic shape that's why it's called neutrino oscillations.

Then why do they oscillate? We'll demonstrate it using two flavors. Three flavor neutrino oscillations are basically the same. It's just more involved in math.

In quantum mechanics, we know that in a two level system a particle on one of its eigen states will remain on that state. For relativistic particles, eigen energy states are determined by masses. Suppose we have a neutrino on one of its eigen energy state or mass state, it will remain on that state. Since flavor states are different from eigen energy states, neutrinos start as electron flavor will change on its path.

In fact flavor states of neutrinos are related to eigen states of neutrinos in this way. $\theta_v$ is the called vacuum mixing angle. If $\theta_v$ equals to 0, we have no mixing.

The evolution of the states are determined by Schrodinger equation. Here the wave function has two amplitudes, one for electron flavor, one for muon flavor. $\mathbf H$ is the Hamiltonian. It is a 2 by 2 matrix. $\omega_v$ is the vacuum oscillation frequency. It's related to the energy and the masses of neutrinos. The sigmas are the Pauli matrices.

We can easily solve the Schrodinger equation and find out the change of flavors. Here and throughout this talk I provide a visualization of the system. The trick is to use Pauli matrices to rewrite Hamiltonian and wave function into three dimensional vectors.

We define a vector $\vec H$ in this way using the Pauli matrices. We also define a flavor isospin vector $\vec s$ using the wave function. $\vec s$ is a three dimensional vector that represents the state of the system. In our definition, if it's pointing upward then we have only electron flavor. If it's pointing downward, then we have only muon flavor. In between we have a mixture of electron flavor and muon flavor.

The equation of motion becomes an equation of precession. $\vec s$ is going to precess around vector $\vec H$.

Now let's apply this to the oscillation Hamiltonian, it is a vector that is tilted away from the vertical axis. Suppose we start from electron flavor. Then we have the flavor isospin vector pointing upward. Due to the precession, we will find that the state rotates into states that is a mixture of electron flavor and muon flavor. And it's periodic.


## Matter effect

So that was vacuum oscillations. How can the interaction with matter change the oscillations of neutrinos? The idea is simple. Different flavors of neutrino experience different potentials or drags in matter.

In the stars, there are a lot of electrons, protons and neutrons. They all interact with all flavors of neutrinos through neutral current. And this interact is blind to flavors: all the flavors experience the same drag. This means that this kind of interaction has no effect on the different flavors. But in the stars we have a lot of electrons and electrons interact with electron flavor neutrinos through charged current. So electron flavor neutrinos experience an extra potential compared to other flavors. This is the reason why matter interaction can change the oscillations.

We can write down the Hamiltonian here. We still have the vacuum part. The matter effect comes in as a potential. $\lambda$ is proportional to the number density of electrons.

We can still use the Pauli matrices to map it into a three dimensional vector. Here we have the vacuum part which is constant. The matter potential is vector pointing downward.

Let's make some diagrams. If the matter density is large, then the vector for matter potential is large. The vector for total Hamiltonian will point downward. If we have only electron neutrinos in the beginning, the precession is tiny. In this case, the conversion from electron flavor to the other flavor is small. If we have a not-so-large density, the precession becomes larger, then we have larger flavor conversion.

At some point, when the matter potential cancels out the vertical component vacuum Hamiltonian, the vector for Hamiltonian is perpendicular to the initial state $\vec s$, then the neutrinos will be converted from electron flavor to the other flavor completely. For low density, the matter potential is small and the oscillations reduce to vacuum oscillations.

Now we know that matter interactions can be important to neutrino oscillations. In many astrophysical environments, such as supernova explosion, neutrinos might experience a turbulent matter potential. A neutrino escaping from the center have to go through the turbulent medium of the supernova shock.

Even though we can solve a problem with turbulent matter potential numerical it doesn't really provide a lot of intuitions. We'll look at a simple case. The electron number density has a cosine perturbation. $n_0$ is a constant background. So the potential will also have the same structure.

(Key: explain why this is different from MSW; explain the plot)
People have done research on this topic. They found that neutrino flavor conversions can also be dramatically different from constant matter potential oscillations.
So MSW resonance requires a specific matter density. Because it has to cancel out the vertical component of the vacuum Hamiltonian. But with periodic perturbations, we can have large conversions for matter densities that is far away from the MSW resonance requirement.
Here is an example reproduced for simplicity. In this example, the matter potential has a periodic perturbation with perturbation frequency $k$. The matter density is set to well below the MSW resonance requirement. We plotted the transitions between two background eigen energy states. I'll explain more later but for now, if there is no perturbation, there would be no transitions in this plot. However with the perturbation, we have have full conversion between two states here. And one can prove that it can lead to full conversion of flavors.


## Stimulated Neutrino Flavor Conversions


We are basically talking about a stimulation of two level system using periodic potential. Another kind of simple oscillations that can have resonance behavior, that I can think of, is Rabi oscillation. It turns out our neutrino oscillations are not so different from Rabi oscillations.
