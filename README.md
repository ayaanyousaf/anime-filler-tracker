# Anime Filler Tracker

Anime Filler Tracker is an application designed to streamline the anime-watching experience for users. It allows users to search for any anime name and be able to view an up to date list of all filler episodes of the series, as well as the percentage of filler episodes in the anime. Users can seamlessly view an entire list of filler episodes and decide which episodes to skip or watch.

A filler episode is an episode that contains content not present or canon in the source material, which is often manga for anime. The episodes are not relevant to the main storyline, but may provide additional backstory or development for certain side characters.

This application was built using Python. It utilizes BeautifulSoup for web scraping and data collection, as well as CustomTkinter to implement a modern and elegant graphical user interface (GUI).

**The website used by this application is [Anime Filler List](https://animefillerlist.com). <br>
Please note that only the shows listed on this site will be compatible with the application.**

![Project Showcase Gif](/public/anime_filler_tracker.gif)

## Installation 
1. Clone Repository
     ```
     git clone https://github.com/ayaanyousaf/anime-filler-tracker.git
     ```
2. Change directory
     ```
     cd anime-filler-tracker
     ```
3. Install dependencies
     ```
     pip install -r requirements.txt
     ```
4. Run application
     ```
     python filler_gui.py
     ```

## Usage 
1. Enter the name of an anime series in the search bar and click the `Search` button or press `Enter` to view results.
2. Click the `Clear` button to clear all text in the search bar and any previous output.
3. Receive feedback based on the type of error that occurred if the search was unsuccessful.

## Features
- **Searching:** Enter an anime series and quickly view all filler episode names and numbers.
- **Fuzzy Search:** Users have more freedom while searching and can make typos.
- **Enter Search:** The `Enter` key may be pressed to search instead of clicking the button.
- **Filler Percentage:** Users can view the percentage of filler episodes in the anime.
- **Clear Button:** Can clear text in the search bar and all previous output with the click of a button.
- **Error Handling:** Receive feedback on URL errors, episode retrieval errors, percentage retrieval errors, and unknown errors.

## Testing 
To run tests, ensure you have the pytest framework installed: 
```
pip install pytest
```
Then type the following command in your terminal: 
```
pytest test.py
```

## Technologies 
- Python
- BeautifulSoup (web scraping)
- customtkinter (designing GUI)
- requests (making HTTP requests)
- fuzzywuzzy (fuzzy search functionality)
- Pillow (image loading) 

## License 
This software is licensed under the [MIT License](LICENSE).
