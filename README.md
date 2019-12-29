# Altitude TV & RSN Streaming

This repository contains the data for [this post on my blog](https://charlie.fish/altitude-tv-rsn-streaming/). Please read that for further information.

---

## FAQ

### What is the difference between the `data.numbers` and `data.csv` files?

Due to `csv` files not supporting merge cells, and other features such as cell highlighting, I exported a copy in a `csv` format. The data is identical for each.

### How did you determine the Random Zip Code field?

Using www.zip-codes.com I searched the city for the given market, and picked at random a ZIP code that looked to have the largest population. However, I did not spend a lot of time picking a ZIP code and it is very likely in some cases I chose a ZIP code that does not have the largest population. In the case of Denver, I selected the ZIP code for Pepsi Center (where both the NHL & NBA teams play), since it was the focus and purpose for this dataset.

### How was this data gathered?

All of this data was gathered manually and inputted into the spreadsheet.

### Why is this data only include NBA & NHL?

The purpose of this data was to gather information about why [this tweet](https://twitter.com/AltitudeTV/status/1207360118003621888?s=20) from Altitude TV is false and untruthful, and due to the fact that Altitude TV primarly broadcasts NBA & NHL games from their home teams, that was the focus for this dataset. If you would like to add more leagues and data, feel free to contribute and submit a pull request so others can benefit from a larger dataset!

### What should I do if I find a problem with the data, or have further questions about the dataset?

Raise an issue (or better yet, pull request) on this GitHub repository, or [contact me](https://charlie.fish/contact).

---

## Sources & Credit

- ZIP Code Lookup - https://www.zip-codes.com
- Sports Teams Markets - https://www.sportsmediawatch.com/nba-market-size-nfl-mlb-nhl-nielsen-ratings/
