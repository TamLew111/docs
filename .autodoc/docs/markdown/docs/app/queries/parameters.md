[View code on GitHub](https://dune.com/docs/app/queries/parameters.md)

# Parameters

This technical guide covers the use of parameters in the Dune app. Parameters are a feature that allows users to implement variables in certain parts of their Query code. This variable can be changed from dashboards, making it possible to create interactive dashboards. Parameters are defined in the Query code as `{{parametername}}` and will appear below the Query and in any dashboards in which a Query Visualization with parameters is used in. 

The guide explains how to use parameters in Queries and dashboards. It also provides an example Query that returns the running total of Gas Paid in USD. The Query Author has included a parameter for `wallet address`, `start date`, and `end date`. The guide also provides examples of dashboards that use parameters. 

The guide explains how to add a parameter to Queries by writing `{{parametername}}` or using the button below the Query. Users can edit the properties of single parameters by clicking on the gear wheel next to the parameter in the Query editor. This allows them to set a default value, define a list of possible parameters, or change the type of the parameter. If users want to share parameters between different Queries on a dashboard, they must ensure that they exactly match in regards to name, type, and default value.

Parameters allow users to make a certain part of their SQL query dynamic and thereby offer them to make Queries and dashboards interactive. That way, they can easily display detailed data on their dashboard since it allows the viewer to customize the dashboard for their needs. Parameters are like filters, but the possibilities of using this feature go beyond that.

In summary, this guide covers the use of parameters in the Dune app. It explains what parameters are, how to use them in Queries and dashboards, and provides examples of Queries and dashboards that use parameters.
## Questions: 
 1. What is the purpose of Parameters in Dune Docs?
- Parameters are a feature in Dune Docs that allow for the implementation of variables in certain parts of Query code, which can be changed from dashboards and allow for an interactive dashboard.

2. How do you use Parameters in Dune Docs?
- Parameters can be added to Queries by writing `{{parametername}}` or using the button below the Query. The properties of single parameters can be edited by clicking on the gear wheel next to the parameter in the Query editor.

3. Can Parameters be shared between different Queries in a Dashboard?
- Yes, Parameters in a Dashboard can be shared between different Queries, as long as they have the same name, type, and default value.