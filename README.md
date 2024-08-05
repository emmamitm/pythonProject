# Movie Recommender

Note that in order to use this program you need you download the dataset using the link below
[https://www.kaggle.com/datasets/asaniczka/tmdb-movies-dataset-2023-930k-movies?resource=download](url)

The dataset above has around 1 million movies. Note that you can specify the number of movies you want to search through. 

Make sure that the .csv file you get from the link above is in the same directory as all the python files.

We used Dash to create the web visualization. This allowed us to create an interactive web interface.

When running the main method you will get an image like the one below:

![image](https://github.com/user-attachments/assets/2f136d72-bc1f-41d1-bc03-99b02966bc3d)

After getting the IP address that dash uses click on that to access the web interface. This will lead you to the movie selector with an interface similar to the one below:

![Screenshot 2024-08-04 230358](https://github.com/user-attachments/assets/d5b4f5cf-538c-4dc5-a2a9-d010ae2260bb)
![Screenshot 2024-08-04 230414](https://github.com/user-attachments/assets/05a5934a-2a2d-4d83-9687-60a7e31f2160)

You change change the various parameters to filter different movies based on your preferences. The most importance aspect is choosing between using the Hashmap and the Red Black Tree. This will determine how efficient each of the data structures are at filtering. Note that the Red Black Tree displays in alphabetical order where the hashmap displays in a random order.

Here is a screenshot of the sample output:
![Screenshot 2024-08-04 230710](https://github.com/user-attachments/assets/a345d742-d435-4c2b-9609-1c95949e59b4)
