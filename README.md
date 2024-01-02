To use, download the project and in rules_1.json change 
"condition": {"urlFilter": "somewebsite.com", "resourceTypes": ["main_frame"] }
to whatever website you want to redirct away from. 


To choose what site you are redirecting to change
"action": {"type": "redirect", "redirect": {"url": "https://www.gutenberg.org/"}},

You can add more sites following the format in rules_1.json.

When you finish all the changes you want go into chrome extensions developer mode and load the folder unpacked. If you ever go in and make changes to the rules_1.json file
you have to reload the extension in the extensions settings for the changes to go into effect.
