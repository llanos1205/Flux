# Flux
A simple flux integration
The purpose of this repo is to store config for my local development clusters
To store common baseline use cases
To test different use cases

Feel free to use as a template
OF course I dont ahve to remind you to change the sources to match your repository and not mine

# Pattern

There are 3 main folders

## Addons

For cluster related charts like monitoring, testing, storage etc

This will have 2 folders inside

- Base  (the most raw  implementation)
- Environment (specific values for a specific cluster)


## Services

For actual apps, mostly made by me too
## Clusters

Clusters containing a specific set of the folders mention above