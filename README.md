# Sentiment Neuron

<a href='https://modeldepot.io/afowler/sentiment-neuron/overview'> 
  <img src='https://img.shields.io/badge/ModelDepot-Pre--trained_Model-3d9aff.svg'/>
</a>
 
 <a href='https://modeldepot.io/afowler/sentiment-neuron/overview'> 
  <img src='https://img.shields.io/badge/Downloads-194-green.svg'/>
 </a>

## Description
Detect a person's sentiment in text using Unsupervised Sentiment Neuron, a model trained on 82 million Amazon reviews. It's able to predict sentiment by taking in a string, and outputting the sentiment value from -1 to 1. The full text of the review is used to detect sentiment, so even if the sentiment switches mid-text, it'll still be detected.

**Possible Use Cases**
1. Process tweets or comments to see what positive or negative things people are saying about your product.
2. Quickly filter survey results to pick the most positive or negative feedback
3. Process transcripts to understand how someone is feeling throughout a conversation.

# Examples

Input Text | Sentiment Output (From -1 to 1) | Good or Bad (As an Example) |
--- |   --- | --- |
the food was hot and the service was fast! | 0.5305157 | 👍 |
worst thing ever, i hate everything about this, will return immediately | -1.6204989 | 👎 |

### Keep 👀 reading 👀 to see how to get these results!

# How Good is This Model?

This model has been trained on 82 million Amazon reviews, taking 1 month across 4 GPUs. As with any ML model, the underlying training corpus will affect how effective this model will be in your specific use case, but the model is relatively generalizable outside of reviews. It achieves near state of the art performance, with only 7.7% error, whereas the [state of the art](https://arxiv.org/abs/1605.07725) achieves 5.91% accuracy on the IMDB sentiment dataset.
