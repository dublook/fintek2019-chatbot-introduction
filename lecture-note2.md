# Chat Bot Introduction 2 (Oct 15, 2019) by Futami

## My mission at these 2 weeks (again)

👇👇👇👇👇<br>
**Put your ideas into acutual solution/product**<br>
👆👆👆👆👆<br>

## Today's menu
1. Why you should learn programming?
2. Develop simple actual chat bot (rule based)
3. [for S Grade] Integrate NLP, ML (how to handle natural language?)

## ⚠️
**All setentences below are just Futami's opinion, off course**


# 1. Why you should (or must) learn programming?

## I don't know: what's your motivation for this lecture?
### Just to pass
![alt](https://images.unsplash.com/photo-1558956035-bb61915a3e86?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1650&q=80)

### Jump to actual business world
![alt](https://images.unsplash.com/photo-1531879251-3da65dd78c99?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=934&q=80)

### My Strong recommend: Start to learn programming from this course
And make chat bot app by yourself!


## I know...
- Almost of you are not going to be an engineer
- You do not have enough time to learn new things
- It's hard to learn


## Making a app experience will help you in future
- Especially you are interested in fintech


## Some stories (based on my current situation)

### Mr. M
- My classmate in Kaji semi.
- Now working in one of biggest bank in Japan
- Now running projects that will replace some jobs with software robots

### Mr. G
- My other classmate in Kaji semi.
- After Keio economics,
- Got master degree of machine learning at Tokyo Institute of Technology
- Worked in Bank of Japan as a research (using machine learning skills)


### Mr. N
- My other classmate in Kaji semi.
- Data analitics, product owner in some big company
- And, running his own company for blockchain wallet, games

## Some news
### "Shrinking to survive: Japan's banks face a quiet crisis"
[![Image from Gyazo](https://i.gyazo.com/21c1c654962ea1b5acdd1fbb31027f19.jpg)](https://gyazo.com/21c1c654962ea1b5acdd1fbb31027f19)
![alt](https://www.ft.com/__origami/service/image/v2/images/raw/https%3A%2F%2Fs3-ap-northeast-1.amazonaws.com%2Fpsh-ex-ftnikkei-3937bb4%2Fimages%2F_aliases%2Flarge_580%2F5%2F9%2F4%2F5%2F13025495-1-eng-GB%2F20180222BOJbignumber2.png?source=nar-cms)
Source: https://asia.nikkei.com/Spotlight/Cover-Story/Shrinking-to-survive-Japan-s-banks-face-a-quiet-crisis

### Lack of engineer will continue to increase
[![Image from Gyazo](https://i.gyazo.com/40743d452ba8225ca7200e874303e7d2.png)](https://gyazo.com/40743d452ba8225ca7200e874303e7d2)

Source: Ministry of Economy, Trade and Industry (経済産業省)
https://www.meti.go.jp/press/2017/08/20170821001/20170821001-1.pdf


### Revenue per Employee (Financial vs IT)
![alt](https://2oqz471sa19h3vbwa53m33yj-wpengine.netdna-ssl.com/wp-content/uploads/2017/06/revenue-per-employee-sector.jpg)


### Why Silicon Valley Is Eating Bankers' Lunch
> Jamie Dimon, CEO, JPMorgan Chase: “When I go to Silicon Valley … [they all] want to eat our lunch.”

Source: https://minutehack.com/opinions/why-silicon-valley-is-eating-bankers-lunch


### G7 vs Facebook's Libra
[![Image from Gyazo](https://i.gyazo.com/cb9c0f07aad5ff19e951eb258fe52357.png)](https://gyazo.com/cb9c0f07aad5ff19e951eb258fe52357)
Source: https://www.wired.co.uk/article/wired-awake-141019

## Some stories of me
### This lesson
- At first, I thought it was voluteer, but I get paid🤑🤑🤑🤑🤑
  - Who wants to pay for engeeners? And what is his/her purpose?
- Why FinTEK has rich web site? http://fintek.keio.ac.jp/en/about-activities

### Working with 'Big 4' accounting company
- Due to their lack of engineers and speed for developing apps

## Conclusion of stories
### Trends
- Improvement of technology allows to earn with less employees
- One employee in big IT companies earn more than financial sectors
  - They have enough capital to invest in huge scale (maybe larger than financial sectors)
- Big IT companies seem to "eat banks lunch" and some conflicts have been happened between those
- Financial companies are thinking to shrink to keep profit/competitive
- Financial sectors started to focus on technologies
  - To make new business
  - To "shape up"
- Demand gap for tech employees will be growing
- Engineers are tend to avoid traditional companies due to culture
- It's not easy for financial sectors to hire tech employees
- Indivual's careers are becoming mixture of tech and financial

### That's why this lesson has sponsors, I guess
- Their feel: 😰

## My Strong recommend: Start to learn programming from this course
- Diffucult to make your career competitive ONLY with financial skills
- Still rare if you have both tech and financial skills
- Best way to learn technology is making an app by yourself
  - Not just reading books!

# 2. Develop simple actual chat bot (rule based)

## Roles in a team for making new service
- BizDev
  - Take a role on making business
  - Making business plan, negotiating with partners or investors... (not strict defined)
- Product manager
  - Take a role on product/service
  - Decide roadmap of product, decide which feature must be added first...
- Project manager / Agile master
  - Take a role on productivity of team
  - Manage deadlines, members' motivation, improving productivities...
- UX Designer / Researcher
  - Take a role on bride between user needs and product
  - Interview with users, making a prototype
- Engineer
  - Making apps/service and delivering to users
- Sales & Marketing
  - Take a role on expanding a product to users


## Azure Bot Service

https://azure.microsoft.com/en-us/services/bot-service/

### What's rule based
```
if user say "hello" then
  do blah blah
```

# [for S Grade] Integrate NLP, ML (how to handle natural language?)
## Azure Bot Service: Natural language understanding
https://www.youtube.com/watch?v=jlmSzFGtdTo

https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-howto-v4-luis?view=azure-bot-service-4.0&tabs=csharp

https://docs.microsoft.com/en-us/azure/bot-service/bot-builder-dialog-manage-complex-conversation-flow?view=azure-bot-service-4.0&tabs=javascript

## Making Natural Language Processing by yourself
### Word2Vec with AWS SageMaker
https://github.com/awslabs/amazon-sagemaker-examples/blob/master/introduction_to_amazon_algorithms/blazingtext_word2vec_text8/blazingtext_word2vec_text8.ipynb
