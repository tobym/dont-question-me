user hits landing page
user enters question
user enters answer options
user submits
backend saves question and associated poll
backend redirects user to results page
backend makes mechanical turk job
results page makes websocket connection to server and dynamically updates result charts and "number reporting" stats
mechanical turk job is really a page on our server that has the question and the ability to answer it (like a poll or google forms)
each mechanical turk job is specific to a given store. this is how the poll answer is linked back to the store
