Wind Turbine BEM Analysis

This project implements the Blade Element Momentum (BEM) method in Python to analyze the aerodynamic performance of a horizontal-axis wind turbine using the NACA 2412 airfoil. The code calculates aerodynamic forces, torque, and power, and visualizes key performance metrics.

Project Overview

Wind turbines generate electricity by extracting kinetic energy from wind. Their performance depends heavily on aerodynamic blade design (chord, twist, airfoil).

The BEM theory is a widely used engineering tool that combines:

Blade element theory → divides the blade into radial sections and calculates lift & drag forces.

Momentum theory → applies conservation of mass and momentum to airflow through the rotor disk.

By iterating between these models, the method estimates induction factors, thrust, torque, and power coefficient (Cp).

Features

Airfoil data for NACA 2412 with linear interpolation for Cl and Cd.

Chord distribution (tapered blade) and twist distribution (linear twist).

Iterative solver for axial (a) and tangential (a′) induction factors.

Performance evaluation for varying:

Tip-Speed Ratio (λ)

Wind Speed (V0)

Visualization of:

Cl vs Angle of Attack

Cp vs λ

Cp vs V0

Tangential Force Ft vs r/R

Torque vs Thrust
