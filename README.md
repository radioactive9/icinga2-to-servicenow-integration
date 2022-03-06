# icinga2-to-servicenow-integration
Outbound Integration from ICINGA2 to Servicenow - Python
The below python code helps in creating a connection between icinga2 and servicenow. There is a connector available out of box in servicenow. But there are lot of downside to it that I have seen. The major one being it doesn't understand the Hard and Soft State. 
Using the connector ServiceNow just pulls all alerts and the great feature of icinga is not being used at all. 
The whole purpose is to give more control to ICINGA rather than giving more control to ServiceNow and use only the incident creation module in servicenow
I am no python coder - but just trying to make my hands dirty. Any changes in code a welcome
