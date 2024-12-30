# Causality-between-support-and-depression

untitled is the tweet collection and scrapping, initial insights
This code generated DB that was passed through the bert model code to generate labels
after labelling we did the required support mapping into C/T and computed the ATE
We then Matched the code using propensity score matching and recalculated the ATE


Conclusion:

We proposed two new metrics, ’Support’ and ’Score,’ with
’Support’ based on the tweet’s engagement and ’Score’ based
on the difference between the percentage of depressive tweets
from an individual user after the intervention and the percentage of depressive tweets from an individual user before
the intervention.
• We used the variables to estimate the outcome effect and the
Average Treatment Effect (ATE) and used various matching
methods such as Propensity Score Matching, Mahalanobis
Distance Matching, and Nearest Neighbor Matching.
After completing the aforementioned tasks, we believe we gained
a better understanding of the causal relationships between users
and their behavior on the social media platforms Twitter.
One of the limitations of our work is that we have done our
analysis on a fairly smaller dataset, we believe we would be able
to get better insight and understanding on the causal relationships
between the behavior of the user on twitter and the support that
they get when they tweet. Sentiment analysis is also a fairly young
research topic so getting the perfect labels is always a problem as
our classifier cannot detect sarcasm and humor. Another limitation
could based on the training dataset we used for training our classifier, we assume that the dataset is accurate, which might not be
the case as many times people in social media hence we are bound
to missclassify some of those as depressive without context, so if
there’s any historically backed data where we are able to know
that the person is depressive and their tweets are depressive and
not sarcastic in nature, but this would possibly violate the privacy
rights of the individual.
There are other methods that can be used to get causal inference,
such as using structured causal learning, which can also provide
us insights on the causal relationships between variables and the
outcome.
More matching techniques can also be implemented to asses the
result


Through the results of our experiments, we have shown how a
collection of behavioral markers that appear on social media may
be used to forecast postings that are suggestive of depression and, in
turn, comprehend widespread depressive tendencies in populations.
These estimates of depression can occasionally be used through
our work and related research to assist early detection and prompt
treatment of depression
