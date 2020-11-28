# ElectricityGridDemandSimulationModel
This is the repository for the ElectricityGridDemandSimulationModel project.

## Objective
Create a simulation model to produce simulated projections/forecasts for the electricity grid. 

## Overview
Electricity grids are being disrupted by new technology. This is occurring on the back of a mega-trend known as the Electrification of Everything. Is it real or is it just hype? Who knows? All I know is that forecasting the demand for grid-delivered electricity is becoming complex. Regular timeseries that we traditionally relied on to forecast the future are changing rapidly.

In part, this is due to adoption of intermittent electricity generation technology (e.g. solar photovoltaic electricity generation systems). Let's call these systems Solar PV. Solar PV systems vary output by the amount of sunlight that is available. If there were no clouds, this would be easy to forecast. However, partly cloudy skies over an electricity grid with a massive installed base of solar PV creates a ripple effect in real power flows through the grid.

There are also other complications related to the way owners of Solar PV use the systems. In short, some kind of regulation and/or control of Solar PV is required to manage the grid. Identifying and establishing controls of Solar PV is a core part of how this simulation model will be used.

However, there are many other factors that impact on this core objective. Here are a few examples (think of them as symptoms of an economic disease):
- Solar PV is widely adopted in Australia as a response to rapid escalation in electricity tariffs. So the underlying motivation has been to reduce electricity bills.
- Much of Australia, especially capital cities, continue to grow in size. This imposes rising costs on existing users where they are paying a cross-subsidy to new customers.
- Economies of scale and density have a big impact on the unit cost of supplying electricity. Low density housing and hollowed out industrial areas means unit cost is escalating quickly.

There are multiple feedback loops underlying this particular economic disease which tend to cause it to spread - a bit like an epidemic. What should we call this disease? maybe Electro Cost Shifting - ECS for short.

So, a big part of this project will be developing causal models of such dynamics and then tracing through the model results to determine how these dynamics impact on grid-delivered electricity. We will start simply and try to establish a clear, transparent logic that others can follow. Hopefully, this will turn into a useful decision making tool for grid planners everywhere.
