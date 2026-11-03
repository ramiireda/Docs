# Google Play Store Listing Guide - Kids Puzzle Game

Use this cheat sheet to quickly fill out the Google Play Console listing fields.

---

### 1. App Details

* **App name:** `Kids Puzzle Game`
* **Short description (80 chars max):**
  > Fun, colorful jigsaw puzzles for kids! 100 playful levels with animals & toys.
* **Full description (4000 chars max):**
  ```markdown
  Welcome to Kids Puzzle Game – the joyful, colorful jigsaw puzzle world crafted specially for toddlers, preschoolers, and young children!

  🧩 100 PLAYFUL PUZZLES ACROSS 10 THEMES
  Explore 10 delightful themes packed with vibrant, high-definition illustrations:
  🦁 Friendly Animals: Lions, elephants, puppies, and kittens!
  🏰 Magical Places: Castles, fairylands, and cozy houses!
  🚗 Colorful Vehicles: Fire trucks, race cars, and airplanes!
  🌈 Beautiful Nature: Rainbows, gardens, and sunny skies!
  🍭 Sweet Treats: Cupcakes, ice creams, and candies!
  🐠 Ocean Adventures: Whales, dolphins, and clownfish!
  🚀 Outer Space: Rockets, astronauts, and planets!
  🦖 Cute Dinosaurs: T-Rex, Triceratops, and playful dino friends!
  🧸 Toybox Fun: Teddy bears, building blocks, and trains!
  🦄 Fantasy World: Friendly dragons, unicorns, and fairies!

  ⭐ CHILD-FRIENDLY & INTUITIVE DESIGN
  • Simple drag-and-drop gameplay designed for small hands.
  • Visual icon navigation: Easy for toddlers to play independently without reading!
  • 100% unlocked from the start: Kids can freely pick any puzzle they love.
  • Gentle learning curve: Puzzles grow from 2x2 pieces up to 7x7 challenges.

  💡 HELPFUL HINT SYSTEM
  Stuck on a tricky piece? A friendly hint option is always available to snap pieces into place and keep frustration away!

  🛡️ 100% SAFE & FAMILY COMPLIANT
  • Compliant with the Google Play Families Policy and COPPA.
  • No personal data collection or account creation required.
  • Kid-directed, family-friendly advertising only.
  • Works completely offline for safe travel and peace of mind.

  Download Kids Puzzle Game today and watch your little ones smile, learn, and explore!
  ```

---

### 2. Graphics & Media Uploads

* **App Icon:** Upload [`assets/ui/app_icon.png`](file:///Users/ramy/my_mac/AntigravityProject/assets/ui/app_icon.png) (1024×1024, meets 512×512 reqs)
* **Feature Graphic:** Upload [`docs/feature_graphic_1024x500.png`](file:///Users/ramy/my_mac/AntigravityProject/docs/feature_graphic_1024x500.png) (Exactly 1024×500)
* **Phone Screenshots:** Capture 4–8 in-game screenshots showing:
  1. Main Category Grid (10 colorful cards)
  2. Level Selection Grid
  3. Active Puzzle Gameplay (2x2 piece snap)
  4. 50% Hint / Rewarded helper popup
  5. Victory Screen with 3 stars!

---

### 3. Policy & Questionnaire Answers

#### A. Target Audience & Content
* **Target Age Group:** Select **5 and under**, **6–8**, and **9–12**.
* **Appeal to Children:** "Yes" (Designed for Families).
* **Neutral Age Screen:** Not required if all content is directed to children.

#### B. Content Rating (IARC Questionnaire)
* **Category:** Game -> Puzzle / Trivia / Casual.
* **Violence / Blood:** No.
* **Fear / Horror:** No.
* **Sexuality:** No.
* **Language:** No.
* **Controlled Substances:** No.
* **Resulting Rating:** **PEGI 3 / ESRB Everyone / Everyone (E)**.

#### C. Data Safety Section
* **Does your app collect or share user data?** Select **No** (Zero personal data collected).
* All gameplay saves remain locally on the device (`user://kids_puzzle_save.cfg`).

#### D. Ads Declaration
* **Does your app contain ads?** Select **Yes**.
* All ads are served through Google AdMob with COPPA `tag_for_child_directed_treatment = true` and Max Ad Rating = `G`.

---

### 4. Release Keystore Backup Information

> [!CAUTION]
> **DO NOT LOSE YOUR KEYSTORE OR PASSWORD.** Google Play requires this exact keystore to sign every future update of your app.

* **Keystore File:** `keystore/kids_puzzle_release.keystore`
* **Keystore Alias:** `kidspuzzle`
* **Keystore Password:** `KidsPuzzle2026Key`
* **Key Password:** `KidsPuzzle2026Key`
* **Certificate SHA-1:** `BF:31:A7:DB:92:59:4F:5C:1E:FB:18:B9:9B:AB:9E:C2:39:81:CC:95`
* **Certificate SHA-256:** `86:FC:64:DC:69:0B:03:89:F8:C1:E4:BF:98:43:DC:2D:B7:5D:C0:45:9E:C0:A8:F3:9D:8D:8F:CC:F4:A7:DA:6C`
* **Valid Until:** Year 2054
