This is an archive of my undergraduate thesis on Archimedes screw turbine optimization - 2024

<img src="docs/20230906_174334.jpg" width="20%">

---

### Abstract
The increasing need for sustainable energy solutions makes microhydro systems, specifically the Archimedes Screw Turbine (AST), a viable option for low-head sites due to its environmental suitability and ease of operation. To improve its performance, this study explores the comparative effectiveness of two optimization methods: Analysis of Variance (ANOVA) and Genetic Algorithm (GA). Experimental tests were conducted on single and double screw turbines with varying head (0.7-1.0 m) and flow rate (106-1035 l/min). ANOVA was used to evaluate the statistical significance and interaction between parameters on efficiency, while GA was applied to determine the optimal configuration that maximizes turbine output. Results showed that screw type and flow rate had a highly significant effect on turbine efficiency (p < 0.001), while head variation showed no significant effect. The GA successfully identified the optimal configuration at a head of 0.95 m and a flow rate of 814.8 l/min with a double screw, resulting in a mechanical power of 99.35 W with an efficiency of 78.73%. These findings suggest that statistical and evolutionary optimization methods can complement each other in evaluating and improving AST performance. The novelty of this study lies in the integrative approach of comparing ANOVA and GA in one experimental framework for screw turbine optimization, which can serve as a strong reference for future micro-hydro designs. Further research is recommended to evaluate a wider range of parameters as well as real-time application of adaptive control systems in the field.

---

## Analysis

### Statistical Analysis

The statistical analysis isolates the primary determinants of turbine efficiency. The ANOVA results demonstrate that flow rate and screw type are highly significant, while hydraulic head has negligible impact at this specific scale.

![](docs/Plot_Anova_FR.png)

*Figure 2: Correlation between flow rate and mechanical efficiency.*
<br><br>

![](docs/Plot_Anova_ST.png)

*Figure 3: Correlation between single vs. double screw configurations and efficiency.*
<br><br>


### Evolutionary Optimization
A Genetic Algorithm (GA) optimization was conducted to navigate search spaces and maximize mechanical efficiency based on the experimental data.

![](docs/Plot_GA.png)

*Figure 4: Genetic Algorithm convergence plot showing the optimal configuration variables across generations.*
