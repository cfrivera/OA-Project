## Twitter Customer Support Dataset Anlyasis

I will be analyzing the _Customer Support on Twitter_ dataset that contains tweets, replies, and author IDs of both companies and inquiring users. The customer support is facilitated by chatbots, and this dataset will reveal inights on the language used, traffic stats on an anual and weekly level, and top users to name a few.

This dataset contains 2,811,774 rows and 7 variables.

### Column/Variable Descriptions

> **‘tweet_id’**: Identifies the tweet, and is the ‘in_response_tweet_id’ that the user is replying to. <br>

> **‘author_id’**: Contains the author of the tweet. The company account name will be shown, but all other non-company-users are referenced by an ID number. <br>

> **‘inbound’**: A boolean value that determines who is reaching out to the company account. If TRUE, then the customer is reaching out and tagging the company account. If FALSE, then the company account is replying/tagging the customer. <br>

> **‘created_at’**: Date and time of when the tweet was sent. <br>

> **‘text’**: Contains the actual message contents of the tweet. <br>

> **‘response_tweet_id’**: References the tweet_id that it is replying to. <br>

> **‘in_response_to_tweet_id’**: An id to be referenced when this tweet is being replied to. <br>
