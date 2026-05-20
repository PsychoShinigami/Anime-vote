OVERVIEW:
 -The application allows users to vote for their favorite anime—One Piece, Naruto, or Bleach.
 -It features a "one vote per system" rule enforced via browser local storage.
 -And provides real-time percentage calculations based on global results stored on a PythonAnywhere server.

MOTIVE:
 -This is a full-stack voting application designed to settle the ultimate debate: Who is the King of the Big Three?

TECH STACK:
 -Frontend: HTML5, CSS3, and JavaScript.
 -Backend: Python with the Flask framework and Flask-CORS for secure cross-origin requests.
 -Database: votes.json (Flat-file JSON storage) for lightweight, persistent data management.
 -Deployment: Hosted on PythonAnywhere for 24/7 availability.

KEY FEATURES:
 -Persistence: Uses localStorage to ensure that once a user votes, the buttons are locked and labeled "Voted" even after a page refresh.
 -Live Analytics: Fetches global vote totals from the server and calculates percentage shares for each anime dynamically.
 -Responsive UI: A dark-themed, sleek dashboard featuring high-quality anime iconography and an overlay voting system.
 -Error Handling: Robust backend logic to handle empty data files or missing information without crashing.

HOW TO RUN:
 -Click demo on project in Macondo event or go to "https://reaperly.com/Anime%20vote/"
 -Vote any anime by clicking on vote button and put your name there.
 -Then your vote will stored in backend and total vote and the anime vote will be increased.
