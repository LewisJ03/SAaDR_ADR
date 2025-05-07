
# Creation and implementation of test databases

## Context and Problem Statement

How will you be implementing and using databases effectively for the project?

We will be using using a smaller set of databases compared to the amount needed to hold the required userbase, which will hold fake data, so that all tests can be done effectively but without spending lots of time creating fake data.

## Decision Drivers

* Having enough data to work with that all user cases can be tested.
* Limiting the amount of data being added so that an effective amount of time can be spent on making the product instead.

## Considered Options

* large Scale customer/admin database.
* small scale customer/admin database.

## Decision Outcome

Chosen option: "large scale users and small scale admin", because this can accurately reflect the ratio of customers to employee accounts that will need to be held on the system once it has been rolled  out to the general public.

### Consequences

* Good, because it allows for accurate representation of accurate system.
* Bad, because with smaller test sizes this could lead to problems that arent seen until full roll out of product.



## Pros and Cons of the Options

### Large scale

* Good, because much more accurate results when testing
* Bad, because would need to be auto generated which takes much longer and data will be less unique

### Small scale

* Good, because unique and varied test data
* Bad, because less accurate results can be given by testing with lower amounts of data
