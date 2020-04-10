<h1>Epidemic Simulator</h1>

<h3>WARNING: This program is not a reliable source of epidemiological information.</h3>

<h4>Description:</h4>
<p>Simulates a disease spreading through a community in random motion. Individuals are represented as points undergoing independent random walks in a bounded 2D environment. Parameters include: the population size, the average population density, the number of times to evolve the system, the number of trials to conduct, and the fraction of the available space that individuals will traverse each timestep (which amounts to their speed). After a randomly-chosen period of time within a given range, infected individuals either recover or die. The probability of death varies by age group:</p>
<p>

- <a href="https://www.worldometers.info/coronavirus/coronavirus-age-sex-demographics">https://worldometers.info/coronavirus/coronavirus-age-sex-demographics</a> (estimated probability of death if infected, by age)</p>
<p>

- <a href="https://newyork.areaconnect.com/statistics.htm">https://newyork.areaconnect.com/statistics.htm</a> (age distribution for New York City)</p>
  
 
<a href="https://colab.research.google.com/github/brayvid/EpidemicSimulator/blob/master/epidemic_simulator.ipynb">Open in Colaboratory Playground</a>

<h4>Outputs:</h4>
<p>
  
- One CSV file containing the expected population breakdown by category (Susceptible, Infected, Recovered, Deceased) at each timestep, as well as the observed reproduction number for that timestep.</p>

<p>

- One PNG file with two figures: a stackplot depicting the expected state of the population at each timestep, and a graph of the expected rate of change of infections (with error bounds of $\pm$ one standard deviation).<p>

<h4>Usage:</h4>
<p>
  
1. Save your own copy of this notebook to your Google Drive (once in the Colab environment) by selecting File (next to Colab logo at top left) --> Save a copy in Drive.</p>

<p>
  
2. In the top right corner of the new window that appears, click Connect to allocate some of Google's computing resources.</p>

<p>
  
3. Edit the parameters in the section called User Inputs below if desired.</p>

<p>
  
4. Select Runtime (to the right of File) --> Run all.</p>

<p>
  
5. Repeat steps 3 and 4 as desired.</p>
