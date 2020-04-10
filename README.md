<h1>Epidemic Simulator</h1>

<h3>WARNING: This program is not a reliable source of epidemiological information.</h3>

<h4>Description:</h4>
<p>Simulates a disease spreading through a community in random motion. Individuals are represented as points undergoing independent random walks in a bounded 2D environment. Parameters include: the population size, the average population density, the number of times to evolve the system, the number of trials to conduct, and the fraction of the available space that individuals will traverse each timestep (which amounts to their speed). After a randomly-chosen period of time within a given range, infected individuals either recover or die. The probability of death varies by age group:</p>
<p>

- <a href="https://www.worldometers.info/coronavirus/coronavirus-age-sex-demographics">https://worldometers.info/coronavirus/coronavirus-age-sex-demographics</a> (estimated probability of death if infected, by age)</p>
<p>

- <a href="https://newyork.areaconnect.com/statistics.htm">https://newyork.areaconnect.com/statistics.htm</a> (age distribution for New York City)</p>
  
 
<a href="https://colab.research.google.com/github/brayvid/EpidemicSimulator/blob/master/epidemic_simulator.ipynb">Open in Colaboratory Playground</a>
