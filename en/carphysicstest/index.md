**[`< Projects`](https://codecanter.github.io/portfolio/en/)**

![Car](https://github.com/user-attachments/assets/595e41c4-589d-4dda-9716-ac916874ecf8)

**CarPhysicsTest** (11.2024 - now)

**[`> Repository`](https://github.com/CodeCanter/CarPhysicsTest_Public)**

A car simulator, in which the emphasis is placed on the representation of vehicle physics (taking into account the main forces). The developed model can be the basis for a driving training/improvement simulator.

Project assumptions:
- considering whether WheelCollider components are worth using as part of the vehicle's physical model - it was decided not to use this component; vehicle suspension was developed based on Physics.SphereCast
- taking into account the main forces acting on the vehicle:
    - suspension force (spring-shock absorber assembly)
    - lateral force (preventing the vehicle from slipping across the slope - if the tire's grip forces are sufficient)
    - frontal resistance force
    - force from the drive wheels (the friction force and the possibility of losing grip of the tire during acceleration were taken into account)
    - braking force (the possibility of losing grip of the tire was taken into account, currently without ABS system simulation)
    - rolling resistance forces
- forces counteracting the centrifugal force when changing the direction of the vehicle's movement (the possibility of vehicle slippage was taken into account)
reproducing the characteristics of the adopted vehicle - mass, resistance coefficients, engine characteristics, braking distance, etc.

![CarPhysics](https://github.com/user-attachments/assets/aa8984bb-f3ef-4aef-bfb0-1203f0837c12)

**[`< Projects`](https://codecanter.github.io/portfolio/en/)**
