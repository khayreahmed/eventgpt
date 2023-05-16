# How it works

This project uses the OpenAI GPT-3 API (specifically, text-davinci-003) and Vercel Edge functions with streaming. It generates 5 event recommendations based on a MongoDB database stacked with current events around the world and user input, sends it to the GPT-3 API via a Vercel Edge function, then streams the response back to the application.
