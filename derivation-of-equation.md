# Derivation of Fluid Equations

## Introduction

In this post, I will collect and review the derivation of a list of fluid equations including

* Euler Equation
* Navier-Stokes Equation (NSE)
* Quasi-geostrophic Equation (QG)
* Surface Quasi-geostrophic Equation (SQG)

Important tools for the analysis includes material derivative, Hilbert expansion, harmonic extension, beta-plane approximation, Boussinesq approximation...

## Euler Equation

## Navier-Stokes Equation

## Quasi-geostrophic Equation

\renewcommand*{\d}{\mathop{\kern0pt\mathrm{d}}\!{}}
\renewcommand*{\D}{\mathop{\kern0pt\mathrm{D}}\!{}}
\newcommand{\Dfr}[2]{\frac{\D #1}{\D #2}}
\newcommand{\bu}{\boldsymbol u}

Quasi-geostrophic equation describe the motion of a stratified fluid on a rotation sphere. Let the angular velocity of the earth be $\boldsymbol\Omega = \Omega \hat z$ with angular speed $\Omega = 7.3 \times 10^{-5} \operatorname{sec}^{-1}$. A fluid parcel in a rotating frame experiences the pressure, the [Coriolis force](https://en.wikipedia.org/wiki/Coriolis_force) and the gravity. The govening primitive equation of the flow are
$
\begin{align}
  \rho \Dfr \bu t = - \rho \grad p - 2 \rho \boldsymbol\Omega \times \bu + \rho \boldsymbol g.
\end{align}
$
Then the Coriolis parameter $f$ is $2 \Omega \sin \theta$ where $\theta$ is the latitude. 

## Surface Quasi-geostrophic Equation
