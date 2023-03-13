# Investigation of prosper.com loan data
## by S. Huff


## Dataset

The Prosper loan dataset contains 113937 loans with 81 features on each one like "IncomeRange", "CreditGrade", and "LoanOriginalAmount" collected from the platform prosper.com. I copied the dataset and removed a few columns which seem not necessary for me. I also renamed one column, because of easier to handle. Then I turned the "IncomeRange" into categorical ordinal data. After an investigation of the completeness of the data, and checking for missing values, I regarded the dataset as good as is with no need for further wrangling.

## Summary of Findings

I am interested in what the data holds for marketing-, and communication-strategy because this is my professional background. Comparable small amounts are borrowed on prosper.com (median $6500). Mostly for "debt consolidation".(Not for fulfilling consumeristic desires.)

The users on prosper.com are more wealthy than the US average in terms of income. (prosper.com mean: 5608 per month = 67296 p.A. / US mean: 54.000 p.A). 

In absolute values, most loans are created in California. However related to the loans to state-inhabitants ratio, the Destrict of Columbia has by far the most borrowers. All in all, prosper.com reaches in no state over 0.0006 which is far below 1%. 

The occupations of the borrowers are very broad. Including "Truckers", "Scientists", "Judges" and many more. The first place is the profession "Others" and the second place is "Professional". This does not provide any value. However "Computer Programmer" is the first concrete profession, shared by around 14.000 people.

The most important reason for borrowing money is debt consolidation. But when segmenting the "Loan original amount" into 5000 ranges like "$0 - 5000", "$5000 - 10.000" until "$30.000 - 35.000" the picture is different: Within the range of "$0 - 5000" "Home Improvement" is the most important reason for borrowing money. "Auto" is in the range "$5000 - 10000", "Home Improvement" again in the range from "$10000 - 15000". 

Higher income is related to "debt consolidation" as a reason for borrowing money. Whereas "Auto" and "Home Improvement" are important for all income ranges. There is no alarming relation between the reasons people borrow money and loan status. For: "People who borrow money for Auto default more often than others." 

When it comes to occupations judges borrow the most money (around $15000), followed by pharmacists (around $ 14000).

The debt-to-income ratio of all occupations seems surprisingly low – related to the mean which is around 0.3. This is one-third of the yearly income and proves responsible money management. (Depending on some other factors). However, in nearly every occupation are outliers who have 10 times more debt than income. People working in Civil Service, Medical Technicians, Police Officers, Attorneys, Military Enlisted, and Engineers seem to behave more "responsible" in financial belongings than other people.

"Self-employed" people seem to spend more on "Wedding loans" than others. "Not employed" people have the largest span of Loan amount when it comes to "Engagement Rings". Employed people are borrowing money mostly for "Baby & Adoption". 

People owning a home borrow money for debt consolidation and Baby & Adoption. This seems reasonable because they built their "nest". People with no home are borrowing the largest amount for "Boat".


## Key Insights for Presentation

When it comes to communication it is important to note, that people using prosper.com seem to be financially literate (higher than average income) and most importantly reasonable debt-to-income ratio. However, prosper.com is used only by a tiny fraction of the population (< 1%) with most borrowers situated in the District of Columbia. Interestingly the reason to borrow money relates to the borrower amount which I explored in 5000 steps. There are a few professions that are more responsible when it comes to financing than others. All in all these findings could frame a first step for a communication strategy. 

