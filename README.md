<!-- 

# Assignment

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.1.5.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page. -->













Health Tracker Application
This is an Angular-based application that helps users track their workouts. The application allows the user to add workouts, search, filter by workout type, and view the total workout progress in a chart. All the data is saved locally in the browser for persistent usage.

Features
Add Workout: Allows users to input workout name, type, and duration.
Search Workouts: Users can search workouts by name.
Filter by Type: Filter workouts based on their type (e.g., Gym, Yoga, Cycling, etc.).
Progress Tracking: Visualize workout progress through a bar chart that shows the total duration of each workout type.
Pagination: Workouts are displayed with pagination, showing a limited number per page.
Local Storage: All workout data is stored locally in the browser using localStorage to persist data across sessions.
Requirements
Angular CLI v15.x.x
Node.js v14.x.x or later
Setup
Clone the repository
bash
Copy
Edit
git clone https://github.com/jotkaur-6284/assign.git
cd assign
Install dependencies
bash
Copy
Edit
npm install
Run the project
Start the local development server:

bash
Copy
Edit
ng serve
After the server starts, open the browser and go to http://localhost:4200/ to view the app.

How It Works
Adding Workouts: Users can add a workout via the "Add Workout" section. They input the workout name, type (e.g., Gym, Yoga), and duration (in minutes).

Viewing Workouts: The "Health Tracker" page displays a list of added workouts. Users can search and filter these workouts by name and type. Pagination is also implemented to manage large lists of workouts.

Workout Progress: The "Progress" section provides a bar chart representing the total duration of workouts by their name. Clicking on a workout name shows its duration as a chart.

Local Storage: All the workout data entered by the user is saved in the browser’s localStorage. This ensures that the data is not lost when the page is refreshed or the browser is closed.

Structure
Health Tracker Component: Displays and manages the workout data with options for searching and filtering.
Add Workout Component: Allows users to add new workouts to the system.
Progress Component: Displays the progress of each workout in the form of a bar chart.