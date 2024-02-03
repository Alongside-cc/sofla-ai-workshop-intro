---
marp: true
 theme: custom-dave
 class: invert
 footer: 'LI: davidcobb'
---

# AI Workshop
# - South Florida, Feb 2024
## David Cobb, Azure MCT


## Find all resources at:
## https://aiworkshop.info/


<button onclick="document.querySelectorAll('section').forEach((e) => e.classList.toggle('invert'))">Toggle appearance</button>

---


# First, thank you!

### Thank you to Damian Montero & all the volunteers of these amazing South Florida Meetups!


- Florida JS 
- Florida.Net
- Microsoft Cloud South Florida
- AI ChatGPT for Business

## And Happy Birthday Damian! 🎂
---



## David's background

- Nearly 30 years in I.T.
- MCT since 2002 teaching SQL Server
- Working my own business last four years teaching & consulting on Azure development, data, admin & security
- Multiple Azure certs including AI-102

---

# AI Prompt Engineering Expert? 😅

- Fascinated by AI since ChatGPT 3.5 release
  
- In 2024 I'm exploring and guiding folks toward the most useful **Azure AI** resources.
  
---


# Goals for Workshop

- Play, make mistakes, have fun
- Learn from each other & share what you know.
- Discuss community possibilities for AI in 2024, like the [Global AI Bootcamp](https://globalai.community/bootcamp)


---


# Agenda

- Looking ahead to upcoming AI community learning opportunities
- BRIEF presentation: **'Learn how to use OpenAI models using prompt engineering'**
- Jump into OpenAI Playground
- Networking & discussions

---

# Looking Ahead

## Join our email list to be notified for dates & details in March 2024 for the [Global AI Bootcamp](https://globalai.community/bootcamp)

---

# Azure OpenAI Technologies of Interest in 2024

## [Semantic Kernel](https://learn.microsoft.com/en-us/semantic-kernel/overview/)

## [Prompt Flow](https://learn.microsoft.com/en-us/azure/ai-studio/how-to/prompt-flow)

## [Copilot Studio](https://learn.microsoft.com/en-us/microsoft-copilot-studio/fundamentals-get-started?tabs=web)

---
## Presentation:
[Learn how to use OpenAI models using prompt engineering](https://docs.google.com/presentation/d/12PlwRj_HyTucpfRUwe6mEf7pN6nXSe8NvZoKBNNDEEo/edit#slide=id.p1)


---

Misc

OpenAI function example, search_hotel

```
[  
    {
        "name": "search_hotels",
        "description": "Retrieves hotels from the search index based on the parameters provided",
        "parameters": {
            "type": "object",
            "properties": {
                "location": {
                    "type": "string",
                    "description": "The location of the hotel (i.e. Seattle)"
                },
                "max_price": {
                    "type": "number",
                    "description": "The maximum price for the hotel"
                },
                "features": {
                    "type": "string",
                    "description": "A comma separated list of features (i.e. beachfront, free wifi, etc.)"
                }
            },
            "required": ["location"]
        }
    }
]  