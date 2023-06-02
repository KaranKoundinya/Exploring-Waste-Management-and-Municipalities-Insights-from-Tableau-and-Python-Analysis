# Exploring-Waste-Management-and-Municipalities-Insights-from-Tableau-and-Python-Analysis

Each row in Municipalities.csv corresponds to information about a municipality in a certain
country. Relevant information about data variables is given below:
tc Waste management cost per capita
area km2
pop population
pden population density (people per km2)
wden waste per km2
urb urbanization index (1 low, 3 high)
paper average percentage of paper in waste
glass average percentage of glass in waste
metal average percentage of metal in waste
plastic average percentage of plastic in waste
msw_so Municipal solid waste that is sorted by waste type (kg)
msw_un Municipal solid waste that is unsorted (Kg)
msw Total Municipal solid waste (kg)
sor Percentage share of sorted waste
geo Geographical region (1 South, 2 Center, 3 North)
roads Km of roads within the municipality
s_wteregio Share of solid waste sent to Waste-to-Energy plants - regional figure
(municipalities are within regions)
s_landfill share of solid waste sent to landfills - regional figure (municipalities are within
regions) 


Q1) Using Tableau, visually explore the relationship between each factor and ‘waste
management cost per capita’. What are your insights? 

Q2) Using Python, visually explore whether there are distinct clusters of municipalities based
on waste produced in them and their urbanization index? Try this using dimensionality
reduction techniques of PCA and UMAP. Which technique works better and why? If distinct
clusters are visible, what does that mean? If not, what does that mean? 
