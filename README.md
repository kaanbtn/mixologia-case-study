# Mixologia — Case Study (iOS)

> Freemium iOS cocktail app built with SwiftUI. Codebase is private (App Store release), but this repo documents product scope, architecture, and demo materials.

## Snapshot
- 300+ global recipes with rich metadata (ABV, calories, tags, substitutions, i18n steps)
- 11 languages (EN, TR, IT, KO, JA, FR, ES, PT-BR, DE, zh-Hans, zh-HK)
- Advanced search (name / ingredients / tags / keywords)
- AI Builder: user enters any ingredients/flavors freely → generates 2–3 unique cocktail ideas per prompt (OpenAI API)
- My Bar inventory & “missing ingredients” UX
- Shopping list + share flow (e.g., WhatsApp)
- Curated Collections

## Tech Stack
- iOS: Swift, SwiftUI
- Backend/Content: Firebase (Firestore, Storage, Remote Config)
- User Data Sync: CloudKit
- Monetization: RevenueCat (weekly / monthly / annual)
- AI: OpenAI API (GPT-4o mini)

## Monetization (Freemium)
- Free: recipe browsing
- Premium: Collections, Shopping List, My Recipes beyond 1, Favorites beyond 3, AI Builder after 1 use

## Screenshots
<p float="left">
  <img src="assets/screenshots/01_home.png" width="240" />
  <img src="assets/screenshots/02_recipe_details1.png" width="240" />
  <img src="assets/screenshots/03_recipe_details2.png" width="240" />
  <img src="assets/screenshots/04_recipe_details3.png" width="240" />
  <img src="assets/screenshots/05_search.png" width="240" />
  <img src="assets/screenshots/06_builderpage.png" width="240" />
  <img src="assets/screenshots/07_ai_builder.png" width="240" />
  <img src="assets/screenshots/08_ai_builder2.png" width="240" />
  <img src="assets/screenshots/09_mybar.png" width="240" />
  <img src="assets/screenshots/10_shopping_list.png" width="240" />
  <img src="assets/screenshots/11_my_recipes.png" width="240" />
  <img src="assets/screenshots/12_paywall.png" width="240" />  
</p>

## Demo
Demo/TestFlight available upon request.

## Contact
- GitHub: https://github.com/kaanbtn
- LinkedIn: www.linkedin.com/in/kaanbutunley
