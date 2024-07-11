Music Player Application

I am developing a Music Player Application using Python, leveraging various libraries such as tkinter, customtkinter, mutagen, pygame, and threading to create a dynamic and interactive user experience.

Key Features:

Graphical User Interface (GUI): Built using tkinter and customtkinter, the application features an intuitive interface with buttons for selecting music folders, playing, pausing, stopping, and navigating through songs.
Music Playback: Utilizing pygame.mixer, the application supports playing, pausing, and stopping MP3 files. It can also seamlessly transition between songs in a playlist.
Folder Selection: Users can select a folder containing MP3 files using the file dialog, and the application will display the available songs in a listbox.
Progress Bar: The progress bar, implemented with tkinter.ttk.Progressbar, shows the current playback position of the song. It updates in real-time using a separate thread for smooth operation.
Metadata Handling: By using the mutagen library, the application reads and utilizes song metadata to manage playback duration and display song progress accurately.
Threading for Real-Time Updates: A dedicated thread ensures that the progress bar and other UI elements update without freezing the main application, providing a seamless user experience.
This project showcases my ability to integrate multiple Python libraries and manage concurrent tasks effectively while creating a user-friendly application.

# Music-app-in-python
