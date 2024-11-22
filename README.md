Travel-Story: Share Your Most Memorable Travel Experiences!

Introduction:
  Welcome to Travel-Story, a platform where you can create and maintain a personalized travel blog. This application provides a seamless way to document your travel experiences around the    world.

Core Functionalities:

  1. Add Your Travel Stories
  Our web application enables you to add unlimited stories, where each story includes:
  Title: Name your travel experience.
  Date of Visit: When you embarked on your journey.
  Place of Visit: The destination of your adventure.
  Travel Story: Narrate your experience in detail.
  Memorable Picture: Upload the most cherished photo from your trip to bring your story to life.
  
  2. Update or Delete a Story
  Edit the details of your story anytime.
  Delete stories you no longer wish to keep.
  
  3. AI-Powered Enhancements
  Want to elevate your storytelling? Use our AI integration powered by Gemini API to:
  Refine your narrative.
  Rephrase your content to make it more engaging and impactful.
  
  4. Geolocation Mapping
  Automatically extract geographical coordinates for your destination using the Nominatim API.
  Plot your travel destinations as pins on a global interactive map using the React-Leaflet library.
  Visualize all your travel memories on a single map.
  
  5. Search Stories
  Search for stories by location on the home screen.
  Use the map to explore pinned locations and discover corresponding travel stories.

How to Run the Application:

  Clone the Repository:
  git clone https://github.com/your-repo/travel-story.git
  
  Connect to your MongoDB:
  To change connection string, go to backend->config.json and replace your respective mongoDB connection URL
  
  Add your gemini api:
  Add your respective gemini api key at frontend->src->pages->Home->AddEditTravelStory.jsx
  
  Install Dependencies:
  npm install
  
  Start the Application:
  npm start
  Access the Application: Open http://localhost:5173 in your browser.


Our Team:
We are a passionate group of developers who collaborated to bring Travel-Story to life. Meet our team: Ritik Madhav, Ronit H U, and myself Rakshith Mahesh

