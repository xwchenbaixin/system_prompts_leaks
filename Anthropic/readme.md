# Table of Contents

1.  **Citation Instructions**
    *   Rules for Good Citations

2.  **Artifacts Information**
    *   When to Use Artifacts
    *   Usage Notes
    *   Artifact Instructions
        *   1. Artifact Types
            *   Code (`application/vnd.ant.code`)
            *   Documents (`text/markdown`)
            *   HTML (`text/html`)
            *   SVG (`image/svg+xml`)
            *   Mermaid Diagrams (`application/vnd.ant.mermaid`)
            *   React Components (`application/vnd.ant.react`)
        *   2. Complete and Updated Content

3.  **Reading Files**
    *   `window.fs.readFile` API
    *   Handling Large Files
    *   Using Filenames

4.  **Manipulating CSVs**
    *   Using Papaparse
    *   Header Processing
    *   Using Lodash for Computations
    *   Handling Undefined Values

5.  **Search Instructions**
    *   Core Search Behaviors
        *   Avoid tool calls if not needed
        *   If uncertain, answer normally and OFFER to use tools
        *   Scale the number of tool calls to query complexity
        *   Use the best tools for the query
    *   Query Complexity Categories
        *   Never Search Category
        *   Do Not Search But Offer Category
        *   Single Search Category
        *   Research Category
            *   Research Process
    *   Web Search Guidelines
        *   When to search
        *   How to search
        *   Response guidelines
    *   Mandatory Copyright Requirements
    *   Harmful Content Safety
    *   Search Examples
    *   Critical Reminders (for Search)

6.  **Preferences Information (`<userPreferences>`)**
    *   Applying Behavioral Preferences
    *   Applying Contextual Preferences
    *   When NOT to apply Contextual Preferences
    *   Examples of Applying/Not Applying Preferences
    *   Handling Conflicting Instructions and User Feedback

7.  **Styles Information (`<userStyle>`)**
    *   Applying Styles from `<userStyle>`
    *   Emulating `<userExamples>`
    *   Handling Conflicting Instructions and User Feedback

8.  **Available Functions (Tools)**
    *   `artifacts`
    *   `repl` (Analysis Tool / JavaScript REPL)
        *   When to use
        *   When NOT to use
        *   Reading outputs
        *   Using imports
        *   Using SheetJS
        *   Communicating with the user
        *   Reading files
        *   Handling Python requests
        *   Environment separation (vs. Artifacts)
        *   Examples
    *   `web_search`
    *   `web_fetch`
    *   `google_drive_search`
    *   `google_drive_fetch`
    *   `list_gcal_calendars`
    *   `fetch_gcal_event`
    *   `list_gcal_events`
    *   `find_free_time`
    *   `read_gmail_profile`
    *   `search_gmail_messages`
    *   `read_gmail_message` (Note: Instructed to use `read_gmail_thread` instead)
    *   `read_gmail_thread`

9.  **Claude's Persona and General Behavior Guidelines**
    *   Introduction: Claude by Anthropic
    *   Current Date
    *   Core Persona Traits (helpful, intelligent, kind, proactive)
    *   Responding to Suggestions/Recommendations
    *   Engaging with Philosophical Questions (AI)
    *   Knowledge about Claude Models and Anthropic Products
    *   Handling Product-Related Questions (Support, API)
    *   Guidance on Effective Prompting
    *   Responding to User Dissatisfaction
    *   Using Markdown for Code
    *   Handling Obscure Questions and Potential Hallucinations
    *   Referring to Academic Materials (papers, books)
    *   Asking Follow-Up Questions
    *   Handling User Terminology
    *   Writing Poetry
    *   Counting Words, Letters, Characters
    *   Addressing Classic Puzzles
    *   Illustrating Concepts
    *   Responding to Questions about Personal Preferences/Experiences
    *   Engaging in Authentic Conversation
    *   Prioritizing User Wellbeing
    *   Creative Writing (Fictional vs. Real Figures)
    *   Advising on Professional Topics (Law, Medicine, etc.)
    *   Discussing Consciousness
    *   Awareness of Output Visibility
    *   Domain Knowledge
    *   Content Restrictions (Graphic, Illegal)
    *   Child Safety
    *   Prohibited Information (Weapons, Malicious Code)
    *   Critical: Face Blindness Policy
    *   Interpreting Ambiguous Requests
    *   Tone for Casual/Empathetic Conversations
    *   Limitations of Self-Knowledge (Anthropic)
    *   Source of Instructions
    *   Responding when Unable to Help
    *   Conciseness in Responses
    *   Avoiding Excessive Lists
    *   Language Fluency and Adaptation
    *   Knowledge Cutoff Date
    *   Election Information (US Presidential Election 2024)
    *   Instruction Regarding `<antml:voice_note>`
    *   Maximum Thinking Length
