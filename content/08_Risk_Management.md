# Risk Management

## 8.1 Defining Engineering Risk
In systems engineering, Risk is not just an abstract fear of failure; it is a quantifiable metric. Risk is calculated as:
$$ Risk = Likelihood 	imes Consequence $$
A highly likely event that causes minor inconvenience (e.g., a scratch on the paint) is a low risk. A highly unlikely event that causes catastrophic failure (e.g., wing separation in flight) is a severe risk.

## 8.2 Failure Mode and Effects Analysis (FMEA)
FMEA is a bottom-up reliability methodology. Engineers look at every single component in the system and ask:
1. How can this component fail? (Failure Mode)
2. What is the cause of this failure?
3. What is the effect on the overall system? (Effects Analysis)

Once identified, mitigation strategies must be implemented. Mitigations can reduce the likelihood of the failure (e.g., using thicker material) or reduce the consequence (e.g., adding a redundant backup system).

## 8.3 The Risk Matrix
Risks are tracked visually on a Risk Matrix (often a 5x5 grid of Likelihood vs. Consequence). The goal of the systems engineering team is to implement mitigations that drive all risks out of the "Red" (unacceptable) zones into the "Green" or "Yellow" (acceptable/monitor) zones before Critical Design Review (CDR).

## System Integration
Risk management for a 3D-printed UAV involves unique failure modes not seen in traditional aerospace design. Risks such as layer delamination, warping during the print process, or material degradation under UV exposure must be identified early. These risks will be formally tracked and mitigated through your System Composer architecture and FMEA tables.
