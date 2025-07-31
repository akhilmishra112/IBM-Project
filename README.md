# Project
Book Recommendation Bot

Overview

The Book Recommendation Bot is designed to interact with users and provide book recommendations based on different genres. This project utilizes a structured JSON configuration compatible with IBM Watson Assistant to interpret user intents and respond accordingly.

Features

Responds to user greetings.

Recommends books across multiple genres:

Fantasy

Historical Fiction

Dystopia

Memoir

Mystery

Psychology

Realistic Fiction

Science Fiction

Short Stories

Recognizes a wide range of phrases related to book recommendations.

Intents

greetings: Recognizes basic user greetings like "Hi", "Hello", "Hey".

book_recommendation: Detects requests for book suggestions in various phrasings such as:

"Recommend good books for Fantasy"

"Book recommendations for Memoir"

"Good Historical Fiction books"

Entities

book_genre: Custom entity supporting fuzzy matching and synonyms.

Example mappings:

"sci fi", "scifi" → Science Fiction

"obsession", "dream" → Fantasy

"memoirs", "autobiography" → Memoir

Dialog Nodes

Welcome: Introduces the bot and prompts the user to select a genre.

Boom Recommendation: Handles book recommendation intent.

Books by genre: Branches based on specific genre entities.

Genre-specific recommendations:

Fantasy: "The Graveyard Book by Neil Gaiman"

Psychology: "Brain on Fire by Susannah Cahalan"

Historical Fiction: "Black Water by Joyce Carol Oates"

Mystery: Randomized selection like "Sharp Objects by Gillian Flynn"

