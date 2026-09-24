# Secondary Research

## Research Objective

The objective of this research is to understand the problems people experience when deciding what to cook with the food they already have at home.

The research focuses on:

* meal decision-making
* planning effort
* the gap between available ingredients and possible meals
* recipe discovery and ingredient mismatch
* existing solutions and their limitations

This research is exploratory. The findings below represent observed signals and research evidence, not validated assumptions about the entire target population.

## Research Approach

The research combines three types of secondary sources:

1. **Online community research** — real user-generated discussions about cooking, meal planning, ingredients and decision-making.
2. **Academic research** — studies examining meal planning, convenience, and the cognitive effort associated with preparing meals.
3. **Existing product research** — analysis of products that already help users discover recipes based on available ingredients.

Reddit discussions are treated as qualitative signals rather than representative user research.

## Research Sources

### Online Communities

Reddit communities including:

* r/cookingforbeginners
* r/cookingtonight
* r/mealprep
* r/dinnersuggestions
* r/simpleliving

These discussions provide examples of how people currently approach meal decisions and what difficulties they encounter.

### Academic Research

Research on meal-kit services provides evidence that meal planning involves more than cooking itself. A 2025 qualitative study found that participants frequently described deciding what to cook, planning, and organizing meals as a cognitive burden. Participants specifically reported that meal-kit services reduced the mental effort associated with answering "what's for dinner?"

### Existing Products

Existing products already address parts of the problem.

Samsung Food allows users to maintain a Food List and search for recipes based on ingredients they have available. Recipes can be ranked according to how well they match the user's available ingredients.

SuperCook also provides recipe search based on ingredients, allowing users to search recipes using ingredients they specify.

This indicates that "what can I cook with what I have?" is an established product use case rather than an entirely new category.


# Observed User Signals

## 1. Meal Decision Fatigue

A recurring theme in online discussions is that deciding what to cook can feel more difficult than the actual cooking.

One 2026 Reddit discussion described users spending significant time looking at the fridge, scrolling through recipes, and still being unable to decide what to make. Other participants described reducing the number of choices or relying on repeatable meals to make the decision easier.

Another discussion described the daily decision of what to cook as the hardest part of the process, with the user eventually building a simple tool that selects recipes based on ingredients and available time to reduce the number of decisions.

### Observed behavior

Users may:

* repeatedly open the fridge without finding an obvious meal
* browse many recipes before making a decision
* fall back to a small set of familiar meals
* use external systems to reduce the number of decisions

### Potential pain point

The challenge may not be the ability to cook. It may be the recurring cognitive effort required to decide **what to cook**.

## 2. Ingredient-to-Meal Gap

Several discussions describe a situation where people have food available but cannot easily translate those ingredients into a satisfying meal.

One Reddit discussion described having ingredients in the fridge while still feeling as though there was "nothing to eat." The discussion also highlighted the frustration caused when recipes require additional ingredients.

Another user described having food at home but repeatedly cooking the same few meals because they lack ideas for how to use the ingredients differently.

### Observed behavior

Users may:

* have multiple ingredients available
* struggle to combine those ingredients into a meal
* repeatedly prepare the same meals
* search for inspiration based on a specific ingredient
* abandon a recipe when an important ingredient is missing

### Potential pain point

Having ingredients available does not necessarily result in a clear meal decision.

There appears to be a gap between:

**"What do I have?"**

and

**"What can I realistically make?"**


## 3. Recipe Mismatch

Recipe discovery can introduce another layer of friction when recipes do not match the ingredients users actually have.

In online discussions, users describe finding recipes that require additional ingredients or discovering only during preparation that an important ingredient is missing.

Existing products attempt to address this problem. Samsung Food, for example, allows users to search using their Food List and prioritizes recipes that match available ingredients.

### Potential pain point

Generic recipe discovery can create additional planning work when users have to:

1. find a recipe
2. compare it with their inventory
3. identify missing ingredients
4. decide whether to shop for them
5. reconsider the recipe if the effort is too high


## 4. Planning Effort

Meal planning discussions show that users often develop personal systems specifically to reduce the number of decisions they need to make.

For example, some users create recurring meal rotations or organize meals around shared ingredients. One 2026 discussion described using a weekly cuisine theme to reduce the number of daily decisions and avoid accumulating unrelated ingredients.

Another user described a structured weekly workflow based on existing ingredients, overlapping ingredients across meals, and grocery planning. The stated benefit was reducing the need to start the planning process from scratch every week.

### Potential pain point

Meal planning can become a recurring operational task rather than a one-time decision.

# Emerging Themes

Based on the sources reviewed so far, four themes are emerging:

| Theme                  | Observed signal                                                     | Product implication                                                                       |
| ---------------------- | ------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Decision fatigue       | Users describe deciding what to cook as mentally tiring             | Recommendations should reduce the number of decisions rather than present endless options |
| Ingredient-to-meal gap | Users may have ingredients but lack a clear meal idea               | The product should connect inventory directly to realistic meals                          |
| Recipe mismatch        | Recipes may require ingredients users do not have                   | Recommendations should clearly distinguish available and missing ingredients              |
| Planning burden        | Users create routines and meal rotations to avoid repeated planning | Future product opportunities could extend beyond individual recipe discovery              |

These themes are currently **research signals**, not validated product requirements.

# Existing Solutions

Existing products demonstrate that several parts of this problem already have established solutions.

### Ingredient-based recipe discovery

Samsung Food allows users to search for recipes using ingredients in their Food List and highlights recipes based on ingredient matches.

### Recipe search by ingredients

SuperCook provides recipe search based on user-specified ingredients.

### Meal-kit services

Meal-kit research suggests that users value the reduction of planning, shopping, and preparation effort. A 2024 study found convenience to be a major source of perceived value, including saving time on grocery shopping, recipe search, and ingredient preparation.

A qualitative study similarly found that participants valued meal kits because they reduced the cognitive and organizational work involved in deciding, planning, and preparing meals.

### Opportunity

The existing market suggests that the underlying problem is already being addressed from several directions:

**Meal kits:** reduce planning and shopping effort by providing a predefined meal.

**Recipe platforms:** provide inspiration and recipes.

**Ingredient-based platforms:** connect available ingredients with recipes.

FridgeMate explores a different interaction model:

> **Start with the user's physical fridge and turn it into a usable starting point for meal decisions.**

# Research Gaps

The secondary research does not answer several important questions:

* How frequently do people experience this problem?
* How much time do they typically spend deciding what to cook?
* Would users prefer photo-based inventory creation over manual ingredient entry?
* How accurate does ingredient recognition need to be before users trust the resulting inventory?
* How much correction would users be willing to make after AI detection?
* What makes a recipe feel "realistic" rather than technically compatible?
* How important are meal context, cuisine, dietary preferences, and available cooking time?
* Would users repeatedly return to an ingredient-based recommendation workflow?

These questions require primary research and product validation.

# Implications for FridgeMate

The research suggests that the opportunity should not be framed simply as **"an AI recipe generator."**

A stronger product hypothesis is:

> FridgeMate could reduce the friction between having ingredients at home and deciding what to cook by helping users quickly create an inventory and turn that inventory into realistic meal options.

The role of AI is therefore primarily to reduce the effort of **creating and maintaining the inventory**, rather than replacing the user's decision-making.

This supports the initial product flow:

**Fridge → AI ingredient detection → User confirmation → Available inventory → Relevant meal options**

The research also suggests that recommendations should not be based solely on ingredient overlap. Factors such as missing ingredients, preparation effort, meal context, and user preferences may influence whether a recommendation is actually useful.

These assumptions should be validated before defining the final MVP.
