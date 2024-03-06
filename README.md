# playing-around-with-gemini-ai-api
Wanted to move from OpenAi API to `gemini-pro` AI API. That's why I started to playing around with it to see how it goes with my need. So far I'm very pleased. 

## Downside
The only downside is JSON object generation by the model. `gemini-pro` generates parsable JSON string inside markdown syntax. Probably in training, it sees a lot JSON data in markdown documentation. So it respond with it. JSON generation was a bit problem in OpenAI too. But with some checks, validations or rerequesting, those can be overcome. Basically we are in the bleeding edge of AI era and AIs are still learning and improving ...fast.
