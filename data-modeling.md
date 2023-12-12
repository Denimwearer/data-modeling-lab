# Brainstorming

1. Users
2. Recipes
3. Ingredients
4. username
5. password
6. email
7. occasions
8. grocery lists

# Table Ideas

## Users

- stores the users info username, password, email

## Recipes

- title, instructions, public/private

## Ingredients

- name and other ingredient related info

## Grocerys List

- quantity and other grocery related info

## Occasions

- info if the occasion is public or private and name

## Occasions_Recipes

- id, recipe_id

## Recipe_ingredients

- quantity, id, recipe_id, ingredient_id

# Relationships

1. one-to-one
2. one-to-many

   - many recipes can belong to one user
   - many recipe_ingredients can belong to one recipe
   - many recipe can use the same ingredient
   - many grocery lists can belong to one user
   - many grocery lists can include the same ingredient
   - many occasions can belong to one user
   - many recipes can be associated with one occasion
   - many occasions can include the same recipe

3. many-to-many

   - many ingredients can be used in many recipes

   ![alt text](ERD.gif)
