# Music-Recommedation-Algorithm

This is a music recommendation system that uses content-based filtering to suggest albums to the user based on their preferences and listening history.

## How it works

The system uses a dataset of albums and their features, such as genre, mood, tempo, artist, etc. The system also collects the user's ratings and feedback on the albums they listen to. Based on this information, the system computes a similarity score between each album and the user's profile, and recommends the albums with the highest scores.

## Features

- The system can handle both explicit and implicit feedback from the user.
- The system can recommend albums from different genres and artists, as long as they match the user's preferences.
- The system can update the user's profile and the recommendations in real time, as the user listens to more albums.

## Installation

To run this system, you need to install the following packages:

- pandas
- numpy
- scikit-learn
- flask
