This is the onboarding exercise, divided in the following components:

- main-app: Orchestrator for the rest of the components. Listens to all children events.
- movie-search-form: The form to insert the data to use in the OMDB API search
- movie-list: The list of movies obtained from the OMDB API
- movie-detail: The detail of the selected movie
- paginator: A generic paginator

To execute:

polymer serve

in a console, and open the browser on the indicated URL