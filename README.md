'Kanban Board Application'
A dynamic Kanban board application built with React.js. It allows users to view and manage tasks grouped by status, priority, or user, while also displaying the of users assigned to tasks. The data is fetched from an external API and allows for real-time sorting and filtering of tasks.

'Features:'
Grouping Options: Tasks can be grouped by Status, Priority, or User.
Sorting Options: Tasks can be sorted by Priority or Title.
Responsive Design: Fully responsive design for mobile and desktop views.
Data Fetching: The application fetches task and user data from an external API.

'Tech Stack:'
React.js: Frontend library for building the UI.
CSS: Custom styles for responsive design and layout.
API: The app fetches tasks and user data from an external API endpoint.

'Project Structure'
The project has the following structure:

kanban-board/
│
├── public/
├── src/
│   ├── components/
│   │   ├── KanbanBoard.js       # The main Kanban board component
│   │   ├── TicketCard.js        # Component that renders individual task cards
│   ├── App.js                   # Main app component
│   ├── App.css                  # Global CSS for the project
│   ├── index.js                 # React entry point
│
├── package.json                 # Project dependencies and scripts
└── README.md                    # Project documentation

'Key Components'
App.js: The main entry point of the application. It fetches data from the API, manages the state for grouping and sorting, and renders the KanbanBoard component.
KanbanBoard.js: This component organizes and displays the task tickets based on the current grouping (status, priority, or user). It also handles sorting.
TicketCard.js: A presentational component responsible for rendering individual task cards.

'Getting Started'

'Prerequisites:'
Make sure you have the following installed:
Node.js: Ensure you have Node.js (>=12.x) installed.
npm: The Node.js package manager comes bundled with Node.js.

'Installation'
Clone the repository:
git clone https://github.com/Anushkaa32/kanban-board.git
Navigate into the project directory:
cd kanban-board
Install the dependencies:
npm install

'Running the App'
npm start

Screenshot of Output-



