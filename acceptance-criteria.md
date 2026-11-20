# Acceptance Criteria
<!--
Acceptance criteria tell you when a user story is DONE. Each one must be testable: pass or fail.
Write 2–3 criteria for every user story using this format:

Given [a situation], when [the user does something], then [this should happen].

Tips:
- Number them under their story: AC1.1 and AC1.2 belong to US1.
- Describe what the user SEES, not how the code works.
- Include at least one "what if it goes wrong" case per story (empty input, no results).
- Avoid vague words like "fast," "nice," or "easy." Could a classmate test it and agree it passed?

Example:
## US1: View today's menu
- AC1.1: Given I open the App page, when it loads, then I see each dish with its name, photo and price.
- AC1.2: Given no dishes are added yet, when I open the menu, then I see "No dishes today yet."

AC - Acceptance Criteria
-->

### Feature:  F1 Updates Dashboard
US1: As a user, I want to view news details in a single page, so that I can stay updated without checking multiple websites and social media platforms. 
- AC1.1: Each news item on the main page to display a headline, publication date, and short summary to scan recent F1 updates in one place.  
- AC1.2: News articles listed from newest to oldest, so that the most recent updates appear at the top.
- AC1.3: See a "No news updates available" message if no articles are loaded to know the page is working even without new content.

### Feature: Categorical Filtering
US2: As a user, I want to filter and switch between views by category, so that I can quickly browse the exact category of race content I need.
- AC2.1: See clickable buttons labeled News, Schedule, Results, and Standings to select a specific content section.
- AC2.2: Display only items matching the category I selected.
- AC2.3: A "No data available for this category" message if a selected section has no records yet (such as Results before the first race).

### Feature: Race Calendar
US3:  As a user, I want to view the race schedule in one place, so that I can easily check upcoming race dates.
- AC3.1: Each item in the schedule will display the Grand Prix name, circuit location, and race date.
- AC3.2: The next upcoming Grand Prix will appear at the top of the schedule with a "Next Race" badge to identify the upcoming race.
- AC3.3: Each race displays a status label of either "Upcoming" or "Completed," to know which races have already finished.

