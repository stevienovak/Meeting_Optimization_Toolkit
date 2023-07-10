# Meeting_Optimization_Toolkit
Transforming traditional, time-consuming meetings into streamlined, data-driven collaborative sessions.  Automating the boring stuff

### Every new creation comes with a propelling story
Transforming traditional, time-consuming meetings into streamlined, data-driven collaborative sessions.  Automating the boring stuff

The backdrop as follows sets the backdrop of this toolkit creation. It perfectly captures the essence of a typical workday in the life of a Singaporean millennial. 

In a bustling metropolis like Singapore, where modernity and tradition coexist, a young consultant named Wei had just embarked on his professional journey with Delion - a fast-growing local tech startup. With only a couple of years of experience under his belt, Wei was handed a task that would demand more than just his technical skills.

Delion's board of directors consisted of a group of seasoned veterans - business tycoons, finance moguls, and tech entrepreneurs who had seen the city-state grow from a trading post to a global hub. The elderly directors, despite being revered for their wisdom and experience, had a distinct need to feel special, loved, and valued. As a young consultant, Wei's job was to ensure that the directors' opinions were always heard, that they never missed any meeting, and that they received all the necessary board meeting documents well in time. Wei's journey was not without challenges. With the fast-paced lifestyle that Singapore is known for, the elderly directors often found it difficult to keep up with the rapidity of modern communication channels. Moreover, the board members, being from an older generation, preferred traditional means of communication - personal interactions, phone calls, and physical documents sent by hand to their Good Class Bungolows (GCB). Wei was thus tasked with navigating this interesting dichotomy of a modern company led by traditionally inclined leaders.

Despite Wei's exceptional problem-solving ability and knack for innovation, he found himself in an inefficacious cycle. A significant portion of his talent was squandered on traditional methods of scheduling board meetings. He had to personally contact the secretaries of each board member, painstakingly ensuring that every hard copy diary reflected the correct time and date for the upcoming board of directors' meeting. Wei discovered that he was investing up to 10 hours a week solely in setting up meetings.

This was an exhaustive process that preceded even the most fundamental steps such as generating slides, documenting minutes, arranging for caterers, or liaising with the facility manager to ensure a pristine office environment before the esteemed guests' arrival. The paradox of his role was that Wei's proficiency in digital solutions and his proficiency in efficient resource allocation were underutilized, owing to the antiquated methods of operations. To streamline operations for professionals like Wei and to enhance resource efficiency, the deployment of a digital tool is indispensable. This tool, proficiently designed to aggregate attendance and collect stakeholder opinions prior to meetings, is a crucial stride towards productive and well-orchestrated gatherings.

### About the project
This project was developed for the core objective of optimizing meetings and enhancing efficiency in decision-making. It is to transform traditional, time-consuming meetings into streamlined, data-driven collaborative sessions by introducing an automated email-based voting mechanism.

The toolkit comprises a bot with four key functionalities:

1. send_email_to_recipient(): This function drafts and sends the meeting brief and agenda items via email to the participants, along with necessary attachments.
2. incoming_emails_handler(): Upon invocation, the bot scans the email inbox and extracts key data based on specific subject headers and item labels.
3. voting_results(votes): This function tabulates the extracted data, detailing the number of agreements and disagreements for each agenda item. It also highlights participants who voice disagreement.
4. analyze_votes(): A higher-level function that leverages both incoming_emails_handler() and voting_results(votes) to streamline the process.

In addition to these core functionalities, we developed two separate programs tailored to the client's meeting styles:

On-the-Spot Poll: This real-time voting system allows for dynamic decision-making within the meeting. Participants cast their votes during the meeting, and results are tabulated instantly, thus accelerating the decision-making process.

Poll with Delayed Response: This program offers greater flexibility. Participants receive an email (through send_email_to_recipient()) containing the meeting brief and agenda items. At their convenience, they can review the items and respond with their votes. The votes are subsequently tracked using incoming_emails_handler() and voting_results(votes). This approach minimizes interruptions to the work schedules of the participants.

The toolkit provides a flexible, data-driven solution that adapts to various meeting formats. Users can choose and customise code to best suit their needs, thereby enhancing meeting productivity and efficiency. Feel free to explore my codebase and contribute to the mission of revolutionizing the meeting culture.
