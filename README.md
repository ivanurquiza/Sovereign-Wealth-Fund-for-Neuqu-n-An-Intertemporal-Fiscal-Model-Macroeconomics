# 💰📈 Sovereign Wealth Fund for Neuquén  

Project developed for the **Macroeconometrics course (M.A. in Economics, Universidad de San Andrés, 2025)**, taught by *Federico Sturzenegger* and *Javier García-Cicco*.  
We evaluated how Neuquén could design a sovereign wealth fund to smooth public spending financed by volatile hydrocarbon royalties from *Vaca Muerta*.  

## Goals
We study the design of a **sovereign wealth fund** to manage oil & gas royalties through intertemporal fiscal optimization, focusing on consumption smoothing and precautionary savings.  

## Methods
- **Dynamic programming** with a Bellman equation under CRRA preferences.  
- **Value function iteration** to solve for optimal savings and consumption policies.  
- **Stochastic income process** for royalties, comparing mean-reverting vs. Hotelling price dynamics.  
- **Simulation of trajectories** for consumption, sovereign fund accumulation, and per capita transfers.  

## Our results
- Optimal policy involves high saving rates early on, building up the fund.  
- Public spending stabilized over time, even after resource depletion.  
- Hotelling price dynamics generate faster accumulation and higher long-run consumption.  
- Clear policy trade-off: Alaska-style per capita transfers vs. Norway-style fiscal rule.  

Implemented in `fulmi.ipynb`, we worked with a Value function iteration and forward simulations under different price scenarios.  

## References
Gourinchas, P.-O., & Parker, J. A. (2002). *Consumption over the Life Cycle*. Econometrica.  
Sturzenegger, F., & Werneck, R. (2006). *Fiscal federalism and procyclical spending*.  
IMF & SP Global datasets on hydrocarbon markets.  
INDEC (2023). *Censo*.  

