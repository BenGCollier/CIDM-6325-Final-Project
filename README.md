# Guide to Book Topics for Final Project (Baseline, Good, Better, Best)

***NOTE***: Updated 11/10/2024 
Finalized for Fall 2024.  

***NOTE***: You **MUST** document and identify which of the Good, Better, Best features you are using in your project in your project's readme.

## How to use this List

I have classified the learning objectives from Antonio's book according to the following scheme.  Each category is relative to the following requirements for your final project:

* You must implement *all* **Baseline** components - Gets you to 70% of the value
* You will implement *at least* four **Good** components - Gets you to 80% of the vaue
* You will implement *at least* two **Better** components - Gets you to 85% of the value
* You will implement *at least* one **Best** components - Gets you to 90% of the value

Where is the remaining 10%? It comes from the synthesis and service to your implementation approach.

* **Baseline**: Essential Django knowledge that must be demonstrated in your final project
* **Good**: Fundamental knowledge that sets up a more useful app
* **Better**: Approaching a higher degree of robustness
* **Best**: Approaching professional-grade features and tools

NOTE: The chapter references indicate which chapter the technique is originally introduced.  I am interested in your ability to demonstrate the technique, not that you'll use it EXACTLY like it is used where/when it is introduced.

Topic                                       | Baseline  | Good  | Better  | Best
---                                         | ---       | ---   | ---     | ---
***Chapter 1***                             |           |       |         |
Create Project and Apps                     | x         |       |         |
Creating models                             | x         |       |         |
Django Migrations                           | x         |       |         |
Configuring models for the Django Admin     | x         |       |         |
Queries and Querysets                       | x         |       |         |
Function-Based Views and Templates          | x         |       |         |
WOrking with URLs                           | x         |       |         |
***Chapter 2***                             |           |       |         |
Canonical Urls for SEO                      | x         |       |         |
Pagination                                  | x         |       |         |
Class-Based Views                           |           | x     |         |
Sending email (internal in console)         | x         |       |         |
Sending email (with 3rd party)              |           |       | x       |
One-to-Many Model Relationships             | x         |       |         |
***Chapter 3***                             |           |       |         | 
Django Taggit for Categorization            | x         |       |         |
Aggregate model quiries                     | x         |       |         |
Django Template Language                    | x         |       |         |
Custom template tags                        |           | x     |         |
Custom template filters                     |           | x     |         |
Sitemap                                     |           | x     |         |
Site feeds                                  |           | x     |         |
Postgres                                    |           | x     |         |
Postgres Full-text search                   |           |       |         | x
***Chapter 4***                             |           |       |         |
Django authentication framework             | x         |       |         |
Django Admin                                | x         |       |         |
Django Admin manage users                   | x         |       |         | 
Django Auth User Profile                    | x         |       |         | 
Customize Admin interface                   | x         |       |         | 
Customize ModelAdmin classes                | x         |       |         |
Media file uploads                          | x         |       |         |
Authentication decorators                   | x         |       |         |
***Chapter 5***                             |           |       |         |
Messages framework                          |           |       | x       |
Use front-end framework (bootstrap)         |           | x     |         |
Custom auth backend                         |           |       |         | x
Social Authentication                       |           |       |         | x
https                                       | x         |       |         |
***Chapter 6***                             |           |       |         |
Many-to-Many Model Relationships            | x         |       |         |
Django Forms Classes                        | x         |       |         |
Django ModelForm Class                      | x         |       |         |
Form data validation and retreival          | x         |       |         |
Front-end JavaScript (see note A below)     | x         |       |         | 
***Chapter 7***                             |           |       |         |
Activity Streams                            |           |       | x       |
Advanced QuerySet operations                |           | x     |         |
Django Signals                              |           |       | x       |
Django Debug Toolbar                        | x         |       |         | 
Redis                                       |           |       | x       | 
***Chapter 8***                             |           |       |         |
Pillow Image processing                     |           | x     |         |
Django Sessions                             |           | x     |         |
Custom context processors                   |           | x     |         |
Django and RabbitMQ/Celery/Flower           |           |       |         | x
***Chapter 9***                             |           |       |         |
Stripe Payments                             |           |       | x       |
Webhook Handlers                            |           |       | x       |
CSV export                                  |           | x     |         |
Add custom view to admin interface          |           | x     |         |
PDF Generation                              |           |       |         | x
Send PDFs via Email (external)              |           |       |         | x
***Chapter 10***                            |           |       |         |
Recommender Engine with redis               |           |       |         | x
***Chapter 11***                            |           |       |         | 
Internationalization (I18N)                 |           |       | x       |
Code translation                            |           |       | x       |
Template translation                        |           |       | x       |
Rosetta                                     |           |       | x       |
Model translation with `django-parler`      |           |       | x       |
Localization with `django-localflavor`      |           |       | x       |
***Chapter 12***                            |           |       |         |
Fixtures                                    |           | x     |         |
Model Inheritance                           | x         |       |         |
Authentication and Authorization            | x         |       |         |
Custom Model Fields                         |           | x     |         |
***Chapter 13***                            |           |       |         |
Content Management System                   | x         |       |         |
HTML5 drag and drop                         |           |       | x       |
HTML5 sortable                              |           |       | x       |
Neapolitan for CRUD Views                   |           |       |         | x
Django Formset                              | x         |       |         |
Additial CBV Mixins with `django-braces`    |           | x     |         |
***Chapter 14***                            |           |       |         |
Django caching with `memchached/redis`      |           |       |         | x
***Chapter 15***                            |           |       |         |
Django Rest Framework for APIs              | x         |       |         |
***Chapter 16***                            |           |       |         |
Implement Daphne ASGI                       | x         |       |         |
Django Channels                             | x         |       |         |
Web Sockets                                 | x         |       |         |
Python/Django Async programming             | x         |       |         |
***Chapter 17***                            |           |       |         |
Docker Deployment (optional)                | x         |       |         |

### Optional 3rd Party Tools to consider***
* [Django admin](https://github.com/wsvincent/awesome-django#admin)
* [APIs](https://github.com/wsvincent/awesome-django#apis)
* [Async](https://github.com/wsvincent/awesome-django#async)
* [ECommerce](https://github.com/wsvincent/awesome-django#ecommerce)
* [Files and Images](https://github.com/wsvincent/awesome-django#filesimages)
* [Model enhancements](https://github.com/wsvincent/awesome-django#models)
* [Search](https://github.com/wsvincent/awesome-django#search)
* [Tasks and Job Scheduling](https://github.com/wsvincent/awesome-django#task-queues)
* [Users and SSO](https://github.com/wsvincent/awesome-django#users)
* [Views](https://github.com/wsvincent/awesome-django#views)

***NOTE A***: This does not JUST mean in the inclusion of any [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).  I would strongly recommend [htmx](https://htmx.org/) if you need any front-end JS magic. However, it should be the case that MOST JavaScript is optional.
