All contributions are welcome!

- Submit them through issues or pull request.
- Try to contribute one service at a time to allow easy review and merging.
- Search for existing issues and pull requests to avoid duplicates.
- Do not forget to update the table of content.
- Order services alphabetically.
- Follow the following template when submitting a new service.

# Template

### [Service name]

[Link to relevant page (product description/pricing)](#)

- *Free tier*: [free tier description]
- *Pros*: [basic review, interesting features, anything non obvious... avoid copying service description]
- *Limitations*: [specific limitations important to know (exceeding the free tier is not a limitation!)]
- *Exceeding the free tier*: [what happens when exceeding the free tier (API return an error, need to pay, informed by email, etc), in order to anticipate eventual migration]

# Rules

## Service selection

As a rule of thumb free tiers too limited should be excluded. The idea is that a developer should be able to use the free tier without being forced to switch to another service or do a lot of modification to continue using the service. 

That is why free tiers limited in time should be excluded. Some exception could be made, I did one for AWS EC2 considering the duration of the free tier and the popularity of the service.

## Service description

**Free tier description**

The free tier description should reflect what is offered in the free tier, not the limitations. Also, try to avoid copying marketing description of the service especially if it is very specific or fancy, like "2 awesome Super.io boxes", if it means "2 build agents".

**Limitations**

Any limitation that is not critical* should be stated in the *Limitations* section of each service. A limitation should be understood as something which is not directly part of the free tier description but important to know. For example, "100Mb bucket for free" should be part of the free tier description and not the limitations section.

###### \* Because a critical limitation may exclude the service from this list.

A good example could be:
- *Free tier*: 100MB storage per project, 1GB bandwidth/month, 2 build agents
- *Pros*: nice interface, automated notifications pushed to GitHub, reactive support
- *Limitations*: limit of 5 projects maximum, no SSL for the free tier, deployment to hosting provider limited to AWS and Google Cloud
- *Exceeding the free tier*: service continues to work and a sale representative contacts the user
