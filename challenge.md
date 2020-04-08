# MongoDB CLI

## Getting Started

The prompts below each ask for you to write the query in MongoDB for performing
some action (described in the prompt). Your response should be a valid query and
it should be property formatted in Markdown. For example:

**Prompt:** Find all burgers in the `burgers` collection.

```
db.burgers.find({})
```

### Instructions

* Start your `mongo` server
* Connect to the `mongo` shell

### Prompts

**Prompt:** What is the command to start the `mongo` server?

**Prompt:** What is the command to connect to the `mongo` shell?

**Prompt:** What is the command for listing all `mongo` databases?

**Prompt:** What command would you use to create a database called `burgers`?

**Prompt:** What command would you use to add the collection `burger` to your
`burgers` database?

**Prompt:** What is the command for listing all collections in a database?

## Inserting

### Prompts

**Prompt:** Insert a single burger into the `burgers` collection with the
following:

* a `patty` property set to `beef`
* a `cheese` property set to `false`
* a `toppings` set to an array with `ketchup`, `onions`, and `pickles`

**Prompt:** Insert 10 burgers into the `burgers` collection with the following:

* a `patty` property that is set to one of: `beef`, `turkey`, or `veggie`
* a `cheese` property that is either `true` or `false`
* a `toppings` property that is either one of `ketchup`, `onions`, `pickles`,
  `mustard`, and `mayonnaise`

## Reading

The following prompts will have you querying (reading) from your `burger`
collection. If you don't have burgers in your database that match the query
criteria described below, you wont get any results back. So, add one or two that
match that criteria before running the query.

### Prompts

**Prompt:** What query would find all burgers with a `beef` patty?

**Prompt:** What query would find all burgers with cheese on them?

**Prompt:** What query would find a burger by it's ObjectId?

**Prompt:** What query would find all burgers with `ketchup` as a topping?

**Prompt:** What query would find all burgers with either a turkey or veggie
patty?

**Prompt:** What query would find all burgers with a beef patty and cheese?

**Prompt:** What query would find all burgers with a beef patty and ketchup as
a topping?

**Prompt:** What query would find all burgers with a beef patty and both onions
and pickles as toppings?

**Prompt:** What query would find burgers with either a turkey patty or cheese?

## Update

### Prompts

**Prompt:** What query would update one burger by it's ObjectId, setting it's
"patty" to "pork"?

**Prompt:** What query would update all burgers with beef paddies to have
cheese? (i.e. set "cheese" to true)

## Delete

### Prompts

**Prompt:** What query would delete a burger by it's ObjectId?

**Prompt:** What query would delete all veggie burgers?

**Prompt:** What query would delete all burgers with pickles on them?
