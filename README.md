📊 About the Dataset
🎯 Context
This dataset brings together user preferences from 73,516 anime fans across 12,294 anime titles!
Each user can mark anime as completed and give it a ⭐️ rating — and this dataset is a collection of those ratings.

📁 Content
📄 Anime.csv
🆔 anime_id – Unique ID from myanimelist.net for each anime.

🎞️ name – Full title of the anime.

🎭 genre – Comma-separated list of genres (Action, Comedy, Romance... you name it!).

🎬 type – Format of the anime (TV, Movie, OVA, etc.).

#️⃣ episodes – Total number of episodes (1 if it's a movie 🎥).

⭐️ rating – Average rating (out of 10) based on user reviews.

👥 members – Number of people who’ve added this anime to their list.

📄 Rating.csv
👤 user_id – Anonymized user identifier.

🆔 anime_id – The anime that was rated.

⭐️ rating – Rating (from 1 to 10). A value of -1 means the user watched it but didn't leave a score.

🙌 Acknowledgements
Thanks to the 💙 MyAnimeList API for powering this dataset with anime details and user ratings!

💡 Inspiration
Can we build an anime recommendation engine 🎯 based solely on what users have watched and rated? Let’s find out! 🚀

Source: https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database?select=rating.csv
