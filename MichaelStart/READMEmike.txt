================================================================================
MICHAEL'S GUIDE TO AI-ASSISTED GAME DEVELOPMENT
================================================================================
Welcome! This guide will help you understand how to work with AI assistants
(Claude and Gemini) for your game development project.
================================================================================

TABLE OF CONTENTS
-----------------
1. What AI Can Do For You
2. What AI Cannot Do
3. Getting Started (Your First Steps)
4. How to Talk to AI Assistants
5. Your Workflow
6. Document Guide
7. Tips for Success
8. Common Questions

================================================================================
1. WHAT AI CAN DO FOR YOU
================================================================================

Think of AI assistants like having a knowledgeable colleague available 24/7
who can discuss ideas, explain concepts, and help you think through problems.

DESIGN ASSISTANCE:
- Brainstorm game mechanics and features
- Review your GDD and suggest improvements
- Help balance game systems (economy, difficulty, progression)
- Discuss player experience and game flow
- Compare approaches: "What if I did X instead of Y?"

LOGIC & PROBLEM-SOLVING:
- Break down complex systems into manageable pieces
- Explain algorithms (pathfinding, collision, state machines)
- Help you think through edge cases
- Discuss data structure choices
- Review your pseudocode or logic flow

DOCUMENTATION:
- Help organize your design documents
- Suggest what to document and how
- Review technical specifications
- Track bugs and feature requests

LEARNING:
- Explain unfamiliar concepts
- Compare to GameMaker/Unity equivalents you already know
- Provide examples and analogies
- Answer "why" questions about best practices

================================================================================
2. WHAT AI CANNOT DO
================================================================================

IMPORTANT LIMITATIONS:

- AI CANNOT see your screen or your actual code files (unless you paste them)
- AI CANNOT run your game or test it
- AI CANNOT remember previous conversations (each session starts fresh)
- AI CANNOT access the internet in real-time for latest updates
- AI may occasionally be wrong - always verify critical information

FOR YOUR PROJECT SPECIFICALLY:
- AI will NOT write code to insert directly into your project
- AI will provide EXPLANATIONS and EXAMPLES for learning
- YOU will implement all final code yourself

================================================================================
3. GETTING STARTED (YOUR FIRST STEPS)
================================================================================

STEP 1: Fill Out Initial.txt
----------------------------
Before anything else, open Initial.txt and answer all the questions.
This tells the AI what you're working on and what you need help with.
Be as detailed as you like - more context = better assistance.

STEP 2: Start a Conversation
----------------------------
Open Cursor and start a new chat with Claude or Gemini.
Your first message should be something like:

    "Please read README.txt and Initial.txt to understand my project.
    Then let's discuss [specific topic you want help with]."

STEP 3: Work Through Your Documents
-----------------------------------
The AI will help you fill out:
- GDD.md (your game design)
- TDD.md (your technical approach)

These documents become your project bible - update them as you go.

================================================================================
4. HOW TO TALK TO AI ASSISTANTS
================================================================================

BE SPECIFIC:
    LESS EFFECTIVE: "Help me with my game"
    MORE EFFECTIVE: "I need help designing a save system for my RPG.
                    Players should be able to save anywhere, and I need
                    to track inventory, quest progress, and player stats."

PROVIDE CONTEXT:
    LESS EFFECTIVE: "Why isn't this working?"
    MORE EFFECTIVE: "I'm implementing a state machine for enemy AI.
                    When the enemy transitions from PATROL to CHASE,
                    sometimes it gets stuck. Here's my logic: [explain]"

ASK FOR COMPARISONS:
    "How would this work compared to GameMaker's state machine approach?"
    "In Unity, I would use a ScriptableObject for this. What's the equivalent
    concept I should use in my C++ implementation?"

ASK FOR BREAKDOWN:
    "Can you break down how a dialogue system works into smaller pieces?"
    "What are the main components I need for an inventory system?"

ASK "WHY":
    "Why would I use a hash map instead of an array here?"
    "Why is this pattern better for game saves?"

================================================================================
5. YOUR WORKFLOW
================================================================================

DAILY WORKFLOW:
---------------
1. Open your project in Cursor
2. Start a chat with Claude or Gemini
3. Tell the AI to read your documents (README.txt, Initial.txt, etc.)
4. Discuss what you're working on today
5. Update your documents as needed (GDD, TDD, BUG-LOG)
6. Implement in your actual project (Visual Studio, etc.)

WHEN YOU HIT A PROBLEM:
-----------------------
1. Log it in BUG-LOG.md with details
2. Discuss with AI: "I have a bug logged in BUG-LOG.md, entry #X.
   Can you help me think through what might be causing this?"
3. Work through the logic together
4. Update BUG-LOG.md with the solution

WHEN DESIGNING A NEW FEATURE:
-----------------------------
1. Discuss the concept with AI first
2. Update GDD.md with the design
3. Update TDD.md with technical approach
4. Break it into tasks
5. Implement step by step

================================================================================
6. DOCUMENT GUIDE
================================================================================

Initial.txt (FILL THIS FIRST)
-----------------------------
Your project description. Answer the questions to give AI context about:
- What your game is
- Where you are in development
- What you need help with

GDD.md - Game Design Document
-----------------------------
Similar to Unity/GameMaker design docs. Contains:
- Game concept and vision
- Core mechanics
- Player progression
- Story/narrative
- Art and audio direction
- UI/UX design

TDD.md - Technical Design Document
----------------------------------
Your technical blueprint. Contains:
- System architecture
- Core systems breakdown
- Data structures
- State management
- Platform requirements

BUG-LOG.md - Bug Tracking
-------------------------
Like a simple issue tracker. Log:
- Problems you encounter
- Features to modify
- Solutions found

ASSET.md - Asset Inventory
--------------------------
Track all your game assets:
- Graphics and sprites
- Animations
- Sound effects and music
- UI elements

================================================================================
7. TIPS FOR SUCCESS
================================================================================

START EACH SESSION WITH CONTEXT:
AI doesn't remember previous conversations. Always start by having it read
your documents so it understands your project.

KEEP DOCUMENTS UPDATED:
Your GDD, TDD, and BUG-LOG are your project memory. Update them regularly
so AI (and you) always have accurate context.

ONE TOPIC AT A TIME:
Focus conversations on specific problems. If you switch topics, it's often
better to start a new chat.

VERIFY IMPORTANT INFORMATION:
AI is helpful but not infallible. For critical architecture decisions,
do your own research to confirm.

USE AI FOR THINKING, NOT TYPING:
The goal is to help you think through problems, not to generate code.
The understanding you gain is more valuable than any code snippet.

ITERATE:
If an explanation doesn't make sense, say so. Ask for:
- A different analogy
- A simpler breakdown
- A GameMaker/Unity comparison
- A concrete example

================================================================================
8. COMMON QUESTIONS
================================================================================

Q: "Should I paste my actual code into the chat?"
A: You can paste code snippets if you want help understanding logic issues.
   The AI will analyze and discuss, not rewrite it for you.

Q: "How do I know which AI to use - Claude or Gemini?"
A: Both can help with most tasks. Try both and see which style you prefer.
   Claude tends toward project management; Gemini toward technical details.

Q: "What if the AI gives wrong information?"
A: It happens occasionally. If something seems off, ask the AI to explain
   its reasoning, or verify independently. Trust your 30 years of experience.

Q: "Can I use AI while coding in Visual Studio?"
A: Yes! Have Cursor open alongside Visual Studio. Use AI for discussion
   and reference while you implement in your familiar environment.

Q: "How detailed should my questions be?"
A: More detail = better answers. Include: what you're trying to do,
   what you've tried, what's not working, and relevant context.

================================================================================
READY TO START?
================================================================================

1. Open Initial.txt
2. Answer all the questions
3. Start a chat and say: "Read README.txt and Initial.txt, then let's begin"

Good luck with your project!

================================================================================
END OF GUIDE
================================================================================
