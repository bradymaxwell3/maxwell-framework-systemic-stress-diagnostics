# Live Stress Tape (LST) Logic

The LST aggregates domain inputs into a single rolling stress measure.

## Inputs
- Energy slack  
- Fiscal slack  
- NPDI  
- Liquidity conditions  
- Production signals  
- Volatility measures  

## Normalization
Each input is normalized to a 0–1 stress scale using domain‑specific transforms.

## Propagation
The propagation engine applies:
- Cross‑domain coupling coefficients  
- Rhizome damping  
- Shock‑absorption factors  

## Aggregation
The LST is computed as a weighted, damped composite of all normalized inputs.

## Output
- Current LST value  
- Rolling trend  
- Envelope position  
