# Tools

## Backlog Item management
As the number of backlog items grow beyond a dozen or so Agile teams quickly find they need a tool for managing them.

For a team to effectively manage their backlog they will need to capture:
| Field | Description | Type of Data |
|-------|-------------|--------------|
| Unique Identifier | Allows each backlog item to be uniquely distinguished from any other item. Employed by the system(s) used to manage the backlog item conversations and test cases, if managed separately. | Alphanumeric |
| Backlog Item Type | Backlog item types are commonly User Story, Defect, Theme/Epic, or Task | Text capturing the specific type |
| Backlog Item Content | The detailed content of the backlog item | Text |
| Priority | The ranking assigned by the Product Owner | Alphanumeric that will allow for sorting |
| Ownership | The teammate who is responsible for the item | Text |
| Iteration Assignment | Used to determine the backlog in which the item belongs or is planned. Typical values include 'Product' and specific iterations or releases. | Text |
| Estimate | The value associated with the backlog item's size estimate. Because estimates are employed during metric calculation, such as velocity and the burndown chart, the value must be numeric. | Numeric |
| Deployed Date | The date the backlog item was released  | Date and time |
| Conversation | See Backlog Item Conversations below| |
| Test case(s) | The test cases verifying the backlog item. | See Test Cases below |
| Due Date (Optional) | The date and time (optionally) the backlog item must be complete. | Date and time |


## Backlog Item Conversations
As details emerge from conversations, spurred by backlog items, between the Development Team, Product Owner, and subject matter experts it is imperative to capture the information. Because backlog items are progressively elaborated it is a best practice to capture the full historical record of the content.

Backlog item conversation detailed information to capture is:
| Field | Description | Type of Data |
|-------|-------------|--------------|
| Unique Identifier | Allows each conversation details to be uniquely identified. Employed by the system(s) used to manage the backlog item and test cases, if managed separately. | Alphanumeric |
| The Backlog Item | Backlog item to which the details apply, if the conversation details are stored and/or managed separately from the backlog items | The backlog item's unique identifier |
| Content | The current conversation details | text, images, diagrams, and etc. |
| Changes to the content | The conversation details at specific points in time | text, images, diagrams, and etc. |
| Version | The indicator of which revision is being displayed | A unique identifier typically a date and time or a numeric indicator |
| Author | Who authored or captured the conversation details | text |
| Deployed Indicator (Optional) | An indication of when the conversation details were deployed into production | Can be either a date and time or a software version number |
| Test Case(s) (Optional) | The test case(s) which verify the functionality of the backlog item per the conversation details | Data which allows the user to uniquely identify and find the test case(s) |

## Test Cases
Backlog items must be testable to ensure they were coded correctly and meets the user's criteria and expectations. Like backlog item conversations, it is a best practice to to capture the full historical record of the test case.
| Field | Description | Type of Data |
|-------|-------------|--------------|
| Unique Identifier | Allows each backlog item to be uniquely distinguished from any other item. Employed by the system(s) used to manage the backlog item and backlog item conversations, if managed separately. | Alphanumeric |
| Test Steps | The criteria and specific actions to perform during validation | A list with each item capable of storing text, images, diagrams, and etc. |
| The Backlog Item | Backlog item which the test case is verifying, if the test cases are stored and/or managed separately from the backlog items | The backlog item's unique identifier |
| Author | Who authored or captured the test criteria and steps | text |
| Version | The indicator of which revision is being displayed | A unique identifier typically a date and time or a numeric indicator |
| Changes to the test steps | The criteria and specific actions to perform during validation at specific points in time | A list with each item capable of storing text, images, diagrams, and etc. |
| Test Case Description | A brief description of the test case | Text |
| Relationship links to other test cases (Optional) | Allows for establishing relations between test cases such as parent/child | The test case's unique identifier |
