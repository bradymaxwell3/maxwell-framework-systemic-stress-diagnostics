# Inflection Point Detector (IPD)

The IPD identifies emerging regime transitions using multi‑signal convergence.

## Inputs
- LST acceleration  
- Envelope breaches  
- Cross‑domain correlation spikes  
- Damping failures  
- Volatility clustering  

## Conditions
An inflection point is flagged when:
- Three or more signals converge within a short window  
- Damping effectiveness drops  
- Envelope breaches persist  

## Output
- IPD status (Off / Watch / Active)  
- Triggering signals  
- Confidence level  
