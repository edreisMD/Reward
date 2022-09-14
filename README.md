# Reward

###
Starting a library to make it easy for AI to get feedback. Starting with text and images.

### Motivation

After the open release of stable diffusion I realised how AI will proliferate fast, and I noticed how badly the systems were collecting feedback to improve the models towards what we want them to do. And most of the time, no feedback were being collected at all. Therefore, its is not even possible to know if the models were behaving like expected or in a good manner. That may be ok for picture generations, but it can become tricky soon when these models start to actually act in the world.

Some features of the large self supervised models (LM) makes it more challenging to know if they are doing what is expected from them, than the previous supervised learning (SL) models for two reasons: 1. SL models are trained on the specific task we expected it to perform later, while LM are trained on a different task, and sometimes a different data from the downstream task. It is a good thing, to use different tasks to leverage intelligence, at the same time it makes it more challenging to understanding what we are feeding the AI with; 2. SL models usually performs objective tasks (because it required objective metrics to train the model), SSL are particularly good at more subjective tasks, because it can be trained for an objective objective task (like predict next bit, or next word), but than performs a much more subjective task, like generating new content.
