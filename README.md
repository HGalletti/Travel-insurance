# Travel-insurance

About Dataset

A third-party travel insurance servicing company that is based in Singapore.

The attributes:

    Target: Claim Status (Claim.Status)
    Name of agency (Agency)
    Type of travel insurance agencies (Agency.Type)
    Distribution channel of travel insurance agencies (Distribution.Channel)
    Name of the travel insurance products (Product.Name)
    Duration of travel (Duration)
    Destination of travel (Destination)
    Amount of sales of travel insurance policies (Net.Sales)
    Commission received for travel insurance agency (Commission)
    Gender of insured (Gender)
    Age of insured (Age)

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 14477 entries, 0 to 14476
Data columns (total 11 columns):
 #   Column                Non-Null Count  Dtype  
---  ------                --------------  -----  
 0   Agency                14477 non-null  object 
 1   Agency Type           14477 non-null  object 
 2   Distribution Channel  14477 non-null  object 
 3   Product Name          14477 non-null  object 
 4   Claim                 14476 non-null  object 
 5   Duration              14476 non-null  float64
 6   Destination           14476 non-null  object 
 7   Net Sales             14476 non-null  float64
 8   Commision (in value)  14476 non-null  float64
 9   Gender                2882 non-null   object 
 10  Age                   14476 non-null  float64
dtypes: float64(4), object(7)
memory usage: 1.2+ MB

Describe:

 	Duration 	Net Sales 	Commision (in value) 	Age
count 	14476.000000 	14476.000000 	14476.000000 	14476.000000
mean 	47.311965 	35.769415 	6.932587 	39.987773
std 	115.161854 	39.543367 	15.318593 	13.675971
min 	0.000000 	-291.750000 	0.000000 	3.000000
25% 	10.000000 	18.000000 	0.000000 	36.000000
50% 	23.000000 	25.000000 	0.000000 	36.000000
75% 	55.000000 	42.000000 	7.700000 	42.000000
max 	4881.000000 	810.000000 	283.500000 	118.000000


- An additional sales date column was created. This column was randomly generated (using several normal distributions added together, so as to simulate seasonality).
