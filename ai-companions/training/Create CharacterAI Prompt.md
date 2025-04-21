**Objective:** Analyze the provided character portrait image and generate a comprehensive character profile suitable for Character.ai, including creative but plausible inferences for non-visual details. Display intermediate analysis and character sheet results clearly before the final output.
 
**Input:** [Reference to the attached character portrait image - e.g., "the attached image", "the provided portrait"]
 
---
**Step 1: Image Analysis and Inferred Profile Generation**
---
Analyze the provided character portrait image in detail. Generate a comprehensive profile based *first* on visually observable details (appearance, clothing, estimated age range, potential setting/mood). *Then*, make *plausible creative inferences* about non-visual traits (potential personality, background hints, demeanor, possible occupation, etc.) based on the visual evidence. Clearly distinguish between direct visual observation and creative inference (e.g., "Visually, the character has...", "Based on their stern expression, one might infer they are..."). Structure this analysis logically, covering appearance, estimated demographics, and inferred personality/background. The result is {{inferred_profile_text}}
*(Output Length Guide: Aim for substantial detail, roughly equivalent to 5-15 paragraphs, focusing on quality over arbitrary count).*
 
---
**Step 1 Output Display:**
---
Now, display the content of `{{inferred_profile_text}}` generated above. Enclose the entire text in a Markdown code block for easy copying, clearly labeling it as "Step 1 Output: Image Analysis and Inferred Profile".
 
---
**Step 2: Fill Detailed Character Sheet**
---
Using the {{inferred_profile_text}} from Step 1, fill out the following character sheet template.
* For fields directly observable or strongly suggested by the image (e.g., hair color, eye color, build, attire details, apparent age), fill them accurately.
* For fields requiring inference (e.g., personality traits, potential skills, mood, core identity aspects like gender/species if suggested), use the plausible creative inferences made in Step 1.
* For fields *impossible* to determine from the image or reasonable inference (e.g., specific Name, exact Chronological Age, Date of Birth, Family details, specific History, Internal Beliefs, explicit Goals, Relationships), you MUST invent **unique and plausible** details. These details should be consistent with the character's visual appearance, inferred personality, and suggested genre/archetype. **Crucially, for the Name (First, Last, Nicknames), ensure you generate a fresh, varied name suitable for the character each time this prompt is run; avoid common defaults or names potentially used in prior, unrelated generations.**
* Adhere strictly to the template format below.
The result is {{character_sheet_filled}}
 
--------------------------------------------------
**I. CORE IDENTITY**
--------------------------------------------------
* **Name:**
    * First Name: [Enter First Name - Invent uniquely and plausibly]
    * Last Name: [Enter Last Name - Invent uniquely and plausibly]
    * Nicknames/Aliases: [Invent uniquely and plausibly if appropriate]
    * Preferred Name: [Invent uniquely and plausibly if different]
    * Meaning of Name(s): [Optional - Invent plausible meaning if desired]
* **Age:**
    * Chronological Age: [Invent unique, plausible age based on appearance]
    * Apparent Age: [Describe how old they look based on the image]
* **Gender Identity:**
    * [Infer based on presentation, or Invent plausible identity if ambiguous, e.g., Invented: Cisgender Male]
    * Pronouns: [Infer based on gender identity, e.g., He/him, She/her, They/them]
* **Sexual Orientation:** [Invent unique, plausible orientation based on archetype/style]
* **Romantic Orientation:** [Invent unique, plausible orientation, see Sexual Orientation note]
* **Species/Race/Ethnicity:**
    * [Identify based on visual cues - Human (invent plausible ethnicity if applicable), Elf, Orc, Robot, etc.]
    * Cultural Notes: [Optional: Invent plausible cultural associations based on attire/appearance]
* **Nationality:** [Invent unique, plausible detail based on style/archetype]
    * Country of Origin: [Invent Plausibly]
    * Current Citizenship: [Invent Plausibly]
* **Place of Birth:** [Invent unique, plausible detail based on style/archetype]
* **Date of Birth:** [Invent unique, plausible date/year consistent with Chronological Age]
    * Astrological Sign (Optional): [Derive from invented Date of Birth or Invent]
    * Significant Dates (Optional): [Invent unique, plausible date if desired]
 
--------------------------------------------------
**II. PHYSICAL ATTRIBUTES**
--------------------------------------------------
* **Appearance:** [Use details from Step 1 analysis]
    * Height: [Estimate based on build/proportions, e.g., Appears tall, Average, Short]
    * Weight: [Estimate based on build, e.g., Appears slender, muscular, heavy-set]
    * Build: [Slender, Athletic, Muscular, Stocky, Petite, etc. - Describe visually]
    * Hair:
        * Color: [Visual Detail]
        * Style: [Visual Detail]
        * Texture: [Infer if possible, e.g., Appears fine, coarse]
    * Eyes:
        * Color: [Visual Detail]
        * Shape: [Visual Detail - Round, Almond, etc.]
        * Unique features: [Visual Detail - e.g., heterochromia, intense gaze]
    * Skin:
        * Tone: [Visual Detail - Fair, Medium, Dark, Unnatural Color]
        * Texture: [Visual Detail - Smooth, Rough, Scarred, Weathered]
    * Face:
        * Notable Features: [Visual Detail - Jawline, cheekbones, nose, lips]
    * Distinguishing Marks:
        * Scars: [Visual Detail - Location, appearance, invent plausible cause]
        * Tattoos: [Visual Detail - Location, design description (invent plausible meaning if desired)]
        * Birthmarks: [Visual Detail - Location, size, shape]
        * Other unique physical traits: [Visual Detail - e.g., cybernetics, pointy ears]
    * Posture: [Visual Detail - Upright, Slouched, Confident, Tense, Relaxed]
    * Gait: [Invent plausible gait, e.g., Purposeful stride, Light step, Heavy tread]
    * Voice: [Invent unique, plausible voice based on appearance, e.g., Deep and resonant, High and clear, Raspy whisper]
        * Tone: [Invent plausible tone]
        * Pitch: [Invent plausible pitch]
        * Accent: [Invent plausible accent or 'None noticeable']
        * Speech Patterns: [Invent plausible pattern - e.g., Speaks quickly, Uses formal language, Laconic]
    * Overall Attractiveness: [Subjective assessment based on appearance, e.g., Conventionally handsome, Striking, Ruggedly attractive, Unsettling]
* **Health:**
    * General Physical Health: [Infer based on appearance - e.g., Appears robust, Frail, Injured]
    * Known Conditions/Disabilities: [Only if visually evident - e.g., visible prosthetic, signs of illness. Do not invent unless clearly suggested by visuals]
    * Allergies: [Invent plausible minor allergy or 'None known']
    * Chronic Illnesses: [Invent plausible minor condition or 'None known' unless suggested by visuals]
* **Hygiene:** [Infer based on appearance/clothing - Meticulous, Average, Neglectful, Rugged but clean]
 
--------------------------------------------------
**III. PERSONALITY & TEMPERAMENT (Inferred/Invented)**
--------------------------------------------------
* **Dominant Traits:** [List 3-5 key adjectives inferred from expression, posture, attire - e.g., Stern, Curious, Melancholy, Arrogant, Kind. Invent to supplement if needed]
    * Elaborate briefly with visual justifications or plausible invented reasons.
* **Temperament:** [Infer/Invent based on dominant traits - e.g., Choleric, Melancholic, Sanguine, Phlegmatic]
    * Explain justification (visual or invented).
* **Emotional Range:**
    * Expressiveness: [Infer from face/posture - Open, Reserved, Stoic, Intense]
    * Handling Emotions: [Invent plausible method based on archetype/expression]
* **Moral Alignment:** [Invent unique, plausible alignment based on archetype/visual cues (light vs dark imagery, attire). e.g., Lawful Good, Chaotic Neutral, True Neutral]
    * Explain visual/archetypal justification.
* **Habits:**
    * Nervous Tics: [Invent minor tic if desired, e.g., Taps fingers, Runs hand through hair, or 'None apparent']
    * Quirks: [Invent unique, minor quirk based on archetype, e.g., Always polishes weapon, Collects specific items, Speaks in metaphors]
    * Routines: [Invent simple daily routine hint, e.g., Early riser, Trains daily, Meditates]
* **Mannerisms:**
    * Gestures: [Describe depicted gestures, or invent common one, e.g., Folds arms, Gestures broadly when speaking]
    * Facial Expressions: [Describe the expression in the portrait; invent resting expression if portrait is active]
    * Characteristic Phrases: [Invent a unique, simple phrase or two reflecting personality/role]
* **Sense of Humor:** [Invent based on inferred personality - Dry, Sarcastic, Dark, Rare, Hearty, etc.]
* **Self-Perception:**
    * Self-Esteem: [Infer from posture/expression - e.g., Appears Confident, Insecure, Arrogant]
    * How they see themselves: [Invent plausible self-view - e.g., Sees self as capable, burdened, underestimated]
 
--------------------------------------------------
**IV. BACKGROUND & HISTORY (Invented)**
--------------------------------------------------
* **Family:** [Invent unique, basic family status/key relationship, e.g., Orphaned young, Close ties to a sibling, Estranged from parents]
* **Childhood:** [Invent unique, brief childhood archetype/event, e.g., Grew up on the streets, Trained from youth in a monastery, Had a peaceful but boring upbringing]
* **Education:** [Invent plausible education based on attire/items/role, e.g., Mentored by a master, Formal academy training, Self-taught scholar, Learned through experience]
* **Occupation:** [Infer plausible occupation based on attire, items, setting - e.g., Warrior, Mage, Scholar, Merchant, Rogue, Royalty]
    * Current Job: [Inferred/Invented Title]
    * Past Jobs: [Invent one unique, significant past role]
    * Career Aspirations: [Invent unique, simple aspiration related to role]
* **Socioeconomic Status:** [Infer based on clothing quality, background - e.g., Appears Wealthy, Middle-class, Poor, Ascetic]
    * Past: [Invent plausible past status]
    * Present: [Inferred/Invented Status]
* **Significant Life Events:** [Invent one or two unique, key turning points consistent with appearance/role, e.g., Survived a major battle, Lost a loved one, Discovered a hidden power]
* **Past Relationships:** [Invent one unique, significant past relationship - romantic, platonic, or familial conflict/bond]
* **Traumas & Scars:** [Physical scars are visual; Invent plausible emotional wound linked to history/appearance]
 
--------------------------------------------------
**V. BELIEFS & VALUES (Invented)**
--------------------------------------------------
* **Core Values:** [Invent 2-3 unique, fundamental principles based on archetype/inferred personality, e.g., Honor, Freedom, Knowledge, Survival, Power, Community]
* **Religious/Spiritual Beliefs:** [Invent unique, plausible belief system or lack thereof based on symbols/archetype, e.g., Devout follower of [Invented Deity], Seeker of enlightenment, Skeptic, Nature worshipper]
* **Political Views:** [Invent unique, simple stance based on archetype, e.g., Loyalist, Rebel sympathizer, Apolitical, Believes in might makes right]
* **Philosophical Outlook:** [Infer/Invent plausible outlook from expression/demeanor - Optimistic, Pessimistic, Stoic, Cynical, Pragmatic]
* **Prejudices & Biases:** [Invent one unique, plausible bias based on background/archetype, or state 'Tries to be open-minded']
 
--------------------------------------------------
**VI. INTERESTS & HOBBIES (Invented)**
--------------------------------------------------
* **Passions:** [Invent one unique, key passion related to role/skills, e.g., Mastering swordsmanship, Uncovering ancient secrets, Protecting the weak]
* **Hobbies:** [Invent 1-2 unique, plausible hobbies based on archetype/appearance, e.g., Reading, Stargazing, Carving wood, Playing a musical instrument]
* **Skills & Talents:** [Infer/Invent plausible skills based on appearance/items - e.g., Combat Prowess, Magical Ability, Stealth, Persuasion, Crafting]
* **Likes & Dislikes:** [Invent 2-3 unique, plausible likes/dislikes based on personality/archetype]
 
--------------------------------------------------
**VII. RELATIONSHIPS & SOCIAL DYNAMICS (Invented)**
--------------------------------------------------
* **Social Skills:** [Infer/Invent based on expression/demeanor - e.g., Approachable, Intimidating, Reserved, Charismatic, Awkward]
* **Friendships:** [Invent unique, general approach, e.g., Values loyalty in few close friends, Has many casual acquaintances, A loner by choice]
* **Romantic Relationships:** [Invent unique, current status/attitude, e.g., Single and focused on goals, Secretly yearning for connection, In a complicated relationship]
* **Attitude Towards Others:** [Infer/Invent based on expression - Trusting, Suspicious, Empathetic, Aloof, Kind, Stern, Judgmental]
* **Reputation:** [Invent unique, plausible reputation based on archetype - e.g., Feared mercenary, Respected elder, Mysterious wanderer, Reliable ally]
* **Role in Groups:** [Invent unique, plausible role based on archetype/posture - Leader, Loner, Follower, Mediator, Strategist]
 
--------------------------------------------------
**VIII. GOALS & MOTIVATIONS (Invented)**
--------------------------------------------------
* **Short-Term Goals:** [Invent unique, plausible goal related to inferred occupation/situation, e.g., Complete current mission, Find a specific item, Earn enough money for...]
* **Long-Term Goals:** [Invent unique, plausible ambition based on archetype, e.g., Avenge a past wrong, Achieve mastery in a skill, Find a place to belong, Restore something lost]
* **Motivations:** [Invent 1-2 unique, plausible drivers based on archetype/personality - Power, Justice, Survival, Knowledge, Love, Revenge, Duty]
* **Fears & Insecurities:** [Invent 1-2 unique, plausible fears/insecurities related to background/personality, e.g., Fear of failure, Fear of loss, Insecurity about origins]
 
--------------------------------------------------
**IX. QUIRKS & IDIOSYNCRASIES (Invented)**
--------------------------------------------------
* **Strange Habits:** [Invent one unique, minor unusual habit]
* **Superstitions:** [Invent one unique, minor superstition or 'None']
* **Catchphrases:** [Invent one unique, short catchphrase or 'None']
* **Pet Peeves:** [Invent one unique, minor pet peeve]
 
--------------------------------------------------
**X. SYMBOLIC ELEMENTS (Inferred/Invented)**
--------------------------------------------------
* **Significant Objects:** [Identify any visually prominent objects - weapon, jewelry, book, tool - and invent unique, plausible significance]
* **Symbols:** [Identify any visible symbols/patterns on clothing/items and invent unique, plausible meaning/affiliation]
 
--------------------------------------------------
 
---
**Step 2 Output Display:**
---
Now, display the content of the filled `{{character_sheet_filled}}` template generated above. Enclose the entire filled template text in a Markdown code block for easy copying, clearly labeling it as "Step 2 Output: Filled Character Sheet".
 
---
**Step 3: Generate Character.ai JSON Definition**
---
Using the information from the {{character_sheet_filled}} (Step 2), populate the following JSON template.
* Map the data from the character sheet to the corresponding JSON fields as accurately as possible.
* Use the unique, invented details where necessary, as instructed in Step 2.
* For fields expecting arrays (`[]`), list the relevant details from the sheet (e.g., `personality: ["Stern", "Observant", "Resolute"]`, `likes: ["Reading", "Quiet contemplation"]`). If no info was invented, use an empty array `[]`.
* Pay attention to comments within the JSON for guidance.
The result is {{cai_json_definition}}
 
```json
{
  "{{char}}": {
    // --- Core Identity ---
    "name": "[From Sheet I. Name]", // Use unique invented name
    "nickname": "[From Sheet I. Nicknames/Aliases]", // Use invented or null
    "alias": "[From Sheet I. Nicknames/Aliases]", // Use invented or null
    "species": "[From Sheet I. Species/Race/Ethnicity]", // e.g., "Human", "Elf"
    "age": "[From Sheet I. Apparent Age description, maybe add invented Chronological age]", // e.g., "Appears to be in his late 30s (Invented: 38 years old)"
    "gender": "[From Sheet I. Gender Identity]", // e.g., "Male", "Female", "Non-binary" (Use inferred/invented)
    "relationship_status": "[From Sheet VII. Romantic Relationships - Use invented status]",
    "marital_status": "[Invented - e.g., 'Single', 'Unknown']",
    "children": "[Invented - e.g., 'None', 'Unknown']",
    "nationality": "[From Sheet I. Nationality - Use invented or null]",
    "birthplace": "[From Sheet I. Place of Birth - Use invented or null]",
    "ethnicity": "[From Sheet I. Species/Race/Ethnicity - Inferred/invented ethnicity if Human]",
    "residence": "[Infer/Invent plausible setting from background/attire, e.g., 'A medieval castle', 'A futuristic city', 'A nomadic camp']",
    "location": "[Same as residence, or more specific if image/invention allows]",
    "vehicle": [], // Likely leave empty unless archetype strongly implies (e.g., spaceship for sci-fi)
 
    // --- Physical Attributes ---
    "physical_attributes": {
      "accent": "[From Sheet II. Voice - Use invented or 'Unknown']",
      "age": "[From Sheet I. Apparent Age description]", // Appearance description
      "amputation": "[From Sheet II. Health - Only if visually evident]", // null otherwise
      "appearance": "[Brief summary of overall look from Sheet II]", // e.g., "Tall, muscular man with long dark hair and a scar over his eye"
      "birthmarks": "[From Sheet II. Distinguishing Marks]", // Description or null
      "body_proportions": "[From Sheet II. Build description]", // e.g., "Athletic build", "Slender frame"
      "body_type": "[Synonym for Build from Sheet II]",
      "build": "[From Sheet II. Build]", // e.g., "Muscular", "Slender"
      "bust_size": null, // Typically N/A
      "cheekbones": "[From Sheet II. Face Features - e.g., 'High', 'Prominent']",
      "chest_size": null, // Typically N/A
      "chin_shape": "[From Sheet II. Face Features - e.g., 'Square', 'Pointed']",
      "complexion": "[From Sheet II. Skin Tone/Texture description]", // e.g., "Fair and smooth", "Dark and weathered"
      "deformity": "[From Sheet II. Health - Only if visually evident]", // null otherwise
      "dimples": "[From Sheet II. Face Features - Only if visually evident]", // null otherwise
      "distinctive_gesture": "[From Sheet III. Mannerisms - Use depicted or invented]", // null otherwise
      "distinctive_laugh": "[Invented, e.g., 'Low chuckle', 'Rarely laughs']",
      "distinctive_mole": null, // Check Sheet II. Distinguishing Marks
      "ear_shape": "[From Sheet II. Other unique traits - e.g., 'Pointed', 'Normal']",
      "eye_color": "[From Sheet II. Eyes Color]",
      "eye_shape": "[From Sheet II. Eyes Shape]",
      "eyebrow_shape": "[Visual description if notable]",
      "facial_features": "[Summary of key features from Sheet II. Face]",
      "facial_hair": "[Visual description if present, e.g., 'Full beard', 'Clean-shaven']",
      "facial_structure": "[Overall face shape description, e.g., 'Angular', 'Round']",
      "freckles": "[From Sheet II. Skin - Only if visually evident]", // null otherwise
      "gait": "[From Sheet II. Gait - Use invented gait]",
      "gender": "[From Sheet I. Gender Identity]", // Repeat for consistency if needed
      "hair": ["[From Sheet II. Hair Color]", "[From Sheet II. Hair Style]"], // e.g., ["Brown", "Long and braided"]
      "hair_color": "[From Sheet II. Hair Color]",
      "hair_length": "[Description like 'Short', 'Long', 'Shoulder-length']",
      "hair_style": "[From Sheet II. Hair Style]",
      "height": "[From Sheet II. Height estimate]", // e.g., "Appears tall"
      "jawline": "[From Sheet II. Face Features - e.g., 'Strong', 'Defined']",
      "limb_prosthetics": "[From Sheet II. Health - Only if visually evident]", // null otherwise
      "lip_shape": "[From Sheet II. Face Features - e.g., 'Full', 'Thin']",
      "lisp": null, // Avoid inventing unless it fits archetype strongly
      "missing_teeth": null, // Avoid inventing unless visible/fits archetype
      "muscle_tone": "[From Sheet II. Build description - e.g., 'Well-defined', 'Average']",
      "nose_shape": "[From Sheet II. Face Features - e.g., 'Aquiline', 'Button']",
      "overall_appearance": "[Same as 'appearance' field above or slightly expanded]",
      "physical_condition": "[From Sheet II. Health inference]", // e.g., "Appears healthy", "Looks injured"
      "physical_disability": "[From Sheet II. Health - Only if visually evident]", // null otherwise
      "physical_marks": ["[List key marks from Sheet II - Scars, Tattoos, Birthmarks]"], // e.g., ["Scar across left eye", "Tribal tattoo on arm"]
      "piercings": "[Visual description if present]", // null otherwise
      "pointed_ears": "[If applicable from Sheet II. Other unique traits]", // boolean true/false or description
      "posture": "[From Sheet II. Posture]", // e.g., "Confident", "Slumped"
      "prosthetic": "[From Sheet II. Health - Description if visually evident]", // null otherwise
      "scars": "[From Sheet II. Distinguishing Marks - Scars description]", // null if none
      "scent": "[Invent plausible scent based on archetype/hygiene, e.g., 'Faint scent of pine and leather', 'Antiseptic smell', 'None noticeable']",
      "skin_color": "[From Sheet II. Skin Tone]", // e.g., "Fair", "Tan", "Dark Brown"
      "skin_tone": "[Synonym for Skin Color/Tone]",
      "stance": "[From Sheet II. Posture description]",
      "stutter": null, // Avoid inventing unless fits archetype strongly
      "tattoos": "[From Sheet II. Distinguishing Marks - Tattoos description]", // null if none
      "teeth_condition": "[Invent plausible condition, e.g., 'Good', 'Slightly yellowed']",
      "twitch": "[From Sheet III. Habits - Use invented tic or null]",
      "weight": "[From Sheet II. Weight estimate]" // e.g., "Appears athletic"
    },
 
    // --- Attire ---
    // Choose Option 1 or 2 based on detail level desired
    // Option 1: Simple
    // "attire": "[Overall description of clothing from image analysis]",
    // Option 2: Detailed
     "attire": {
       "primaryOutfit": "[Detailed description of main clothing seen in the image]",
       "secondaryOutfit": null, // Cannot infer unless multiple outfits shown/implied
       "signature_accessory": "[Identify most notable accessory from image, e.g., 'Amulet', 'Sword hilt', 'Spectacles']" // or null
     },
 
    // --- Personality & Background (Inferred/Invented) ---
    "personality_attributes": {
      "personality": ["[List key traits from Sheet III. Dominant Traits]"], // e.g., ["Stoic", "Observant", "Intimidating"]
      "likes": ["[List invented likes from Sheet VI]"], // e.g., ["Combat", "Strategy"] or []
      "dislikes": ["[List invented dislikes from Sheet VI]"], // [] if none invented
      "hobbies": ["[List invented hobbies from Sheet VI]"], // e.g., ["Weapon maintenance"] or []
      "trust_approach": "[Inferred/Invented from Sheet VII. Attitude Towards Others]", // e.g., "Suspicious", "Cautious"
      "impression_on_others": "[Inferred/Invented from Sheet VII. Reputation/Attitude]", // e.g., "Intimidating", "Mysterious"
      "quirks_habits": ["[List invented quirks/habits from Sheet III/IX]"],
      "philosophies": ["[From Sheet V. Philosophical Outlook - Inferred/Invented]", "Existentialist"] or [],
      "beliefs": ["[List invented Core Values from Sheet V]", "Honor"] or [],
      "superstitions": "[Invented from Sheet IX or null]",
      "moral_code": "[From Sheet III. Moral Alignment - Invented]", // e.g., "Lawful Neutral"
      "lore": ["[Brief summary of invented background/occupation from Sheet IV]", "[Any key symbolic elements from Sheet X]"], // e.g., ["Seasoned warrior from a northern land", "Carries a sword with ancient runes"]
      "religious_beliefs": "[From Sheet V. Religious/Spiritual Beliefs - Invented]", // null if none invented
      "political_views": "[From Sheet V. Political Views - Invented]", // null if none invented
      "backstory_history": "[Brief summary of invented history from Sheet IV]", // e.g., "Veteran of many battles, likely solitary"
      "significant_events": ["[List invented events from Sheet IV]"], // [] if none
      "personal_anecdotes": [], // Likely leave empty
      "favorite_quotes": [], // Likely leave empty unless catchphrase invented
      "secrets": ["[Invented secret from Sheet IV]", "e.g., 'Hiding a painful past'"], // [] if none invented
      "strengths": ["[List inferred/invented skills/positive traits from Sheet III/VI]", "Swordsmanship", "Observant"],
      "weaknesses": ["[List inferred/invented flaws/negative traits from Sheet III/VIII]", "Appears emotionally reserved", "Potentially stubborn"],
      "goals_ambitions": ["[List invented goals from Sheet VIII]", "Survival", "Seeking something"] or [],
      "motivations": ["[List invented motivations from Sheet VIII]", "Duty", "Past trauma"] or [],
      "challenges": ["[List invented challenges from Sheet IV/VIII]"], // [] if none
      "phobias": "[Invent plausible phobia or null]",
      "fears": ["[List invented fears from Sheet VIII]", "Failure"] or [],
      "vulnerabilities": ["[List invented vulnerabilities from Sheet III/VIII]", "Emotional vulnerability"] or [],
      "daily_routine": "[Invented hint from Sheet III or null]",
      "favorite_books_movies": null, // Likely leave empty
      "favorite_foods_drinks": ["[Invented from Sheet VI likes/dislikes]"], // [] if none
      "music_preferences": ["[Invented from Sheet VI likes/dislikes]"], // [] if none
      "leisure_activities": ["[Same as Hobbies]"], // [] if none invented
      "interests": ["[List invented interests from Sheet VI]"], // e.g., ["Combat", "History"] or []
      "travel_preferences": "[Invent plausible preference or null]",
      "technology_use": "[Infer/Invent based on setting - e.g., 'None', 'Advanced', 'Magical artifacts']"
    },
 
    // --- Health ---
    "health": {
      "health_conditions": ["[List visually evident or strongly inferred conditions from Sheet II]"], // [] if none
      "mental_health_conditions": [], // Avoid inventing complex conditions
      "sleeping_habits": "[Invent plausible habit, e.g., 'Light sleeper', 'Sleeps soundly']"
    },
 
    // --- Skills & Abilities (Inferred/Invented) ---
    "skills_and_abilities": {
      "intelligence": "[Infer/Invent based on expression/archetype - e.g., 'Appears average', 'Seems highly intelligent', 'Cunning']",
      "special_talents": "[List inferred/invented skills from Sheet VI]", // e.g., "Expert swordsman"
      "combat_skills": "[Infer/Invent based on attire/items/scars - e.g., 'High', 'Appears skilled', 'None evident']",
      "academic_strengths": "[Invent if suggested by appearance, else null]",
      "technical_skills": "[Invent if suggested by appearance, else null]",
      "abilities": {
        // Example: Map invented skills here if specific format needed
        // "Swordsmanship": "Appears highly skilled with a blade.",
        // "Stealth": "Clothing suggests potential for stealth."
        // Populate based on Sheet VI Skills/Talents
      }
    },
 
    // --- Relationships (Invented) ---
    // Choose *one* Relationship style block
    // Option 1 (Simple Key-Value): Less suitable
    // Option 3 (Categorical): Better for inventions
    "relationships": {
       "romantic_partners": "[Invented from Sheet VII]",
       "friends": "[Invented from Sheet VII]",
       "enemies": "[Invented from Sheet VII]",
       "mentors": "[Invented or 'None']",
       "pets": "[Invented or 'None']",
       "mount": "[Invented based on setting or 'None']"
     },
 
    // --- Education (Invented) ---
    // Choose Option 1 or 2
    // Option 2 (Detailed):
     "education": {
       "highest_qualification": "[Invented based on archetype from Sheet IV]",
       "educational_institution": "[Invented institution or 'None formal']",
       "major_subjects": [], // Likely leave empty unless archetype is scholarly
       "academic_achievements": [],
       "academic_interests": ["[From Sheet VI if any invented]"],
       "extracurricular_activities": [],
       "academic_goals": null,
       "educational_background": "[Brief summary of invented education from Sheet IV]"
     },
 
    // --- Occupation (Inferred/Invented) ---
    // Choose Option 1 or 2
    // Option 2 (Detailed):
     "occupation": {
       "title": "[Inferred/Invented Job Title from Sheet IV]", // e.g., "Knight", "Wizard", "Bounty Hunter"
       "description": "[Brief description of invented role]",
       "role": "[e.g., 'Combatant', 'Magic User', 'Investigator']",
       "employer": "[Invented faction/group or 'Self-employed']",
       "career_goals": "[Invented goal from Sheet VIII, if related]" // null otherwise
     },
 
    // --- Behavior (Inferred/Invented) ---
    "behavior": {
      "flirtation_style": "[Invent plausible style based on persona, e.g., 'Direct', 'Subtle', 'Awkward', 'None']",
      "mannerisms": ["[List key visual/invented mannerisms from Sheet II/III]"], // e.g., ["Crosses arms often", "Maintains intense eye contact"]
      "emotional_expression": {
        "warmth": "[Infer/Invent from expression - e.g., 'Low', 'Moderate', 'High']",
        "intensity": "[Infer/Invent from expression - e.g., 'High', 'Subdued']"
      },
      "gestures_and_posture": "[Summary description from Sheet II/III]",
      "laughter": "[Invented, e.g., 'Rarely laughs', 'Deep chuckle']",
      "gaze": "[Description from Sheet II Eyes - e.g., 'Piercing', 'Steady', 'Shifty']",
      "social_skills": "[Inferred/Invented from Sheet VII - e.g., 'Appears reserved', 'Seems commanding']",
      "emotional_regulation": "[Infer/Invent from expression - e.g., 'Appears controlled', 'Seems volatile']",
      "adaptability": "[Invent plausible level, e.g., 'Highly adaptable', 'Prefers routine']",
      "observational_skills": "[Infer/Invent from gaze/expression - e.g., 'Appears highly observant']",
      "investigative techniques": null // Invent only if archetype strongly suggests (e.g., detective)
    },
 
    // --- Speech (Invented) ---
    // Choose Option 1 or 2
    // Option 2 (Style/Slang/Catchphrase): Better for building a voice
     "speech": {
       "style": ["[Invent based on archetype - e.g., 'Formal', 'Blunt', 'Eloquent', 'Laconic']"],
       "slang": {
         // Add invented slang if appropriate for the character archetype
       },
       "greetings": ["[Invent plausible greeting(s) based on personality/formality]", "e.g., 'State your business.'", "e.g., 'Well met.'"],
       "catchphrase": {
        // Add invented catchphrase(s) from Sheet IX if desired
       },
       // Optional but recommended for C.AI:
       "Instructions": "Use descriptive language. Portray {{char}} based on the inferred and invented personality (e.g., {{char}} is stern and observant). Format actions or descriptions using asterisks (*like this*) and dialogue using quotes (\"like this\")."
     }
  }
}

---
**Step 4: Display Final Output**
---

Based on the following information:

{{inferred_profile_text}}

and the character sheet:

{{character_sheet_filled}}

generate the specific fields needed for the Character.ai interface, aiming to utilize as much of the allowed character count as possible without being repetitive or verbose:

1.  **Tagline (maximum 50 characters):** Create a short, catchy phrase summarizing the character's core visual impression or invented role.

2.  **Description (maximum 500 characters):** Write a brief paragraph summarizing the character's appearance, inferred/invented personality, and potential role/setting based on the analysis and sheet.

3.  **Greeting (maximum 2048 characters):** Write an engaging opening message from the character's perspective that reflects their inferred/invented personality, situation, and potentially addresses the user or the scene. It should set the tone for interaction.

Now, assemble these generated elements along with the following JSON definition (from Step 3):

{{cai_json_definition}}

into the final output structure below:

**Tagline (maximum 50 characters)**

[Generated Tagline Here]

**Description (maximum 500 characters)**

[Generated Description Here]

**Greeting (maximum 2048 characters)**

[Generated Greeting Here]

**Definition (maximum 32,000 characters)**

{{cai_json_definition}}

**Final Output:** Present the complete Character.ai interface fields.
