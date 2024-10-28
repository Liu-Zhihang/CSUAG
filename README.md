# CSDAG
This repository contains the code and data for the paper *"Fear is Polar? A Complex Network Analysis of Media Fear Appeal and Public Sentiment Transition Related to Long-COVID"*.

- **ABM.ipynb**: Implements the agent-based model (ABM) used in the paper, detailing the computational processes outlined in the manuscript.
- **Text_mining.ipynb**: Contains code for text processing and sentiment analysis.
- **Prediction.ipynb**: Includes the training and prediction code for modeling the transitions in node states.
- **Plot.ipynb**: Provides code for visualizing the results of the model simulations.

### Key Figures:

1. **CSDAG Framework**  
   Our proposed framework for health communication models various groups of agents on multi-layer networks.  
   ![CSDAG Framework](./graph/CSDAG.tif)

2. **Network Evolution**  
   The simulation results show the evolution of node states over time.  
   ![Network Evolution](./graph/network_evolution.png)

3. **Model Performance**  
   The method effectively captures the temporal dynamics of node states.  
   - Sentiment and metric trends:  
     ![Metric and Sentiment Trends](./graph/metric+sentiment_lines.png)
   - Media metrics and risk assessment:  
     ![Media Metric and Risk Trends](./graph/media_metric_risk_lines.png)
   - Parameter distribution with mean and 3SE bars:  
     ![Parameter Distribution](./graph/parameter_distribution_with_mean_and_3se_bars.png)
