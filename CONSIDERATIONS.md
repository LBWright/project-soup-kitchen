# Things to consider

What will we need to use for the database?

How specific do we want our API endpoints to be?

What forms of Authentication will we want?

Microservices vs Monolith?

Will we want Redux in this application?

How will we manage permissions?

What will we use for deployment?

How will we design the client?

What data do we need to keep on the client? More specifically, what data needs to be available to the private and public profiles?

GraphQL vs REST? 

Creating a good git workflow
* right now, to me, it makes sense to create new branches of all each 'feature' as we move along. The branch would be named `/feature/feature-name`. If Tyson wanted to work on a specific feature, he'd create another branch called `/feature/feature-name/tyson`. After work on a feature branch is done by an individual, it will be merged onto that feature branch. Each pull request that touches other code *should* be reviewed by someone else before it's merged. Feature branches that pass the appropriate tests (optional testing?) will be merged onto staging, and that branch will be merged to master. 
* let's iron out the kinks in a workflow that works for us as a team
* I would like to eventual set up automatic deployment from the master branch
