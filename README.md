# **Fairy Tale Generator**

## **Description**

This Python script generates a randomly structured fairy tale using predefined grammar. The story follows a classic hero’s journey format, including an introduction, adventure, climax, and conclusion. The grammar consists of different components such as setting, protagonist, antagonist, trials, and resolution, which are randomly selected to create a unique story each time the script is run.

## **Features**

Randomly selects a protagonist and antagonist.

Generates a structured story with an introduction, body, and conclusion.

Uses recursive grammar-based sentence generation.

Ensures the protagonist and antagonist remain consistent throughout the story.

## **How It Works**

**Grammar Definition**:

The script defines a dictionary (grammar) containing different parts of the story.

Each key represents a part of the story (e.g., Intro, Body, Climax).

The values are lists of possible sentence structures, some containing placeholders ({Protagonist} and {Antagonist}) for dynamically inserting names.

**Random Selection**:

A protagonist and antagonist are randomly selected from predefined lists.

The script replaces {Protagonist} and {Antagonist} placeholders with these values.

**Recursive Sentence Generation**:

The generate_sentence function constructs the story by recursively replacing grammar rules with corresponding phrases.

The function ensures that major story components appear in a structured manner.

**Story Output Formatting:**

The generated story is printed in a structured format with clear paragraph separations.

## **Customization**

You can modify or extend the grammar dictionary to create different types of fairy tales.

Add new protagonist or antagonist options to generate more diverse stories.

Adjust the story structure by modifying how sections are combined.

Author

Created by Ryan Ng.
