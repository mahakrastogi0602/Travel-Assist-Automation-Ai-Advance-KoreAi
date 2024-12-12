Advanced Bot Automation Project: Implements dynamic entity amendments, multilingual support, API integrations, custom dashboards, and feedback mechanisms using Kore.ai's platform. Features include advanced task handling, analytics, and webhook integrations.
 
Advanced Bot Automation Project

This repository showcases the implementation of advanced configurations and features for a conversational AI bot built on the Kore.ai platform. The bot is designed to provide a seamless, dynamic, and multilingual user experience while integrating essential functionalities such as API support, dashboards, and feedback mechanisms.

Features Implemented

1. Dynamic Entity Amendments

	•	Objective: Enable users to amend input entities dynamically during a conversation.

	•	Implementation: Sub-intents allow users to modify existing entities via prompts or direct user utterances.

	•	Demonstration: The bot adapts entity values based on user corrections or re-prompts.

2. Custom Dashboards

	•	Widgets Added:

	◦	Dialog tasks and FAQ counts displayed date-wise.

	◦	Language-wise incoming and outgoing message counts.

	•	Purpose: Visualize key bot metrics for improved analytics and decision-making.

3. Multilingual Enablement

	•	Language Added: [Insert language, e.g., Spanish].

	•	Task Adaptation: Translated prompts and bot responses using content variables for consistency.

	•	NLP Training: Trained bot with task-specific utterances in the newly enabled language.

	•	FAQs: Added and tested FAQs in the new language.

4. API Integration

	•	Get ChangeLogs API:

	◦	Used to retrieve bot's change logs programmatically.

	◦	Demonstrated API integration using Postman.

5. Feedback Survey (NPS)

	•	Objective: Collect user feedback after selected tasks to gauge user satisfaction.

	•	Implementation: Created an NPS survey, integrated it at the end of specific tasks, and generated a feedback report.

6. "Raise Issue" Task

	•	Purpose: Allow users to report concerns categorized into tasks, FAQs, user experience, incorrect responses, or general issues.

	•	Trigger: Automatically initiated when users express dissatisfaction (e.g., "unhappy" or "not satisfied").

	•	Dashboard: Custom widget tracks date-wise initiation counts of the task.

7. Webhook Channel Integration

	•	Integration: Enabled webhook channel to allow task triggering through API requests.

	•	Demonstration: Showcased API interaction with Postman, triggering tasks and receiving responses.

Prerequisites

	1	Kore.ai developer account with access to the bot.

	2	Tools: Postman, Kore.ai platform, and API documentation.

	3	Understanding of NLP training and bot workflows.

