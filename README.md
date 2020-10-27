# Expert recommendations

Final project for the Building AI course

## Summary

This project will use a database of experts and their skills to make better recommendations when people search for experts on specific topics,
and also recommend other skills to investigate and people to contact based on your own skills.

## Background

I've recently joined a project team at work which has developed a company internal experts & knowledge exchange platform.

While the basic search functionality works nicely and already includes some AI in the form of word embeddings,
the current system doesn't really make much use of the data that has been collected by now,
and so many interesting search results, recommendations and connections might remain hidden.

I want to change that by implementing a recommendation system based on the available data.

## How is it used?

The functionality will be directly included in the tool/webapp we already have and are using internally,
so all our users who are already using it (and future ones) will (hopefully) benefit from this project.

For obvious reasons I won't be able to provide the data used in this repo,
but I will try to include some anonymized sample data, and the scripts to train and use the model.

## Data sources and AI methods

Data is available in an existing database, and is continously filled with new data from users. Essentially the data is of the form "Expert `E` has skill `S` at level `L`".

I will use some sort of item-item recommendation system, not sure about the details yet, I still have some reading and experimenation ahead of me on that topic.

## Challenges

Even if there already is quite some data, it might not be enough to create good recommendations.

Another problem might be that not so common items will become hidden from users, which I will have to find ways to remedy.

## What next?

Too early to say really, as I'm not yet even sure this will work as intended :)


## Acknowledgments

*  The [Elements of AI](https://www.elementsofai.com/) Team for inspiring me to try this project
*  ...
*  will be filled as the project progresses
