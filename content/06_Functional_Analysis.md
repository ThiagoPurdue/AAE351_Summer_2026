# Functional Analysis

## 6.1 The Transition from "What" to "How"
Before physical components (like a motor or a wing) are designed, systems engineers must understand the *functions* those components will perform. Functional Analysis is the process of translating system requirements into a logical architecture. It describes what the system must do, without yet specifying what physical parts will do it.

## 6.2 Functional Decomposition and IDEF0
The top-level function of our system might be "Transport Cargo." Functional decomposition breaks this down into sub-functions:
1. Provide Lift
2. Provide Thrust
3. Store Energy
4. Navigate
5. Communicate

Engineers often use **IDEF0 (Integration Definition for Function Modeling)** diagrams. These diagrams map out the Inputs, Controls, Outputs, and Mechanisms (ICOM) for each function. For instance, the "Provide Thrust" function takes electrical power (Input) and a throttle signal (Control) to produce thrust (Output) using a motor and propeller (Mechanism).

## 6.3 Functional Allocation
Once the functional hierarchy is complete, functions are allocated to physical subsystems. This matrix mapping ensures that every physical component has a purpose (it performs a function) and every necessary function is physically realized.

## System Integration
Functional decomposition of the RCUAV forces us to break down 'Deliver Cargo' into sub-functions like 'Generate Lift', 'Provide Thrust', and 'Maintain Structural Integrity'. In System Composer, these functions must be modeled logically before they are allocated to specific physical components, ensuring that the 3D-printed airframe adequately supports all avionics and payloads.
