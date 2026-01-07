# Qdoba Nutrition Calculator: Calories, Macros & Custom Meal Builder

> Complete nutrition database and calculator for all Qdoba Mexican Eats menu items. Calculate calories, track macros, build keto meals, and customize your order with accurate nutrition facts.

## What This Tool Does

This repository provides the complete **Qdoba nutrition database** in JSON format. Use it to calculate meal nutrition, track calories, monitor macros, and make informed dietary choices at Qdoba Mexican Eats.

**[Try the Interactive Calculator →](https://qdobanutrition.net/)**

---

## How to Calculate Your Qdoba Meal Nutrition

Building a custom Qdoba meal means adding up each ingredient you choose. Here's how to calculate your total nutrition.

### Basic Formula

```
Total Calories = Base Calories + Protein Calories + Rice/Bean Calories + Topping Calories + Sauce Calories
```

**Example:**

You build a bowl with Grilled Adobo Chicken, Cilantro Lime Rice, Black Beans, Guacamole, and Salsa:

```
Grilled Adobo Chicken (3.5 oz):  190 calories
Cilantro Lime Rice (4 oz):       190 calories
Black Beans (4 oz):              140 calories
Hand Crafted Guacamole (2 oz):   80 calories
Pico de Gallo (1 oz):             5 calories
─────────────────────────────────────────────
Total Meal:                      605 calories
```

### Calculating Macros for Custom Bowls

Use the same approach for protein, carbs, and fat:

```
Total Protein = Protein Source + Beans + Cheese + Other Toppings
Total Carbs = Rice + Beans + Tortilla + Salsas
Total Fat = Protein Fat + Guacamole + Cheese + Sour Cream
```

**Example:**

Your bowl macro breakdown:

```
Protein:  19g (chicken) + 9g (beans) + 1g (guac) = 29g protein
Carbs:    38g (rice) + 24g (beans) + 5g (guac) + 1g (salsa) = 68g carbs
Fat:      12g (chicken) + 1g (beans) + 8g (guac) + 2.5g (rice) = 23.5g fat
```

### Net Carbs Formula (For Keto)

If you're following a keto diet, calculate net carbs:

```
Net Carbs = Total Carbs - Dietary Fiber
```

**Example:**

A Keto Bowl with 13g total carbs and 7g fiber:

```
Net Carbs: 13g - 7g = 6g net carbs
```

This is perfect for staying under 20-30g net carbs per day on keto.

---

## Popular Signature Eats - Nutrition Guide

### Complete Signature Eats Menu

| Item | Calories | Protein | Carbs | Fat | Fiber |
|------|----------|---------|-------|-----|-------|
| Chicken Queso Bowl | 750 | 43g | 74g | 33g | 16g |
| Chicken Queso Burrito | 1,050 | 51g | 126g | 40g | 19g |
| Cholula® Hot & Sweet Chicken Bowl | 610 | 31g | 77g | 20g | 15g |
| Cholula® Hot & Sweet Chicken Burrito | 910 | 39g | 130g | 27g | 19g |
| Citrus Lime Chicken Salad | 540 | 31g | 49g | 26g | 16g |
| Double Protein Bowl - Chicken | 700 | 51g | 41g | 38g | 20g |
| Double Protein Bowl - Steak | 1,040 | 52g | 47g | 72g | 20g |
| Fajita Vegan Bowl | 530 | 17g | 79g | 17g | 22g |
| Impossible™ Taco Salad | 520 | 31g | 46g | 23g | 18g |
| Quesabirria Burrito | 980 | 46g | 124g | 95g | 19g |
| Quesabirria Quesadilla | 1,080 | 55g | 67g | 127g | 6g |
| Southwest Steak Burrito | 1,220 | 43g | 134g | 58g | 19g |

### Lowest Calorie Signature Eats

| Item | Calories | Protein | Notes |
|------|----------|---------|-------|
| Impossible™ Taco Salad | 520 | 31g | Plant-based |
| Fajita Vegan Bowl | 530 | 17g | Vegan, high fiber |
| Citrus Lime Chicken Salad | 540 | 31g | Salad base |
| Cholula® Hot & Sweet Chicken Bowl | 610 | 31g | Spicy option |
| Double Protein Bowl - Chicken | 700 | 51g | High protein |

---

## Keto Options - Low Carb Meals

Qdoba offers dedicated Keto Bowls designed for low-carb diets:

### Keto Bowl Nutrition

| Keto Bowl | Calories | Protein | Net Carbs* | Fat |
|-----------|----------|---------|------------|-----|
| Keto Bowl - Chicken | 400 | 33g | 4g | 26g |
| Keto Bowl - Brisket Birria | 370 | 25g | 6g | 25g |
| Keto Bowl - Steak | 490 | 25g | 6g | 38g |

*Net carbs = Total carbs minus fiber

**Building Your Own Keto Meal:**

```
Base: Romaine Lettuce (0 calories)
Protein: Grilled Adobo Chicken (190 cal, 19g protein, 2g carbs)
Toppings: Fajita Veggies (40 cal, 3g carbs)
Sauce: Habanero Salsa (10 cal, 2g carbs)
─────────────────────────────────────────────
Total: 240 calories, 19g protein, 7g net carbs
```

**Keto Formula:**

```
Keto-Friendly = Net Carbs < 10g per meal
```

Most keto diets aim for 20-30g net carbs per day, so one Keto Bowl fits perfectly.

---

## High-Protein Options

### Protein Efficiency Formula

To find the best protein-to-calorie ratio:

```
Protein Efficiency = (Protein in grams ÷ Calories) × 100
```

**Example Comparison:**

Double Protein Bowl - Chicken:
```
(51g ÷ 700 calories) × 100 = 7.3% protein efficiency
```

Grilled Adobo Chicken (3.5 oz):
```
(19g ÷ 190 calories) × 100 = 10% protein efficiency
```

### Highest Protein Items

| Item | Calories | Protein | Protein per 100 cal |
|------|----------|---------|---------------------|
| Double Protein Bowl - Steak | 1,040 | 52g | 5.0g |
| Double Protein Bowl - Chicken | 700 | 51g | 7.3g |
| Quesabirria Quesadilla | 1,080 | 55g | 5.1g |
| Chicken Queso Burrito | 1,050 | 51g | 4.9g |
| Grilled Adobo Chicken (3.5 oz) | 190 | 19g | 10.0g |
| Brisket Birria (3.5 oz) | 140 | 15g | 10.7g |

---

## Ingredient Nutrition Guide

### Protein Options

| Protein | Serving | Calories | Protein | Fat | Carbs |
|--------|---------|----------|---------|-----|-------|
| Grilled Adobo Chicken | 3.5 oz | 190 | 19g | 12g | 2g |
| Grilled Steak | 3.5 oz | 360 | 20g | 28g | 5g |
| Ground Beef | 3.5 oz | 190 | 15g | 12g | 4g |
| Pork Carnitas | 3.5 oz | 110 | 14g | 4.5g | 0g |
| Brisket Birria | 3.5 oz | 140 | 15g | 7g | 3g |
| Cholula® Hot & Sweet Chicken | 3.5 oz | 190 | 16g | 10g | 10g |
| Chorizo | 3.0 oz | 260 | 14g | 20g | 5g |
| Plant-Based Impossible™ | 3.1 oz | 170 | 13g | 9g | 8g |
| Eggs | 6 oz | 230 | 19g | 16g | 2g |

### Rice & Beans

| Item | Serving | Calories | Carbs | Fiber | Protein |
|------|---------|----------|-------|-------|---------|
| Cilantro Lime Rice | 4 oz | 190 | 38g | 1g | 3g |
| Seasoned Brown Rice | 4 oz | 170 | 36g | 2g | 4g |
| Black Beans | 4 oz | 140 | 24g | 14g | 9g |
| Pinto Beans | 4 oz | 130 | 23g | 14g | 8g |

**Fiber Formula:**

```
Total Fiber = Bean Fiber + Rice Fiber + Vegetable Fiber
```

**Example:**

```
Black Beans (4 oz):  14g fiber
Brown Rice (4 oz):    2g fiber
Fajita Veggies:       1g fiber
─────────────────────────────────
Total:               17g fiber
```

### Toppings & Salsas

| Topping | Serving | Calories | Carbs | Notes |
|---------|---------|----------|-------|-------|
| Hand Crafted Guacamole | 2 oz | 80 | 5g | High in healthy fats |
| Hand Crafted Guacamole | 4 oz | 170 | 9g | Double portion |
| Pico de Gallo | 1 oz | 5 | 1g | Low calorie |
| Roasted Tomato Salsa | 1 oz | 5 | 1g | Low calorie |
| Salsa Verde | 1 oz | 10 | 0g | Zero carbs |
| Habanero Salsa | 1 oz | 10 | 2g | Spicy, low cal |
| Chile Corn Salsa | 1 oz | 25 | 5g | Moderate calories |
| Shredded Cheese | 1 oz | 110 | 1g | High protein |
| Sour Cream | 1 oz | 50 | 3g | Moderate calories |
| Three Cheese Queso | 2 oz | 80 | 3g | Lower cal than queso diablo |
| Queso Diablo | 2 oz | 90 | 3g | Spicy option |

---

## Burrito vs Bowl - Calorie Comparison

### Burrito vs Bowl Formula

```
Burrito Calories = Bowl Calories + Tortilla Calories
```

**Example:**

Chicken Queso:
```
Bowl:        750 calories
+ Tortilla:  300 calories (12.5")
─────────────────────────────────
Burrito:   1,050 calories
```

**Calorie Savings:**

```
Savings = Burrito Calories - Bowl Calories
Savings = 1,050 - 750 = 300 calories saved by choosing bowl
```

### Popular Comparisons

| Item | Bowl | Burrito | Difference |
|------|------|---------|------------|
| Chicken Queso | 750 cal | 1,050 cal | +300 cal |
| Cholula® Hot & Sweet Chicken | 610 cal | 910 cal | +300 cal |
| Double Protein - Chicken | 700 cal | N/A | - |

**Pro Tip:** Choosing a bowl over a burrito saves approximately 300 calories by eliminating the large flour tortilla.

---

## Vegan & Plant-Based Options

### Vegan Items (Marked with "v")

| Item | Calories | Protein | Fiber | Notes |
|------|----------|---------|-------|-------|
| Fajita Vegan Bowl | 530 | 17g | 22g | Complete meal |
| Black Beans (4 oz) | 140 | 9g | 14g | High fiber |
| Pinto Beans (4 oz) | 130 | 8g | 14g | High fiber |
| Cilantro Lime Rice (4 oz) | 190 | 3g | 1g | Vegan base |
| Seasoned Brown Rice (4 oz) | 170 | 4g | 2g | Whole grain |
| Plant-Based Impossible™ | 170 | 13g | 0g | Meat alternative |

**Building a Vegan Bowl:**

```
Base: Cilantro Lime Rice (190 cal)
Protein: Plant-Based Impossible™ (170 cal, 13g protein)
Beans: Black Beans (140 cal, 9g protein)
Toppings: Fajita Veggies (40 cal)
Salsa: Pico de Gallo (5 cal)
─────────────────────────────────────────────
Total: 545 calories, 22g protein, 19g fiber
```

---

## Sodium Tracking

Many Qdoba items are high in sodium. Here's how to calculate your meal's sodium:

```
Total Sodium = Protein Sodium + Rice/Bean Sodium + Topping Sodium + Sauce Sodium
```

**Example:**

```
Grilled Adobo Chicken:  440mg sodium
Cilantro Lime Rice:     390mg sodium
Black Beans:            330mg sodium
Shredded Cheese:        180mg sodium
─────────────────────────────────────────────
Total:                1,340mg sodium
```

**Daily Sodium Limit:** Most adults should stay under 2,300mg per day. One meal can easily exceed half your daily limit.

**Lower Sodium Options:**
- Pork Carnitas: 560mg (for 3.5 oz protein)
- Seasoned Brown Rice: 250mg (vs 390mg in cilantro lime)
- Pico de Gallo: 70mg (vs higher sodium salsas)
- Romaine Lettuce: 0mg (salad base)

---

## Beverage Calories

### Fountain Beverages

| Beverage | Size | Calories | Sugar | Carbs |
|----------|------|----------|-------|-------|
| Coca-Cola | Regular (20 oz) | 240 | 67g | 67g |
| Dr. Pepper | Regular (20 oz) | 250 | 65g | 67g |
| Sprite | Regular (20 oz) | 260 | 59g | 67g |
| Fanta Orange | Regular (20 oz) | 270 | 73g | 73g |
| Cherry Coca-Cola | Regular (20 oz) | 270 | 69g | 69g |
| Minute Maid Lemonade | Regular (20 oz) | 280 | 70g | 72g |
| Barq's Root Beer | Regular (20 oz) | 280 | 73g | 73g |
| Barq's Root Beer | Large (30 oz) | 430 | 110g | 110g |

### Bottled Beverages

| Beverage | Size | Calories | Sugar | Protein |
|----------|------|----------|-------|---------|
| Mexican Coke | 12 fl oz | 150 | 39g | 0g |
| Simply Orange Juice | 11.5 fl oz | 160 | 33g | 2g |
| Chocolate Lowfat Milk 1% | 8 fl oz | 160 | 24g | 9g |
| Honest Apple Juice Box | 6 fl oz | 40 | 9g | 0g |

**Calorie Savings Formula:**

```
If you skip a regular soda (240-280 calories) and choose water:
Daily savings: 240-280 calories
Weekly savings: 1,680-1,960 calories (nearly 0.5-0.6 pounds)
```

---

## Meal Planning Examples

### 500-Calorie Meal

```
Pork Carnitas (3.5 oz):     110 calories
Seasoned Brown Rice (4 oz): 170 calories
Black Beans (4 oz):         140 calories
Pico de Gallo (1 oz):         5 calories
Fajita Veggies (2 oz):      40 calories
─────────────────────────────────────────────
Total:                      465 calories
```

### 700-Calorie High-Protein Meal

```
Double Protein Bowl - Chicken: 700 calories, 51g protein
```

### 400-Calorie Keto Meal

```
Keto Bowl - Chicken: 400 calories, 33g protein, 4g net carbs
```

### Custom 600-Calorie Bowl

```
Grilled Adobo Chicken (3.5 oz):  190 calories
Cilantro Lime Rice (4 oz):       190 calories
Black Beans (4 oz):              140 calories
Hand Crafted Guacamole (2 oz):    80 calories
─────────────────────────────────────────────
Total:                           600 calories
```

---

## Allergen Information

### Allergen Codes

- **S** = Soy
- **E** = Egg
- **F** = Fish
- **M** = Milk/Dairy
- **P** = Peanuts
- **C** = Crustacean/Shellfish
- **T** = Tree Nuts
- **W** = Wheat
- **G** = Gluten
- **Se** = Sesame
- **(v)** = Vegan Product
- **\*** = May contain allergen

### Common Allergen Sources

**Wheat & Gluten (WG):**
- All flour tortillas
- Crunchy tortilla shells
- Tortilla chips
- Seasoned potatoes

**Milk (M):**
- All cheese (shredded, cotija, queso)
- Sour cream
- Picante ranch dressing
- Chocolate milk

**Eggs (E):**
- Eggs (breakfast items)
- Chile crema
- Picante ranch dressing

**Soy (S):**
- Plant-Based Impossible™
- Some dressings and sauces

**[Check Allergen Filters →](https://qdobanutrition.net/)**

---

## Data Source & Accuracy

This nutrition database is compiled from official Qdoba Mexican Eats nutrition information for 2025. All values are per standard serving size.

**Important Notes:**
- Serving sizes may vary slightly by location
- Nutritional content may vary because products are made to order by hand
- Calorie ranges for entrées are based on base ingredients
- Actual calories may vary depending on ingredient preferences and portion size
- Always consult healthcare professionals for personalized dietary advice

---

## How to Use This Repository

1. **Calculate Custom Meals:** Add up calories and macros from individual ingredients
2. **Find Keto Options:** Use Keto Bowls or build custom low-carb meals
3. **Track Protein:** Identify high-protein options for fitness goals
4. **Monitor Sodium:** Calculate total sodium to stay within daily limits
5. **Compare Options:** See calorie differences between bowls, burritos, and salads
6. **Plan Vegan Meals:** Use vegan-marked items to build plant-based meals

**[Use Our Interactive Calculator →](https://qdobanutrition.net/)**

The calculator automatically handles all formulas and provides instant results for any custom Qdoba meal combination.

---

## Quick Tips

1. **Choose bowls over burritos** to save ~300 calories (no large tortilla)
2. **Skip sugary drinks** to save 240-280 calories per meal
3. **Add vegetables** for fiber and nutrients with minimal calories
4. **Use Keto Bowls** for low-carb diets (under 10g net carbs)
5. **Double protein** if you need more protein without extra carbs
6. **Go vegan** with plant-based options marked with (v)
7. **Calculate before ordering** to stay within your calorie budget

---

## Disclaimer

Nutrition information is provided for informational purposes only. Actual values may vary based on preparation methods, serving sizes, location, and customizations. This data is not a substitute for professional medical or nutritional advice.

**For accurate, up-to-date calculations, visit [Qdoba Nutrition Calculator](https://qdobanutrition.net/).**

---

**Made for health-conscious Qdoba customers**

**[Calculate Your Custom Meal Now →](https://qdobanutrition.net/)**
