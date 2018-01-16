# Financial-Behaviour

This is a small descsriptive analysis of the first set of kids who will be test users of the Dojo platform. This is a picture of their financial habits before getting and engaging with the application.

The original size of the dataset was n=604 transactions nested under 35 accounts. However, only 31 of those accounts actually had any transactional data, bringing the total sample down to 31 accounts. As described in the notebook, upon removal of 3 accounts for various reasons (one was clearly not a kid, the other two were extreme savings outliers) we are left with a final sample of n=533 transactions nested under 28 accounts.

Within the dataset, as I got it, there is really only one two useful elements for each transaction: (a) a credit/debit labeler that tells me whether the transaction was a deposit or a withdrawal, and (b) the actual transaction amounts. As such, I just did a series of descriptive analysis to explore and display the ratio of earning versus saving within the limited number of accounts that I had.
