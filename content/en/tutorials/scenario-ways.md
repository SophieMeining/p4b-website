---
title: Scenarios - Ways
permalink: "/tutorials/scenario-ways/"
weight: 30
sections:
- training

---
#### Description of the feature

GOAT allows you to develop your own scenarios, such as network modifications or building a new bridge. The developed scenario can be added to the current network, and changes in accessibility can be evaluated using isochrones.

#### Possible use cases (planning questions)

* How does the construction of a new bicycle bridge across the river change accessibility?
* How does accessibility with a wheelchair change with the construction of a barrier-free road?
* Which option of a new cycle path will serve the highest number of residents?

#### Step-by-step tutorial for the exemplary planning task

##### 1 Scenario for a new bicycle bridge

###### 1.1 Planning question

How does the construction of a new bicycle bridge across the river change accessibility?

###### 1.2 Step-by-Step guide

1. Go to the menu for scenario development and create a new scenario.

<img src="/images/training_materials/Scenario_POIs/create_scenario.webp"  alt="Create scenario" style="max-height:150px;"/>

2. Give the scenario a name and click on "OK".

<img src="/images/training_materials/Scenario_building/name_scenario.webp"  alt="Name scenario" style="max-height:200px;"/>

3. Select which layer you want to edit, in this case the "Ways" Layer.

<img src="/images/training_materials/Scenario_building/scenario_ways.webp"  alt="Edit ways" style="max-height:300px;"/>

4. Zoom to the place where you want to build a new bicycle bridge and select the surrounding road network using the circle tool.

<img src="/images/training_materials/Scenario_building/circle_scenario.webp"  alt="Circle toot" style="max-height:300px;"/>

5. Draw a new route connection at the desired location, select "Bridge" as the route type and click on "Save". The drawn paths are now listed in the table on the right. In order to integrate these paths into the database, you have to click on the "Upload" button.

<img src="/images/training_materials/Scenario_building/bridge_building.webp"  alt="Draw" style="max-height:300px;"/>

6. Now you can analyze the effect of the new route connection on accessibility by calculating the standard and scenario isochrones. To do this, select the routing mode "Bike" and set the calculation mode to "Comparison." You have the option to set the travel time, driving speed and the number of calculated isochrones.

<img src="/images/training_materials/Scenario_building/comparison.webp"  alt="Comparison" style="max-height:400px;"/>

7. Place the starting point for the isochrone calculation near the new bridge. As a result, the isochrone in the starting position is displayed in red and the isochrone taking into account the new route connection is displayed in green.

![](/images/training_materials/Scenario_building/result-isochrone.webp)