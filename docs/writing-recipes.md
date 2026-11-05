# Writing a recipe

You are writing for one cook, at the stove, in the kitchen described here. The page is what they read while cooking. This document is what you read before you write. Follow these rules. Use `recipes/Mapo tofu (麻婆豆腐).md` as a finished page that already follows them.

A **line** is one ingredient measure. A **part** is one stage the cook finishes. The **gather list** is the `## Ingredients` section. A **coil move** is how this stove changes heat.

## 1. Name the file

Done when the path and the `#` title are fixed.

- Save the file at `recipes/<title>.md`. The directory is flat.
- The title is the headword an English-language cookbook prints: `Mapo tofu`, `Kung Pao chicken`, `Pizza`.
- When that headword renders a name from another language, add a space and the original name in parentheses: `Mapo tofu (麻婆豆腐)`. A spelling that drops diacritics still takes the original: `Pho (phở)`.
- When English already spells the name the same way, the title is the English name alone: `Pizza`.
- The `#` title and the filename are the same words.
- The English name is unique inside `recipes/`. A variant adds the distinguishing words to the English name: `Mapo tofu with beef (麻婆豆腐)`.
- Write the name with spaces and capitals, as it reads on the page.

## 2. Check the dish online

Done when two published recipes have been read and the shared method is chosen.

Search the original name and the English headword. Read at least two published recipes from cooks who know that cuisine. A specialist cookbook, a tested kitchen, or a regional writer outranks an unsourced page.

Keep the cut, the coating, the fat, the defining aromatics, the cook order, and the amounts those sources share. Scale them to this yield. Where the sources disagree, choose the version this kitchen can cook, and put that choice in the steps.

## 3. Split the dish into parts

Done when every part has a name, a place in the cook order, and a vessel.

A part is a component the cook finishes before it joins the dish, or a stage with its own lines: a blanch, a toasted spice, a slurry, the knife-and-cup prep, the cook in the pan.

Order the parts in the order the cook starts them. A dish cooked as one sequence is one part. That part measures its own lines and cooks them.

When earlier parts measure everything the last part uses, the last part is a combining section. Name it for the action (`Stir-fry`). Every line in it was already measured. It still gets a cooking section.

Rice is its own page, `recipes/Jasmine rice.md`. Do not add a Rice part to another dish.

## 4. Choose the vessel

Done when every part uses one vessel from this kitchen.

This cook has an electric stove with exposed coils, a round-bottom wok that sits in a ring, an Instant Pot, and a frying thermometer. The neutral oil is peanut oil.

- **Rice.** Only on `recipes/Jasmine rice.md`. The Instant Pot. Rinse the rice until the runoff is almost clear and drain it well. Use 1 cup of water for each 1 cup of rice. Lock the lid, set the valve to sealing, and pressure cook on high for 3 minutes. When it beeps, turn the valve to venting. Leave the lid on until serving, then fluff the rice. Do not copy this part into another dish.
- **A pot of water.** A heavy saucepan on a coil: blanching, boiling, a simmer you hold at a shiver. When the boil is harder than the step wants, pull the pot so it sits half on the coil.
- **A spoonful of spices.** A small skillet on a coil. Slide the skillet off the coil if they smoke.
- **A sear, a paste, or a fry that turns into a simmer.** A 10 in heavy skillet on a coil. This pan can leave the coil.
- **The round bowl.** The wok, when the wall is doing the work: a full load tossed through a small hot center, or food held up the sides while the bottom reduces. The wok stays in the ring for the whole cook.
- **Deep frying.** A deep heavy saucepan on a coil. A slip through a deep pot of oil uses this same pot. Read the oil on a frying thermometer, in Fahrenheit. The step names the temperature. A slip stays cooler than a crust fry, and the food should not brown. Bring the oil back to that temperature between batches. When the oil smokes or climbs past it, pull the saucepan off the coil until it returns, then set it back. A few tablespoons in a skillet is too shallow for the thermometer. That oil is ready when it shimmers. A pour onto dried chilies is ready when a dry wooden spoon handle makes small bubbles and the oil has not yet smoked. Smoking oil blackens those chilies. A pour that blooms spices in the pan is ready when the oil just starts to smoke, and the pan comes off the coil before the spices go in.

### Coil moves

Write these into the step that changes the heat. The water drop is for an empty pan. Once oil is in the pan, do not flick water into it to judge the heat.

For a skillet or a saucepan:

- Heat the empty pan on high until a drop of water skitters and vanishes, about 3 minutes for the 10 in skillet.
- To lower the heat, pull the pan off the coil, turn the coil down, wait until the coil stops glowing, and set the pan back.
- When the center boils hard, pull the pan so it sits half on the coil, or turn the coil down one notch.
- When a paste smells sharp, pull the pan off the coil and stir until the smell sweetens, then set it back.

For the wok:

- Heat the empty wok in the ring on high until a drop of water flicked into the center vanishes, about 5 minutes.
- Keep the food in the bottom, where the heat is. The walls stay cooler. Food can sit up the sides while the sauce cooks in the bottom, then fold back down.
- To lower the heat, turn the coil off, wait until it stops glowing, and turn it to the lower setting. The wok stays in the ring.
- When a paste smells sharp, turn the coil off and stir until the smell sweetens, then turn the coil back to the lower setting.

## 5. Write the lines

Done when the gather list and every part list satisfy this section. Scale the shared amounts from the online check to this yield.

Each line is one measure the cook makes, written `quantity unit name` or `count name`. Two uses of one ingredient are two lines. Each use of water is its own line. Put the role or the prep after a comma: `1 tbsp peanut oil, for the beef`, `2 tsp garlic, minced`, `3 scallions, cut into 3/4 in lengths`.

- Weight is ounces. Volume is teaspoons, tablespoons, and cups. Size is inches. Write fractions as `1/2`, `1/4`, `1/8`, `3/4`. Count garlic by cloves, or measure it by the teaspoon, the tablespoon, or the ounce.
- A spoon measure of kosher salt names the brand after a comma: `1/2 tsp kosher salt, Diamond Crystal`.
- Parentheses hold the original-language name and nothing else, placed after the English name and before any comma: `2 tbsp Pixian doubanjiang (郫县豆瓣酱), chopped`.
- Add that original name when an English search commonly returns a different product. The mapo tofu page is the calibration: soft tofu (嫩豆腐), Sichuan peppercorns (红花椒), Pixian doubanjiang (郫县豆瓣酱), fermented black beans (豆豉), Sichuan chili flakes (四川辣椒面). Garlic, ginger, scallions, peanut oil, stock, rice, potato starch, and white pepper stay in English. When a recipe needs a neutral oil, write peanut oil. Do not substitute canola, vegetable oil, or rapeseed oil. A flavored oil stays when the dish needs that flavor, and it keeps its original name: toasted sesame oil (香油).
- When that named product still has kinds a shopper mixes up, the part that first measures it opens with a short sentence naming the kind this page uses. Say it once. Copy a sentence this book already uses, rather than writing a new one for the same product: water-packed soft tofu, the coarse Pixian paste, medium 二荆条 flakes marked 中辣, unsalted Shaoxing, thin threads with mung bean starch first, dried sweet potato cords about as thick as a chopstick, round white Shanghai-style wheat wrappers from the refrigerator or freezer case, thick square wrappers from the refrigerator case, the fatty plate sold as 牛腩, and leave the fat on, plain red chili oil, flank steak so the slices soften in this time, thick Chinese scallions so the pieces stay crisp, the thin marbled slices sold for hot pot, a waxy potato so the pieces stay whole, ripe tomatoes that smell sweet, ground pork that shows some fat, large peeled shrimp with the tails off, cleaned squid tubes, the yolks from salted duck eggs, unsweetened shredded coconut, tomato ketchup, plain rice vinegar, the thick stem of celtuce, fresh shiitake, a long Chinese eggplant, sweet wheat sauce from the jar marked 甜面酱, Yibin suimi yacai from the jar marked 碎米芽菜, canned pork luncheon meat, firm tofu from the block marked 北豆腐, small bok choy, Sichuan pickled red chilies from the jar marked 泡椒, and toasted Chinese sesame paste. For green beans in a stew: Flat green beans and common green beans both turn silky in this stew. For a dry-fry: Flat green beans and common green beans both blister in this fry.
- The gather list contains each line once, under the bold label of the part that first measures it. Labels follow cook order. Inside a part, lines follow use order.
- Every part that measures a line repeats it with the same words.
- A later part may append only the state the ingredient is in now: `, drained`, `, toasted and crushed`.
- The combining section repeats the lines it uses. Those repeats are the same measures, grouped under the same bold labels, in the same order.

When you change a line, change every copy of it.

## 6. Assemble the page

Done when the page matches this shape. The fixed sentences in the template are exact.

```markdown
# English name (原文)

Serves 2. About 30 minutes.

<One line naming the vessel and program for each part.>

<One line for the order of work when a pot waits or a timer interrupts.>

Measure each ingredient once. A later list is that same amount again.

## Ingredients

**First part**

- 1 cup ingredient

**Second part**

- 4 oz ingredient

---

## First part

- 1 cup ingredient

1. Do the thing with the **ingredient** until the cue. Go on to the next part.

## Second part

Do this before the pan is hot.

- 4 oz ingredient

1. Do the thing until the cue.

## Stir-fry

These amounts were measured above.

**First part**

- 1 cup ingredient

**Second part**

- 4 oz ingredient, drained

1. Add the **ingredient** and cook until the cue.
```

- The yield line is `Serves N. About M minutes.` or `Makes N. About M minutes.` The time runs until the cook eats, including waits that overlap other parts.
- The setup line names the Instant Pot program and the pan for each part that has one.
- The order line is there when the cook starts a part and leaves it. It names the interrupt: when the timer rings, what they do, then that they keep going.
- The measure sentence is on every page.
- The gather list is one `## Ingredients` section. Its groups are bold labels, so the outline stays the cooking sections.
- A `---` sits between the gather list and the first cooking section.
- Cooking sections are `##` headings in cook order.
- A part may open with one or two short sentences under the heading. One names the kind of ingredient, when the line alone still fits more than one product. Prep that must finish before heat says so. The combining section says `These amounts were measured above.`
- Ingredient bullets sit under the heading or the bold label. The numbered steps follow them.
- Keep each numbered list on consecutive lines, so the numbers stay one series.
- The page teaches the cook the dish. Filename, heading, and parenthesis rules stay in this document.

## 7. Write the steps

Done when each part has steps a cook can follow while the pan is hot.

- Number the steps. Write them as imperatives.
- Bold the thing the step adds. The bold words match the line's name: the **peanut oil for the beef**, the **drained tofu**.
- A step is one addition or one wait, and it ends on a cue: a look, a smell, or a time.
- Put the heat in the step that uses it, using the coil moves.
- Finish knife work, rinsing, and measuring in an earlier part when a later step resolves in under a minute. The hot step then names the cups.
- When several cups go in at once, say they go in together.
- A timer that overlaps the next part tells the cook to go on, and tells them what to do when it rings. The later part that receives that food says what to do if it is still waiting.

Name an ordinary pan, pot, or spoon in the step that uses it. When a common tool produces the result, use it. When only an uncommon tool produces the result, put one line under that part's heading and above its lines: `Tool: bamboo steamer.`

## 8. Check, then save

Done when every item below holds and the file is saved at `recipes/<title>.md`.

- The amounts and the method were checked against at least two published recipes. Where those recipes disagree, the page uses the version this kitchen can cook.
- The path is `recipes/<title>.md`, the `#` title matches, and the English name is unique.
- An original name sits in parentheses when the English title renders another language.
- The header has the yield line, the setup line, the order line when something waits, and the measure sentence.
- The gather list is `## Ingredients` with bold labels. Each line appears there once.
- A combining section is absent from the gather list and present among the cooking sections, with its amounts grouped by the part that measured them. A one-part dish has no combining section.
- A `---` sits between the gather list and the first cooking section. Cooking sections are `##` headings in cook order.
- Every line is one measure, with a quantity and a unit or a count. Units are ounces, teaspoons, tablespoons, cups, and inches, written as fractions. Count garlic by cloves, or measure it by the teaspoon, the tablespoon, or the ounce.
- Labels in the gather list follow cook order. Inside a part, lines follow use order.
- Copies of a line match. A later copy adds only the current state.
- An ingredient that an English search commonly misidentifies carries its original name. The mapo tofu page is the calibration.
- When a named product still has kinds a shopper mixes up, the part that first measures it names the kind in a short sentence. A choice already written on another page is copied.
- A spoon measure of kosher salt names Diamond Crystal. Parentheses hold only an original-language name.
- The neutral oil is peanut oil. A flavored oil is named only when the dish needs that flavor.
- Rice stays on `recipes/Jasmine rice.md`. Another dish has no Rice part. Every part uses the vessel this kitchen assigns it.
- Heat changes use the coil moves. A wok stays in the ring.
- Deep-fry oil, and oil for a slip, is a Fahrenheit temperature on a thermometer. The step names the temperature, and the oil returns to it between batches. A shallow skillet of oil does not.
- Steps are a tight numbered list. The added thing is bold. Each step ends on a cue.
- Work that a short step depends on is finished in an earlier part.
- An uncommon tool has one `Tool:` line. Every other tool is named in the step.
