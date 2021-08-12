
# Miwok_Android_App

This app displays lists of vocabulary words for the user to learn the Miwok language. 

Miwok is an android app created to get familiarized with android basics such as views, layouts, intents, activities, MediaPlayer, constraint Layout, Adaptor, ListView, 
view recycling, audio Focus, onClickListener, OnAudioFocusChangeListener, etc

The idea of the App:
Miwok is the language of native Americans. In this app, we have a parent activity and 4 child activities. Parent activity displays the categories. On clicking on a category the
relevant child activity opens up.
Child activities are displayed in a listview. Each element in the list has an image, Miwok word, English translation of the Miwok word and audio for the Miwok word.
When the Number category is clicked in the home screen user is navigated to NumbersActivity. In the child activity, we used adaptors to implement view recycling.
AudioFocus has been implemented in the app to avoid playing the app the audio in case of a phone call or other priority apps playing.
