

## Demonstration of time-reversibility Of a Stokes Flow:
https://www.youtube.com/watch?v=8V6kc0PQa14

## Q&A assisted with GPT-4: What are inertial forces and viscous forces?

In fluid mechanics, an inertial force is a force that arises due to the motion of a fluid and is proportional to its mass and acceleration. The inertial force exists because the reference frame is non-inertial. A viscous force, on the other hand, is a force that arises due to the internal friction between adjacent layers of fluid and is proportional to the viscosity of the fluid.

## What is Viscosity?

Viscosity is a measure of fluid "thickness", proportional to the viscous force.

## How are the Stokes flow Equations obtained?

In the Stokes equations, the inertial term (ρ(∂u/∂t + u ⋅ ∇u)) from the Navier-Stokes equations is neglected. This simplification is valid for low Reynolds number flows, where viscous forces dominate over inertial forces. By neglecting the inertial term, the momentum equation becomes independent of time, as there is no explicit time dependence in the remaining terms.


## What is instantaneity?

Instantaneity can either mean that:
	The flow does not depend on time 
or that
	The flow reacts instantaneously to a force applied.
Instantaneity in Stokes flow follow the first definition.

## What does ∇ ⋅ σ + f = 0 mean in the Stokes equations?

In the context of the Stokes equations, the equation ∇ ⋅ σ + f = 0 represents the force balance in a fluid. Here's a breakdown of the terms:
1. ∇ ⋅ σ: This term represents the divergence of the stress tensor (σ). The stress tensor describes the forces acting on the fluid due to viscosity and pressure. The divergence of the stress tensor (∇ ⋅ σ) gives the net force acting on a fluid element due to these stresses.
2. f: This term represents the external force acting on the fluid, such as gravity or any other body force.
The equation ∇ ⋅ σ + f = 0 states that the sum of the net force due to the stress tensor and the external force is zero. This means that the forces acting on the fluid are in balance, which is a key assumption in the Stokes equations. The Stokes equations describe the motion of a viscous fluid at low Reynolds numbers, where inertial forces are negligible compared to viscous forces.

## How does ∇ ⋅ u = 0 demonstrate the conservation of mass?

The continuity equation for an incompressible fluid is given by:
∇ ⋅ u = 0
Where u is the fluid velocity vector, and ∇ ⋅ u is the divergence of the velocity field.
The divergence of a vector field is a measure of how much the field is expanding or contracting at a given point. In the context of fluid flow, the divergence of the velocity field (∇ ⋅ u) represents the net rate at which fluid is flowing into or out of a small volume element around a point.
When the divergence of the velocity field is zero (∇ ⋅ u = 0), it means that the net flow of fluid into or out of any volume element is zero. In other words, the amount of fluid entering a volume element is equal to the amount of fluid leaving it. This condition ensures that the mass of the fluid is conserved, as there is no accumulation or depletion of mass within any volume element in the fluid.
