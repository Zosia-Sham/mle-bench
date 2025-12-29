# Data card

The dataset contains conversational interactions where a single prompt is answered by two different large language models.

For each interaction, the data includes the prompt text, the two generated responses, and a labeled outcome indicating whether response A, response B, or a tie was preferred by a human judge.

The training set includes model identities and preference labels, while the test set includes only prompts and responses.

All data originates from real user interactions collected on the Chatbot Arena platform.


# Metric

LogLoss

# Description

The task is to predict which of two chatbot responses a user prefers in a head-to-head comparison, or whether the user considers them equally good, based on the given prompt and responses.
