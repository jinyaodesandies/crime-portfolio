---
layout: writeup
title: "Incarceration in Florida"
project_number: "Project 2"
project_class: "project-incarceration"
dashboard_id: "dashboard-2"
description: "Full written analysis of incarceration patterns in Florida, including county-level variation, corrections policy, and imprisonment trends."
---

# Incarceration in Florida

## Write-Up
The data used for this project is sourced from the 2025 Vera Institute of Justice
Incarceration Trends data set. Although last updated in May 2025, the most up to date data
extends from 1988 to 2019, the most recent year all data was collected. The data was in the form
of a csv, with each row being an observation of a county’s various measures over a quarter of a
year in the time frame. The observations were utilized to create three figures and two tools. The
first and second figure are maps with color describing the rate of incarceration for prison and jail,
respectively, while the third is an area chart that describes incarceration data by county over
time. The interactive tools allowed for highlighting of different levels of urbanicity as well as for
specific counties to be searched.

Prison refers to state or federal facilities holding convicted criminals for long periods
(BJS, 2023). Prison Population Rate per 100,000 (2019) utilizes the prison_pop_rate measure
on the downloaded csv, which combined with the county name dimension was used to create a
colored map. The density of color represents number of prisoners per 100,000 residents of the
county. The use of per 100,000 is significant because it allows for the incarceration trends to be
compared with understanding that each county had varying levels of density. The prison
population rate in most Florida counties is broadly on par to the national average of 435, with
outliers such as the densest Baker County having over 4 times as many. According to Bartos and
Kubrin (2018), decreasing the severity of punishment did not significantly increase property
crime rates. Florida’s large prison population therefore may manifest the phenomenon of
resource overallocation, asmore than socially optimal are held given the cost of running prisons.
Similarly, the density of color in the jail map represents the number of Floridians in jail
per 100,000, the measure jail_pop_rate also being directly sourced from in the Vera Dataset and
organized by county. Jail differs from prison in being temporary holding of individuals without
specific indictments (BJS, 2023). Florida jail population rates are also on par with the US
average, with exceptionally large outliers like Baker County existing because of large
immigration facilities holding undocumented immigrants. For example, the county with most
jailed people per 100,000 is County, which also has one of the largest immigration detention
facilities in the United States (Henrichson, 2018). Florida’s large jail population may also be an
explanatory factor to its large number of convicted and imprisoned criminals. According to the
Vera Institute, a few days in jail can drive harsher sentences, reduce economic viability, teach
future criminal behavior, and worsen detainee mental health. That makes jail a “gateway to
deeper and more lasting involvement in the criminal justice system” (Subramanian et al., 2015).
Thus, Florida’s large jail population is likely a driver in its large and rising overall incarcerated
population.

The Area Chart The Great Depression and Incarcerated Population by County effectively
captures this recent rise. The area chart combines the prison_pop_rate and jail_pop_rate fields
with year records to describe a striking increase in state incarceration. The tooltip also uses an
extra calculated field to represent the total incarcerated population in the state during the year. Q
Pew report describes a nationally decrease in incarceration trend. Florida’s rising number of
prisoners was despite bipartisan legislation aimed at decreasing the incarcerated population
across the county because of the low benefit and high cost of prisons (Pew, 2017)(Gramlich,
2021). Neither was Florida’s prison and jail population significantly impacted by economic
recessions like the great recession, which the reference band shows. Instead, evidence points to
private prison construction. In theory, new private detention facilities may be driving an increase
in sentencing, which in turn drives more prison construction, creating a negative feedback loop
increasing prison population. This hypothesis is confirmed by a study which found that along
with private prison construction there was a moderate increase in sentencing length (Dippel &
Poyker, 2019). The rampant construction of private prisons in Florida at the time may have
contributed to this rise in incarceration that is visible in the graph, especially when isolating
counties like Baker County, where there were private detention facility construction projects
(Equal Justice Initiative, 2018).

Furthermore, a urbanicity selector was created to sort through the different levels of
density in counties. It is observable that dense counties had a lower per 100,000 incarceration
rates than rural ones, likely not only because urban areas are denser but because it is cheaper and
more politically strategic to open prisons in sparse areas. Prisons can often become profit drivers,
commodifying human suffering for small gains in employment and supposed economic
revitalization (Vera Institute, 2017). The dashboard also includes a county search tool, allowing
for specific counties to be searched and highlighted in the area chart and maps.

In conclusion, in most counties Florida’s jail and prison population was comparable to the
national average. For outliers, the high number in prisons may be driven by a similarly high jail
population, whether because of the jail’s inherent role as a pre-prison processing center the
externality its supply creates as a gateway to serious crime. Other potential factors include the
rampant construction of private prisons in the state, which circa 2017 aligns well with a spike in
the state’s incarceration rates. Lastly, certain counties have exceptionally high density in part
because of large immigration facilities. These outliers are likely harmful for the state: housing
more than the optimal number of inmates incurs deadweight loss to society and may increase
crime instead.

## Citations

<div class="citations-section">

Bartos, B. J., & Kubrin, C. E. (2018). Can We Downsize Our Prisons and Jails Without
Compromising Public Safety? Criminology & Public Policy, 17(3), 693–715.
https://doi.org/10.1111/1745-9133.12378
BJS. (2019). Correctional Populations in the United States, 2019 – Statistical Tables. BJS; US
Gov. https://bjs.ojp.gov/media/64696/download
BJS. (2023). Correctional institutions. Bureau of Justice Statistics.
https://bjs.ojp.gov/topics/corrections/correctional-institutions
Dippel, C., & Poyker, M. (2019). NBER WORKING PAPER SERIES DO PRIVATE PRISONS
AFFECT CRIMINAL SENTENCING?
https://www.nber.org/system/files/working_papers/w25715/w25715.pdf
Equal Justice Initiative. (2018, August 8). Private Prison Population Skyrockets. Equal Justice
Initiative. https://eji.org/news/private-prison-population-skyrockets/
Henrichson, C. (2018). Expanding our Knowledge on Local Incarceration Trends. Vera Institute
of Justice. https://www.vera.org/news/expanding-our-knowledge-on-local-incarceration-
trends#post2
OPPAGA. (2019). Diverting Low-Risk Offenders from Florida Prisons. Fl.gov.
https://oppaga.fl.gov/Products/ReportDetail?rn=19-01
Subramanian, R., Delaney, R., Roberts, S., Fishman, N., & Mcgarry, P. (2015). Incarceration’s
Front Door: The Misuse of Jails in America.
https://www.safetyandjusticechallenge.org/wp-content/uploads/2015/01/incarcerations-
front-door-report.pdf
Vera Institute. (2017, January). Why Are There So Many People in Jail in Scranton, PA? Vera
Institute of Justice. https://www.vera.org/in-our-backyards-stories/why-are-there-so-
many-people-in-jail-in-scranton-pa
Vera Institute. (2025). GitHub - vera-institute/incarceration-trends: Incarceration Trends
Dataset and Documentation. GitHub. https://github.com/vera-institute/incarceration-
trends/tree/main

</div>