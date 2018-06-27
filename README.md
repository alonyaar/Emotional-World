# Emotional World

[Enter the map](https://alonyaar.github.io/Emotional-World) - **Works best on Google Chrome!**

---

- The project maps 53 languages by comparing their daily use of approx. 100 words
  that deals with emotions, feelings and experiences

- I used [this database](http://worldlex.lexique.org/) to calculate the frequency
  of the words in each language. Then, by translating the words to 60 languages I
  found their frequency in Twitter, Blogs & Newspapers and created a 60X100 matrix
  with the frequency of each word for each language.

- By reducing the dimensions of that matrix using **PCA and T-SNE**, I achieved the
  2D map.

- The interface offers four different perspectives over the results - **Flags**, **Geographical**, **Language Families** & **Happy Planet Index**, each one of them
  may explain the proximity of languages.

- Additional info was added for each language:
  - Unique Word: Is the most commonly used emotional word for this language.
  - Words most used by this language: The words that are uniquely used when compared to other languages.
  - Countries speaking this language.
  - The language family that this language belongs to.