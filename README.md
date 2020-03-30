# COVID19
 
The New York Times is releasing a series of data files with cumulative counts of coronavirus cases in the United States, at the state and county level, over time. We are compiling this time series data from state and local governments and health departments in an attempt to provide a complete record of the ongoing outbreak.

Since late January, The Times has tracked cases of coronavirus in real time as they were identified after testing. Because 
of the widespread shortage of testing, however, the data is necessarily limited in the picture it presents of the outbreak.

We have used this data to power our maps and reporting tracking the outbreak, and it is now being made available to the 
public in response to requests from researchers, scientists and government officials who would like access to the data 
to better understand the outbreak.

The data begins with the first reported coronavirus case in Washington State on Jan. 21, 2020. We will publish regular 
updates to the data in this repository.

United States Data
Data on cumulative coronavirus cases and deaths can be found in two files for states and counties.

Each row of data reports cumulative counts based on our best reporting up to the moment we publish an update. We do our 
best to revise earlier entries in the data when we receive new information.

State-Level Data
State-level data can be found in the states.csv file.

date,state,fips,cases,deaths
2020-01-21,Washington,53,1,0
...
County-Level Data
County-level data can be found in the counties.csv file. For counties, we provide a FIPS code.

date,county,state,fips,cases,deaths
2020-01-21,Snohomish,Washington,53061,1,0
...
In some cases, the geographies where cases are reported do not map to standard county boundaries. See the list of 
geographic exceptions for more detail on these.

Methodology and Definitions
The data is the product of dozens of journalists working across several time zones to monitor news conferences, analyze
data releases and seek clarification from public officials on how they categorize cases.

It is also a response to a fragmented American public health system in which overwhelmed public servants at the state, 
county and territorial level have sometimes struggled to report information accurately, consistently and speedily. 
On several occasions, officials have corrected information hours or days after first reporting it. At times, cases 
have disappeared from a local government database, or officials have moved a patient first identified in one state or 
county to another, often with no explanation. In those instances, which have become more common as the number of cases 
has grown, our team has made every effort to update the data to reflect the most current, accurate information while
ensuring that every known case is counted.

When the information is available, we count patients where they are being treated, not necessarily where they live.

In most instances, the process of recording cases has been straightforward. But because of the patchwork of reporting 
methods for this data across more than 50 state and territorial governments and hundreds of local health departments, 
our journalists sometimes had to make difficult interpretations about how to count and record cases.

For those reasons, our data will in some cases not exactly match with the information reported by states and counties. 
Those differences include these cases: When the federal government arranged flights to the United States for Americans 
exposed to the coronavirus in China and Japan, our team recorded those cases in the states where the patients subsequently
were treated, even though local health departments generally did not. When a resident of Florida died in Los Angeles, 
we recorded her death as having occurred in California rather than Florida, though officials in Florida counted her case 
in their own records. And when officials in some states reported new cases without immediately identifying where the
patients were being treated, we attempted to add information about their locations later, once it became available.

Confirmed Cases
Confirmed cases are patients who test positive for the coronavirus. We consider a case confirmed when it is reported by 
a federal, state, territorial or local government agency.

Dates
For each date, we show the cumulative number of confirmed cases and deaths as reported that day in that county or state. 
All cases and deaths are counted on the date they are first announced.

Counties
In some instances, we report data from multiple counties or other non-county geographies as a single county. For instance,
we report a single value for New York City, comprising the cases for New York, Kings, Queens, Bronx and Richmond Counties.
In these instances the FIPS code field will be empty. (We may assign FIPS codes to these geographies in the future.)
See the list of geographic exceptions.

Cities like St. Louis and Baltimore that are administered separately from an adjacent county of the same name are counted 
separately.

“Unknown” Counties
Many state health departments choose to report cases separately when the patient’s county of residence is unknown or 
pending determination. In these instances, we record the county name as “Unknown.” As more information about these cases
becomes available, the cumulative number of cases in “Unknown” counties may fluctuate.

Sometimes, cases are first reported in one county and then moved to another county. As a result, the cumulative number 
of cases may change for a given county.

Geographic Exceptions
New York City
All cases for the five boroughs of New York City (New York, Kings, Queens, Bronx and Richmond counties) are assigned 
to a single area called New York City.

Kansas City, Mo.
Four counties (Cass, Clay, Jackson and Platte) overlap the municipality of Kansas City, Mo. The cases and deaths that 
we show for these four counties are only for the portions exclusive of Kansas City. Cases and deaths for Kansas City 
are reported as their own line.

Joplin, Mo.
Joplin is reported separately from Jasper and Newton Counties.

Chicago
All cases and deaths for Chicago are reported as part of Cook County.

License and Attribution
In general, we are making this data publicly available for broad, noncommercial public use including by medical 
and public health researchers, policymakers, analysts and local news media.

If you use this data, you must attribute it to “The New York Times” in any publication. If you would like a more 
expanded description of the data, you could say “Data from The New York Times, based on reports from state and local 
health agencies.”

If you use it in an online presentation, we would appreciate it if you would link to our U.S. tracking page at 
https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html.

If you use this data, please let us know at covid-data@nytimes.com and indicate if you would be willing to talk to 
a reporter about your research.

See our LICENSE for the full terms of use for this data.

Contact Us
If you have questions about the data or licensing conditions, please contact us at:

covid-data@nytimes.com

Contributors
Mitch Smith, Karen Yourish, Sarah Almukhtar, Keith Collins, Danielle Ivory and Amy Harmon have been leading our U.S. 
data collection efforts.

Data has also been compiled by Jordan Allen, Jeff Arnold, Aliza Aufrichtig, Mike Baker, Matthew Bloch, 
Nicholas Bogel-Burroughs, Maddie Burakoff, Christopher Calabrese, Andrew Chavez, Robert Chiarito, Carmen Cincotti, 
Alastair Coote, Matt Craig, John Eligon, Tiff Fehr, Andrew Fischer, Matt Furber, Rich Harris, Lauryn Higgins, 
Jake Holland, Will Houp, Jon Huang, Danya Issawi, Jacob LaGesse, Patricia Mazzei, Allison McCann, Jesse McKinley, 
Miles McKinley, Sarah Mervosh, Andrea Michelson, Blacki Migliozzi, Steven Moity, Richard A. Oppel Jr., Jugal K. Patel,
Nina Pavlich, Azi Paybarah, Sean Plambeck, Scott Reinhard, Thomas Rivas, Michael Robles, Alison Saldanha, Alex Schwartz,
Libby Seline, Shelly Seroussi, Rachel Shorey, Anjali Singhvi, Charlie Smart, Ben Smithgall, Steven Speicher, 
Michael Strickland, Albert Sun, Tracey Tully, Maura Turcotte, Miles Watkins, Jeremy White, Josh Williams and Jin Wu.