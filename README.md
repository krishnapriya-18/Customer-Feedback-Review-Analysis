# Customer-Feedback-Review-Analysis

AIM:

- Built a sentiment analysis tool to assess and analyze large volumes of customer
feedback, and help prioritize areas for improvement for Happay.
- The same tool can be used for analyzing competitor’s customer feedback.
- Reveal insights on what Happay should focus on as well as our competitor's
(Concur, Expensify etc) weakness which can lead to better marketing pitch of our
product.

PROCESS:

- Build a workflow and test the prototype on various natural language processing techniques
and see which performs best.
- The prototype was created using a natural language processing technique called
Word2vec. It is a shallow, two-layer neural network that is trained to reconstruct linguistic
contexts of words.

PROBLEMS:

- Customer Feedback Data was not
available.
- Web Scraping official API’s provided
limited data access and only if you
are a developer of that application or
owner of the product.
- Labelled positive and negative review
data for training the model was not
available.

SOLUTIONS:

- Web Scraping of reviews.
- Built a Dynamic Web Scraper for
google play store, G2 Crowd, Apple
app store and Capterra.
- Two approaches:
1) Downloaded labelled data available for
research purposes of various products
like amazon cell phone, electronics
reviews, Myntra product reviews etc and
combined them to build a robust model.
2) Label dataset for 2000 travel and
expense reviews manually and use them
for predictions for other data which will
get better with time.

