All contributions are welcome!

- Submit them through pull requests (not accepting issues).
- Try to contribute one service at a time to allow easy review and merging.
- Search for existing issues and pull requests to avoid duplicates.
- Do not forget to update the table of content.
- Order services alphabetically.
- Follow the following template when submitting a new service.

# Template

### [Service name]

[Link to relevant page (product description/pricing)](#)

- *Free tier*: should reflect what is offered in the free tier, not the limitations. Also, try to avoid copying marketing description of the service especially if it is very specific or fancy, like "2 awesome Super.io boxes", if it means "2 build agents"
- *Pros*: basic review, interesting features, anything non obvious... avoid copying the service description.
- *Limitations*: specific limitations important to know (exceeding the free tier is not a limitation!), like an instance sleeping for 30 minutes every day. 
- *Exceeding the free tier*: what happens when exceeding the free tier: API returns an error, a payment method needs to be added, an email is sent.
- *Credit card required*: this is optional. You can answer "yes" or "no", or provide more information if it's relevant.

**Example**:
  
    ### AWS Cool product
    
    [Pricing page](#)
    
    - *Free tier*: 100MB storage per project, 1GB bandwidth/month, 2 build agents
    - *Pros*: nice interface, automated notifications pushed to GitHub, reactive support
    - *Limitations*: limited to 5 projects, no SSL for the free tier, automated deployment limited to provider X
    - *Exceeding the free tier*: service continues to work and a sale representative contacts the user
    - *Credit card required*: No

# Services selection

The purpose of this project is to list services with free tiers that can be used in production for application hosting. The free tier should be usable for small projects without cost. Services that are too limited in functionalities or that are limited in time shouldn't be listed.

The list is not limited to hosting providers. It can include any service that can be useful for production applications, like databases, email services, monitoring tools, data APIs (e.g. currency or geocoding), etc. 

However, the list should not include services that are not actively used in production applications, like development tools, code editors, design tools, etc. 

Personal or hobby projects shouldn't be listed either. We aim to list services that will be around for a some time. 