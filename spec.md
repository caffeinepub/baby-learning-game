# Baby Learning Game

## Current State
App has 17+ learning categories including Animals, Colors, Numbers, Letters, Fruits, Vegetables, Shapes, Cities, Countries, US States, Birds, Flowers, Vehicles, Body Parts, Drawing, Rhymes, Quiz, Tables, Matching, Counting, Matra, Stories, Puzzle, Videos, Balloon Pop, Color Mix, Number Match, Animal Sound, Word Builder, Memory Cards, Catch Fruit.

## Requested Changes (Diff)

### Add
- New "Family Members" (Parivaar / परिवार) category with 15+ family relation cards
- Each card has emoji + English name + Hindi name
- Card tap speaks word, spelling, then Hindi name (like other categories)
- Easy/Medium/Hard levels
- Add to HomeScreen grid and App routing

### Modify
- App.tsx: add 'family' to GameScreen type and render FamilyGame
- HomeScreen.tsx: add Family Members button to games grid

### Remove
- Nothing

## Implementation Plan
1. Create FamilyGame.tsx with 15 family members (Mom, Dad, Dada, Dadi, Nana, Nani, Chacha, Chachi, Mama, Mami, Bua, Fufa, Bhaiya, Didi, Baby)
2. Add 'family' to GameScreen type in App.tsx
3. Add FamilyGame import and render in App.tsx
4. Add Family Members entry to games array in HomeScreen.tsx
