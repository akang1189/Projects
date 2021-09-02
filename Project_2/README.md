# Project 2 - Ames Housing Data and Kaggle Challenge

Problem Statement

Housing prices have skyrocketed to all time highs in most recent years, is that a good thing? What is causing this and why? Are we destined to repeat the 2007 housing market crash? Or is it different this time around?

We wish to look at the factors driving these record home prices to see if they are caused by short term inputs such as the current state of interest rates or even the price of lumber. We will decide on our investments based on future prediction of these home prices


| feature | dype |Description
| --- | --- | --- |
| MS SubClass | int64 |
| MS Zoning | object |Identifies the general zoning classification of the sale.
| Lot Frontage | float64 |Linear feet of street connected to property
| Lot Area | int64 |Lot size in square feet
| Street | object |Type of road access to property
| Lot Shape | object |General shape of property
| Land Contour | object |Flatness of the property
| Neighborhood | object |Physical locations within Ames city limits
| Condition 1 | object |Proximity to main road or railroad
| Condition 2 | object |Proximity to main road or railroad (if a second is present)
| Bldg Type | object |Type of dwelling
| House Style | object |Style of dwelling
| Overall Qual | int64 |Overall material and finish quality
| Overall Cond | int64 |Overall condition rating
10 Very Excellent
| Year Built | int64 |Original construction date
| Year Remod/Add | int64 |Remodel date (same as construction date if no remodeling or additions)
| Roof Style | object |Type of roof
Flat Flat
| Roof Matl | object |Roof material
| Exterior 1st | object |Exterior covering on house
| Exterior 2nd | object |Exterior covering on house (if more than one material)
| Mas Vnr Type | object |Masonry veneer type
| Mas Vnr Area | float64 |Masonry veneer area in square feet
| Exter Qual | object |Exterior material quality
| Exter Cond | object |Present condition of the material on the exterior
| Foundation | object |Type of foundation
| Bsmt Qual | object |Height of the basement
| Bsmt Cond | object |General condition of the basement
| Bsmt Exposure | object |Walkout or garden level basement walls
| BsmtFin Type 1 | object | Quality of basement finished area
| BsmtFin Type 2 | object |Quality of second finished area (if present)
| Total Bsmt SF | float64 |Total square feet of basement area
| Heating | object |Type of heating
| Heating QC | object |Heating quality and condition
| Central Air | object |Central air conditioning
| Electrical | object |Electrical system
| Gr Liv Area | int64 |Above grade (ground) living area square feet
| Bsmt Full Bath | float64 |Basement full bathrooms
| Bsmt Half Bath | float64 |Basement half bathrooms
| Full Bath | int64 |Full bathrooms above grade
| Half Bath | int64 |Half baths above grade
| Bedroom AbvGr | int64 |Number of bedrooms above basement level
| Kitchen AbvGr | int64 |Number of kitchens
| Kitchen Qual | object |Kitchen quality
| TotRms AbvGrd | int64 |Total rooms above grade (does not include bathrooms)
| Functional | object |Home functionality rating
| Fireplaces | int64 |Number of fireplaces
| Fireplace Qu | object |Fireplace quality
| Garage Type | object |Garage location
| Garage Yr Blt | float64 |Year garage was built
| Garage Finish | object |Interior finish of the garage Fin Finished
| Garage Cars | float64 |Size of garage in car capacity
| Garage Area | float64 |Size of garage in square feet
| Garage Qual | object |Garage quality
| Garage Cond | object |Garage condition
| Paved Drive | object |Paved driveway
| Wood Deck SF | int64 |Wood deck area in square feet
| Open Porch SF | int64 |Open porch area in square feet
| Enclosed Porch | int64 |Enclosed porch area in square feet
| 3Ssn Porch | int64 |Three season porch area in square feet
| Screen Porch | int64 |Screen porch area in square feet
| Pool Area | int64 |Pool area in square feet
| Mo Sold | int64 |Month Sold
| Yr Sold | int64 |Year Sold
| Sale Type | object |Type of sale
| SalePrice | int64 | the property's sale price in dollars

Conclusions and Recommendations 

Based on our analyzed data findings, we can determine and test the factors most likely to impact the Sales Price. Square footage(total), number rooms/bathrooms, upgraded amenities, quality and add-ons such as AC, Garages and fireplaces have shown to have the most significant impact. 

Normal predictors for home prices show the market is being impacted by other external factors. Factors such as tax cuts, recent stimuli, limited supply and the pandemic have exacerbated the underlying issue. While these factors differ from the 2007-8 Housing crash, similarities are obvious…. But more research is needed.