# Renton Technical College CSI-246

<div align="center">  
    <img src="logo.jpg" alt="Logo">
    <h3 align="center">Independent Activity 1: Simple Game Inventory</h3>
</div>

## Task: Create a Basic Game Item System

In this activity, you'll create a simple system for managing game items using TypeScript. You'll apply the concepts you learned in Guided Activity 1 to create something fun!

### Setup

1. Create a new directory for your project
2. Initialize a new TypeScript project:
```bash
npm init -y
npm install --save-dev typescript @types/node
tsc --init
```

### Requirements

Create three TypeScript files that work together to make a simple game item system:

1. Create a file called `itemTypes.ts`:
   - Define an enum for ItemType (Weapon, Armor, Potion)
   - Define an interface for a basic game Item
   - Your item interface should include properties like:
     - name (string)
     - type (use your enum)
     - value (number)
     - Plus at least two more properties of your choice

2. Create a file called `items.ts`:
   - Create at least three different items using your interface
   - Include at least one of each item type
   - Export your items so they can be used in your main file

3. Create a file called `main.ts`:
   - Import your items
   - Create a function that prints item details
   - Create a function that compares two items (e.g., by value)
   - Test your functions with your created items
   - Add a simple inventory array of items and add some items to it.
   - Create a function that sorts the inventory array by item value ascending.
   - Create a function that sorts the inventory array by item value descending.

### Example Output

Your program should produce output similar to this (but with your own items):
```
Item Details:
Magic Sword (Weapon) - Value: 100
Steel Armor (Armor) - Value: 150
Health Potion (Potion) - Value: 25

Comparing Items:
Magic Sword is less valuable than Steel Armor
```

### Testing Requirements

Your code should demonstrate:
1. Use of TypeScript types and interfaces
2. Use of enums
3. Basic functions with type annotations
4. Import/export of types and values


### Submission Requirements

Submit:
1. Your three TypeScript files
2. A screenshot showing your code running
3. Create a commit with the comment Independent Activity 1 Complete
4. Push your changes to github


### Tips

- Review the interfaces section from Guided Activity 1
- Remember to use proper type annotations for parameters
- Test your code with different items
- Include comments explaining your code

If you have any questions about this assignment, please reach out to your instructor or TA for this course.
