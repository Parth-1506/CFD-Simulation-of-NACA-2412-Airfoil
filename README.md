# 🚀 CFD and Structural Analysis of NACA 2412 Airfoil using ANSYS

This project involves Computational Fluid Dynamics (CFD) and Static Structural Analysis of the **NACA 2412 airfoil** using ANSYS Fluent and ANSYS Static Structural tools. The aim is to analyze the aerodynamic performance and structural integrity of the airfoil under simulated flow conditions.

---

## 🔧 Tools & Software Used

* ANSYS Fluent (for CFD simulation)
* ANSYS Mechanical (for static structural analysis)
* ANSYS Meshing
* Post-processing tools for contour and graph visualization

---

## 📌 Project Objectives

* Analyze the aerodynamic behavior of NACA 2412 airfoil under steady airflow.
* Determine lift and drag forces acting on the airfoil.
* Study the airflow behavior using velocity and pressure contours.
* Evaluate the stress and deformation of the airfoil under aerodynamic loading.

---

## 🌀 CFD Simulation Details

* **Airfoil:** NACA 2412
* **Flow Type:** Steady, incompressible external flow
* **Turbulence Model:** k-ω SST
* **Boundary Conditions:**

  * Inlet: Velocity Inlet
  * Outlet: Pressure Outlet
  * Airfoil: No-slip wall
* **Monitored Outputs:**

  * Lift Coefficient (Cl), Drag Coefficient (Cd)
  * Scaled residuals for convergence
  * Contour plots (velocity & static pressure)

---

## 🧱 Structural Analysis

* **Objective:** Evaluate stress and deformation due to aerodynamic pressure distribution
* **Loading:** Imported pressure distribution from CFD results
* **Output:** Total deformation, von Mises stress

---

## 📊 Results Overview

* Lift and drag coefficients obtained across multiple iterations.
* Pressure and velocity contour plots show smooth airflow with expected pressure drop across the surface.
* Structural analysis confirms that the airfoil remains within safe deformation and stress limits under load.

---

## ✅ Conclusion

The project successfully demonstrates both aerodynamic and structural performance of the NACA 2412 airfoil using simulation tools. This type of analysis is essential in optimizing airfoil design for real-world applications.
