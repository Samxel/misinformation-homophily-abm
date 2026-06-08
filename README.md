# Misinformation Homophily Agent Based Model

Agent-based simulation studying how ingroup bias affects the spread of misinformation across population groups.

## Research Question
Does ingroup bias slow down the spread of misinformation across a population and at what bias level does it stay confined to a single group?

## Model
- SIS spreading model combined with group dynamics.<br>
- Agents belong to one of two groups and are less likely to accept misinformation from out-group neighbors (bias parameter β).<br>
- Two network types are compared: random (Erdős–Rényi) and small-world (Watts–Strogatz).

## Setup
```bash
pip install -r requirements.txt
```

## Papers
1. Yavaş & Yücel (2013) - "Impact of Homophily on Diffusion Dynamics Over Social Networks"
2. Furutani et al. (2023) - "Analysis of Homophily Effects on Information Diffusion on Social Networks"
3. Liu et al. (2019) - "Homophily on Social Networks Changes Evolutionary Advantage in Competitive Information Diffusion"
4. Watts & Strogatz (1998) - "Collective Dynamics of 'Small-World' Networks"
