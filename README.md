# Playlist Manager
![image](https://github.com/user-attachments/assets/b87cc24b-cca3-4486-98ff-a8b2940f87b9)


# Overview
This Python script is a simple playlist manager that allows users to add, view, update, and delete songs in a playlist. The playlist stores song details including title, artist, and genre.

# Features
Add Songs: Add new songs to the playlist with details such as artist and genre.
View Playlist: Display all songs in the playlist.
Update Songs: Modify existing song details, including artist and genre.
Delete Songs: Remove songs from the playlist.


# Functions
add_song(title, artist, genre)

Adds a song to the playlist if it doesn't already exist.
Prints a message confirming the addition or noting if the song is already in the playlist.
view_playlist()

Displays all songs in the playlist with their details.
Prints a message if the playlist is empty.
update_song(title, artist=None, genre=None)

Updates the details of an existing song.
Allows updating either the artist, genre, or both.
Prints a confirmation message or an error if the song is not found.
delete_song(title)

Removes a song from the playlist.
Prints a confirmation message or an error if the song is not found.


# Example Workflow
Adding Songs:

Add several songs to the playlist with add_song().
Viewing Playlist:

Use view_playlist() to see the current playlist.
Updating Songs:

Update the genre of a song with update_song().
Deleting Songs:

Remove a song from the playlist with delete_song().
Viewing Playlist After Updates/Deletion:

Use view_playlist() to check the playlist after making changes.


# License
This project is licensed under the MIT License. See the LICENSE file for details.

For any issues or suggestions, please contact the project maintainer.








