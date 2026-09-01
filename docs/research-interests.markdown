---
layout: page
title: "Research Interests"
permalink: /research-interests/
weight: 2
---

<style>
    p {
        text-align: justify;
    }
    .figure-container {
        display: flex;
        align-items: center;
        margin-bottom: 20px;
    }
    .figure-container img {
        max-width: 40%;
        height: auto;
        margin-right: 20px;
    }
    .figure-caption {
        max-width: 60%;
        text-align: justify;
    }
</style>

<h3><u>Complex Dynamical Systems</u>, <u>Nonequilibrium Statistical Physics</u>, <u>Many-Body Dynamics</u></h3>

<p>Our research focuses on fundamental dynamical constraints that govern irreversibility,
transport, and chaotic growth in nonequilibrium systems. We seek organizing principles,
including geometric, inertial, and informational constraints, that determine what a system
operating out of equilibrium can and cannot do.</p>

<h4 style="margin-top: 20px;">Force Geometry and Irreversibility</h4>

<p>A central direction of our current work is a geometric formulation of nonequilibrium
irreversibility based on the instantaneous organization of forces. In driven overdamped
systems, externally applied forces and information (entropic) forces associated with the
evolving probability distribution are separated and compared through a time-dependent
force-correlation measure. This captures how force misalignment produces irreversible
dissipation.</p>

<div class="figure-container">
    <img src="{{ site.baseurl }}/images/force-geometry.png" alt="Force geometry and irreversibility schematic">
    <p class="figure-caption"><strong>Figure 1:</strong> Irreversibility arising from the geometric relation between
    the externally imposed force and the information (entropic) force associated with the evolving distribution.</p>
</div>

<p>This framework provides an instantaneous characterization of dissipation without relying
on steady-state or quasistatic assumptions. It distinguishes thermodynamic stall from true
reversibility and identifies geometric waste: dissipation arising from force misalignment
that cannot be removed by protocol optimization alone. Ongoing work extends this perspective
to periodically driven systems relevant to optical-tweezer microrheology and soft matter,
as well as to underdamped and higher-dimensional dynamics.</p>

<h4 style="margin-top: 20px;">Speed Limits on Nonequilibrium Dynamics</h4>

<p>We are developing a classical density theory that draws parallels with the density-matrix
formulation of quantum mechanics. The theory is designed to ensure norm-preserving evolution
in the tangent space of deterministic systems and applies to both Hamiltonian and dissipative
dynamics.</p>

<div class="figure-container">
    <img src="{{ site.baseurl }}/images/Lorenz-attractor-speed-limit-400x400.png" alt="Local perturbation growth rate schematic">
    <p class="figure-caption"><strong>Figure 2:</strong> How quickly can the growth rate of a local perturbation
    to a system change over time? <a href="https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.5.L012016">[Das & Green, PRR (Letter), 2023]</a></p>
</div>

<p>One major finding is a set of model-independent dynamical speed limits for deterministic
systems, closely analogous to quantum and stochastic speed limits. These results give
time-information uncertainty relations for deterministic systems and bounds on the rates
of entropy production and the variation of local stability indicators, including Lyapunov
exponents.</p>

<div class="figure-container">
    <img src="{{ site.baseurl }}/images/Max-speed.png" alt="Entropy production speed limit schematic">
    <p class="figure-caption"><strong>Figure 3:</strong> What is the minimum entropy production rate that can occur
    in a given time interval? <a href="https://journals.aps.org/pre/abstract/10.1103/PhysRevE.109.L052104">[Das & Green, PRE (Letter), 2024]</a></p>
</div>

<p>An important element of this work is a classical Fisher information tailored to
deterministic differentiable dynamics, analogous to quantum Fisher information. This
measure connects phase-space geometry with dynamical instability. More broadly, the
framework bridges the dynamical-systems perspective on stability and phase-space
structure with the stochastic-thermodynamics perspective on entropy production and
fluctuations.</p>

<h4 style="margin-top: 20px;">Bounds on Chaos in Many-Body Systems</h4>

<p>A major new direction is the development of intrinsic bounds on chaotic growth in
classical many-body Hamiltonian systems. By analyzing the instantaneous stability matrix
of Hamiltonian flows, we derive upper bounds on the largest Lyapunov exponent that apply
at all times and cannot be transiently violated.</p>

<div class="figure-container">
    <img src="{{ site.baseurl }}/images/dynamical-speed-limits.png" alt="Dynamical speed limits schematic">
    <p class="figure-caption"><strong>Figure 4:</strong> Fundamental constraints on nonequilibrium dynamics, including
    an inertial ceiling and dynamical bounds on the rate of evolution.</p>
</div>

<p>These bounds separate geometry-blind contributions, controlled by local curvature, from
geometry-aware contributions that retain spectral information and collective modes. In
one-dimensional rotor chains, they predict forbidden regions in the Lyapunov exponent--energy
plane. In the thermodynamic limit, the results reveal an inertial ceiling on chaotic growth
in classical many-body systems.</p>

<h4 style="margin-top: 20px;">Outlook</h4>

<p>Our long-term goal is to develop a coherent and integrative framework for nonequilibrium
dynamics that explains how irreversibility, chaos, and transport are shaped by geometric,
inertial, and informational limits, rather than by detailed microscopic modeling alone.</p>
