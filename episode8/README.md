# Episode 8: Implementing custom actions with backend integrations, forms and fallback

---
## What's in this episode?

In this episode we:
- updated the NLU data of our assistant by adding more training examples, implementing regex features and synonyms
- updated the custom action with real world backend integrations
- implemented form action
- added TwoStageFallbackPolicy

## How do I use this directory?
Train the assistant using the command:  
`rasa train`

Test the assistant using the command:  
`rasa run actions & rasa shell`

## What do you need to follow this episode?

This episode requires you to have Rasa installed on your machine:  
```pip3 install rasa-x --extra-index-url https://pypi.rasa.com/simple```

In addition to this you need to install additional dependency to run Rasa on Jupyter 
notebooks:  
```pip install nest_asyncio```
