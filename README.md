# ptest8 is some miscellaneous code that gets a json list from the Internet, loads the list into a popover menu when the user pushes the plus button and displays detailed data that is selected from the popover by the user.  The data gotten through json is put into backing store, so the json parsing is done only once.  After that, all data is gotten from the backing store from CoreData.

All the coding was done without using storyboards.  The jsonSWIFTY library was used to simplify json parsing.
