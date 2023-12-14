# The Guardian Popular Articles
### Project Overview

- This project is designed to retrieve and display the most recent articles from The Guardian newspaper as a list.
- Users can select any article to read it in a separate view.

### Features

* Navigation Drawer
* Fragments
* ViewPager plus TabLayout
* Loaders
* Intent
* Guardian API
* JSON Parsing
* Glide
* CardView
* RecyclerView
* SharedPreferences

***I/O Diagram***

![I/O](https://github.com/eldoma/Capstone-Vanderbilt-MOOC-Week-1/blob/main/Main_Activity.drawio.png)

***URL***
### API Key Note

Optional: You may need to insert your API key.
Go to a file named `Constants.java` and find the value of API_KEY.
Replace "test" with "YOUR-API-KEY".
```
public static final String API_KEY = "YOUR-API-KEY";
```
- In this project, use [Guardian API](http://open-platform.theguardian.com/documentation/). 
This API returns information in a JSON format.
