---
title: "Quantum Package 2.0: An Open-Source Determinant-Driven Suite of Programs"
collection: publications
permalink: /publication/2018-02-21-Quantum-Package-2.0
excerpt: 'Quantum Package is an open-source programming environment for quantum chemistry specially designed for wave function methods.'
date: 2019-02-21
venue: 'arXiv'
paperurl: 'http://mveril.github.io/files/2019-02-21-Quantum-Package-2.0.pdf'
citation: '&quot;Quantum Package 2.0&quot;

Yann Garniron, Thomas Applencourt, Kevin Gasperich, Anouar Benali, Anthony Ferté, Julien Paquier, Barthélémy Pradines, Roland Assaraf, Peter Reinhardt, Julien Toulouse, Pierrette Barbaresco, Nicolas Renon, Grégoire David, Jean-Paul Malrieu, Mickaël Véril, Michel Caffarel, Pierre-François Loos, Emmanuel Giner, Anthony Scemama
<i>arXiv</i>
arXiv:1902.08154 [physics.comp-ph]'
---
Quantum Package is an open-source programming environment for quantum chemistry specially designed for wave function methods. Its main goal is the development of determinant-driven selected configuration interaction (sCI) methods and multi-reference second-order perturbation theory (PT2). The determinant-driven framework allows the programmer to include any arbitrary set of determinants in the reference space, hence providing greater methodological freedoms. The sCI method implemented in Quantum Package is based on the CIPSI (Configuration Interaction using a Perturbative Selection made Iteratively) algorithm which complements the variational sCI energy with a PT2 correction. Additional external plugins have been recently added to perform calculations with multireference coupled cluster theory and range-separated density-functional theory. All the programs are developed with the IRPF90 code generator, which simplifies collaborative work and the development of new features. Quantum Package strives to allow easy implementation and experimentation of new methods, while making parallel computation as simple and efficient as possible on modern supercomputer architectures. Currently, the code enables, routinely, to realize runs on roughly 2\,000 CPU cores, with tens of millions of determinants in the reference space. Moreover, we have been able to push up to 12\,288 cores in order to test its parallel efficiency. In the present manuscript, we also introduce some key new developments: i) a renormalized second-order perturbative correction for efficient extrapolation to the full CI limit, and ii) a stochastic version of the CIPSI selection performed simultaneously to the PT2 calculation at no extra cost. 
[Download file here](hhttp://mveril.github.io/files/2018-02-21-Quantum Package 2.0.pdf)