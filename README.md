# Hero Academy: Healthy Plate

Hero Academy: Healthy Plate is a 10-round food-classification game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each run randomly selects 10 food or drink items from a built-in bank of 19. For each item, the player chooses between the game’s two categories: **healthy** or **unhealthy**.

**random item → healthy/unhealthy choice → compare with built-in label → +10 points for a match → next item → final score and message**

The maximum score is 100. The final screen selects feedback from score bands after all 10 classifications are completed.

## Items represented

The current bank includes apples, candy, broccoli, water, soda, carrots, pizza, donuts, strawberries, fries, eggs, burgers, watermelon, ice cream, grapes, corn, oranges, cake and hot dogs.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## Nutrition boundary

The `healthy` and `unhealthy` values in the source are binary game labels. They are not a complete nutrition standard or individualized dietary assessment. Nutritional suitability can depend on portion, preparation, overall dietary pattern, allergies, medical needs and other context not represented by this game.

The repository contains no study measuring nutrition knowledge retention, dietary behavior change or health outcomes outside the game.

## Deployment status

The repository Homepage field currently points to `https://kids-hero-academy.vercel.app`, which returned 404 during the audit. No working public deployment is therefore claimed here.

## Repository scope

The playable implementation is contained entirely in `index.html`.

`index.html` is preserved as the game artifact. Documentation must not alter the item bank, built-in classifications, random selection, scoring, score-band messages, controls, visuals, timing or runtime behavior.
