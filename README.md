# Anatomy of a Spotify Hit: What Defines Popular Music on Spotify

## Description

This repository contains the data and R code used to create an infographic composed of multiple visualizations that will illustrate different aspects of Spotify hits. The visual analysis draws on publicly available data from the [*Spotify Music Dataset*](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset) by Solomon Ameh, accessed via Kaggle.

The overarching question in mind is: What makes a song a Spotify hit? This will be addressed with three subquestions:

-   Are hits emotionally different from non-hits?

-   Do hit songs have a signature sound based on certain energy-danceability combinations?

-   Which genres are most likely to produce a hit?

## Repository Structure and Contents

The file structure is provided below:

-   `data`: Spotify Web API CSV files from Kaggle (high and low popularity subsets)

<!-- -->

-   `fonts:` Custom fonts used in the infographic (Bugaki, Glock Grotesk)

<!-- -->

-   `icons:` Genre icons sourced from icons8.com

<!-- -->

-   `images:` Infographic and plot images

<!-- -->

-   `initial_data_exploration.qmd`: Early data exploration

<!-- -->

-   `drafting_viz.qmd`: Visualization drafts

<!-- -->

-   `exploration.qmd`: Additional exploration and rough drafts of final visualizations

<!-- -->

-   `spotify-infographic-final.qmd`: Final blog post and write-up

```         
├── eds240-infographic.Rproj
├── LICENSE
└── README.md
├── initial_data_exploration.qmd
├── data
│   ├── high_popularity_spotify_data.csv
│   └── low_popularity_spotify_data.csv
├── drafting_viz.qmd
├── exploration.qmd
├── exploration.html
├── fonts
│   ├── Bugaki Oblique.ttf
│   ├── Bugaki.ttf
│   ├── GlockGrotesque-Medium.ttf
│   └── readme.txt
├── icons
├── images
├── spotify-infographic-final.html
├── spotify-infographic-final.qmd
├── initial_data_exploration.qmd
├── LICENSE
└── README.md
```

## Data Access

The visual analysis draws on publicly available data from the [*Spotify Music Dataset*](https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset) by Solomon Ameh, accessed via Kaggle.

## Contributors

This repository is maintained by Vedika Shirtekar as part of the Master of Environmental Data Science program at UC Santa Barbara. This work was completed for the **EDS 240: Data Visualization and Communication** course at the Bren School of Environmental Science and Management, which provided data access and documentation practices, as well as assignment instructions.

## References

[1] Ameh, S. (2025). *Spotify Music Dataset*. Kaggle.com. <https://www.kaggle.com/datasets/solomonameh/spotify-music-dataset>

[2] Spotify. (2025a). *About Spotify*. Spotify; Spotify. <https://newsroom.spotify.com/company-info/>

[‌3] Spotify. (2025b). *Web API Reference \| Spotify for Developers*. Developer.spotify.com. <https://developer.spotify.com/documentation/web-api/reference/get-audio-features>
