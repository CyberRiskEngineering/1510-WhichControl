# 1510-WhichControl
Which Control do I need? - Building Fit for Purpose Control Environments

Synopsis

Spreadsheet to support one-way sensitivity analysis of the impact of changes in security controls on overall risk level of the organization

Motivation

The objective of the project is to allow optimal selection of the security controls required to meet the risk appetite of an organization.

Default example is using the ISF IRAM2 list of threats and controls as a starting point. Users can customise those list as well as others parameters to match the characteristics of an organization.

Installation

Notes: Edit only the cells marked as blue or green

A. Threat and control rating
1. Select ‘Controls_Threats’ workbook
2. Rank the threats in column D from 0 to 10
3. Assign control criticality against the threat in columns F-AH

B. Sensitivity Analysis
1. Set the base control efficiency rate for each control in row 4 [ex. 0.5]
2. Repeat the following for each control
a. Change control efficiency value to upper bound rate [ex. 0.8]
b. Record the value in control efficiency upper bound field (row 5)
c. Change control efficiency value to lower bound value [ex. 0.2]
d. Record the value in control efficiency lower bound field (row 6)
e. Change the control efficiency rate back to base [ex. 0.5]
