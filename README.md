# Express Mongoose Relationships Lab

### Node.js, Express, Mongoose/MongoDB, Jest 
___

#### Assignment: "Update your recipe application so that `Event` is related to a `Recipe`."


## Requirements

**Add tests if needed**

### Update Event (2 points)

On the `Event` model update `recipeId` so it is a reference to your `Recipe` model.

### Update Recipe routes(6 points)

#### findById route

On getting a recipe by id also fetch all `Event` documents associated with the recipe

#### findByIdAndDelete route

On deleting a recipe also delete all `Event` documents associated with the recipe

#### find route

Allow users to provide a query string to search for recipes by an ingredient
(e.g. `/api/v1/recipes?ingredient=flour`).

### Update Event routes (2 point)

#### findById route

On getting an event by id `populate` the recipe

