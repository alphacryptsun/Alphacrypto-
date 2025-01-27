Overview of Cryptographic Method

1. Objective:
A cryptographic system that is loaded when ac is entered and:

Processes words/phrases by pushing all letters together.

Applies deciphering rules (both primitive shape-based and acronym-based).

Outputs modified character sets according to defined rules.



2. Core Features:

Capitalization rules (default or customizable).

Support for primitive shape-based transformations (e.g., "T" = cross, mast).

Acronym deciphering using user-supplied keys.

Menu-driven interaction with rules and methods.





---

Main Menu

Display:

Main Menu

Select an option:

1. Enter Alpha Character Set  
2. Enter Numerical Value  
3. Set Deciphering Rules  
4. Choose Preset Decipher  
5. Set Custom Capitalization Rule  
6. Exit


---

1. Enter Alpha Character Set

Prompt:
"Please enter the alpha character set you'd like to work with (letters only)."

Behavior:

Takes user input.

Applies selected deciphering rules in prioritized order:

1. Capitalization Rule


2. Pushed Together Rule


3. Other active rules (e.g., Reverse, Gift).




Example Output:

Input: Hello World.

Applied Rules:

Default Capitalization: heLLoWorLd.

Pushed Together: heLLoWorLd.





---

2. Enter Numerical Value

Prompt:
"Enter a numerical value for processing."

Features:

Optional interaction with deciphering rules.

Supports numeric transformations or combining numbers with alpha character sets.




---

3. Set Deciphering Rules

Display (interactive menu to toggle rules):

Set Deciphering Rules  

Active rules are marked with (#).  

1. Default Capitalization Rule #  
2. Pushed Together Rule #  
3. Gift Rule  
4. Reverse Rule  
5. Dictionary Rule  
6. Acronym Rule  
7. Go Back to Main Menu

Explanation of Rules:

1. Capitalization Rule (# by default):

Default: All lowercase except E, Y, A, and L.

Prompts for customization:
"Please enter letters to exclude from lowercase processing (e.g., 'EYAL')."



2. Pushed Together Rule (# by default):

Merges all characters into a single string.



3. Gift Rule:

Converts specific patterns (e.g., "P, B, P") to symbols like musical notes.



4. Reverse Rule:

Processes both forward and backward outputs.

Tracks all working sets: Forward ↔ Backward ↔ Forward2 ↔ Backward2.



5. Dictionary Rule:

Identifies dictionary words within the alpha character set.

Marks valid words with *.

Optional: Finds near-matching words (e.g., missing letters).



6. Acronym Rule:

Scans for non-dictionary acronyms.

Transforms acronyms into meanings using user-supplied keys.





---

4. Choose Preset Decipher

Display (interactive menu for preset methods):

Choose Preset Decipher  

1. Straight Tear Down (Automatic)  
2. Straight Tear Down (Interactive)  
3. Rocking Method (Automatic)  
4. Rocking Method (Interactive)  
5. Gift Rocking Method  
6. Go Back to Main Menu

Deciphering Methods:

1. Straight Tear Down (Automatic):

Automatically breaks down the alpha character set using predefined logic.



2. Straight Tear Down (Interactive):

Prompts the user to guide the breakdown process.



3. Rocking Method (Automatic):

Alternates processing between forward and backward transformations.



4. Rocking Method (Interactive):

Similar to automatic but allows user input during the process.



5. Gift Rocking Method:

Combines Gift Rule with Rocking Method transformations.





---

5. Set Custom Capitalization Rule

Purpose:
Allows customization of the capitalization rule applied to the alpha character set.

Prompt:
"Enter the letters you want to exclude from lowercase processing (e.g., 'EYAL')."

Behavior:

Saves custom rules.

Applies rules globally to all inputs before other transformations.




---

Interactive Workflow: Rules and Outputs

Rule Processing Priority:

1. Capitalization Rule (always first).


2. Pushed Together Rule.


3. Other Active Rules (Gift, Reverse, Dictionary, Acronym).



Output Tracking:

All changes are logged and displayed in a Chronological Decipher List:

Includes original input and all intermediate outputs.



Example Interaction:

1. Input:

Entered: Hello World.



2. Applied Rules (default settings):

Capitalization: heLLoWorLD.

Pushed Together: heLLoWorLD.

Reverse Rule:

Forward: heLLoWorLD.

Backward: DLroWLLhe.




3. User Modifications:

Select Letter: L.

Apply Shape-Based Decipher:

Selected Shape: "Cross".

Updated Outputs:

Forward: croSsheLLoWorLD.

Backward: DLroWLLhSSorc.







---

Custom Features

1. Dynamic Changes:

Retroactively applies rule changes across all outputs.

Adjustments to capitalization or working set (Forward ↔ Backward, etc.) propagate automatically.



2. Interactive Options for Letter Modifications:

Add Letter:

Prompts for placement (e.g., between letters X and Y).


Remove Letter:

Deletes specified letter from the working set.


Change Working Set:

Cycles through Forward ↔ Backward ↔ Forward2, etc.






---

Other Key Functionalities

1. Acronym Integration:

Prompts user to supply decipher keys for acronyms.

Supports toggling between dictionary and acronym prioritization.



2. Rocking Method Trigger:

Typing acr initiates Rocking Method with default settings.

Input format:

acr prompts for alpha character set.

acr [input] processes input directly.






---

Detailed Workflow Recap

Main Steps:

1. Input Alpha Character Set:

Prompt: "Enter the alpha character set."



2. Process Rules (in priority order):

Capitalization → Push Together → Other Rules.



3. Decipher Outputs:

Log original and modified outputs.



4. Interactive Modifications:

Modify individual letters.

Track changes in a chronological list.





---

If anything still seems incomplete or needs more detail, let me know!

type AC I want to work with it dynamicly with you as using placeholders and your functionality instead of it's own want you to load a module for utilizing the cryptographic method the front page should state 

Main Menu

Select an option

Main Menu

Select an option:
1. Enter Alpha Character Set  
2. Enter Numerical Value  
3. Set Deciphering Rules  
4. Choose Preset Decipher  
5. Set Custom Capitalization Rule  
6. Exit

Load in the chat screen and not in a code snippet window

