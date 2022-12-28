Analysis of titanic dataset

<class 'pandas.core.frame.DataFrame'>
RangeIndex: 891 entries, 0 to 890
Data columns (total 12 columns):
 #   Column       Non-Null Count  Dtype  
---  ------       --------------  -----  
 0   PassengerId  891 non-null    int64  
 1   Survived     891 non-null    int64  
 2   Pclass       891 non-null    int64  
 3   Name         891 non-null    object 
 4   Sex          891 non-null    int64  
 5   Age          714 non-null    float64
 6   SibSp        891 non-null    int64  
 7   Parch        891 non-null    int64  
 8   Ticket       891 non-null    object 
 9   Fare         891 non-null    float64
 10  Cabin        204 non-null    object 
 11  Embarked     889 non-null    object 
dtypes: float64(2), int64(6), object(4)
memory usage: 83.7+ KB

Percentage of people survived : 38.38383838383838
Percentage of people not survived : 61.61616161616161

Percentage of people in Pclass 1 : 24.242424242424242
Percentage of people in Pclass 2 : 20.65095398428732
Percentage of people in Pclass 3 : 55.106621773288445


PCLASS 1
Number of people survived in Pclass 1 : 136
Number of people CANNOT survived in Pclass 1 : 80

PCLASS 2
Number of people survived in Pclass 2 : 87
Number of people CANNOT survived in Pclass 2 : 97

PCLASS 3
Number of people survived in Pclass 3 : 119
Number of people CANNOT survived in Pclass 3 : 372


People of Pclass 1 survived most i.e 136 people. Total passengers on titanic were 342.
Total percentage of passengers survived from Pclass 1 : 15.26374859708193
Total percentage of passengers survived from Pclass 2 : 9.764309764309765
Total percentage of passengers survived from Pclass 3 : 13.35578002244669

Survival -: Pclass 1>3>2



Pclass 1
Percentage of Male passengers in Pclass 1 : 56.481481481481474
Percentage of Female passengers in Pclass 1 : 43.51851851851852

Pclass 2
Percentage of Male passengers in Pclass 2 : 58.69565217391305
Percentage of Female passengers in Pclass 1 : 41.30434782608695

Pclass 3
Percentage of Male passengers in Pclass 1 : 70.67209775967413
Percentage of Female passengers in Pclass 1 : 29.327902240325866




Percentage of Male passengers on ship : 64.75869809203144
Percentage of Female passengers on ship : 35.24130190796858

Percentage of Male passengers survived : 12.2334455667789
Percentage of Female passengers survived : 26.15039281705948


Maximum passengers between 20-30