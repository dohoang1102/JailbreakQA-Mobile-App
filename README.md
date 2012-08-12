##JailbreakQA [un]official mobile application

This is a very early (attempt) of making JailbreakQA mobile and easier to read/reply/ask without dealing with JailbreakQA's desktop site on MobileSafari.

While this may not be very useful to your average jailbreaker, it might come in handy for us (The volunteers at JailbreakQA). That being said, this app may or may not be submitted to a Cydia repository. 



##Contribution

The app is open sourced with the intent that you, developers, will contribute to finishing this application. I certainly can't do it alone, and >1 developers are better than 1. 

So.. Please feel free to contribute to this app by forking it & submitting pull requests to this repository. 

##How it works

How this works is almost too simple. JBQA (which runs on OSQA) has an RSS Feed (thekirbylover pointed that out). The XML is simply parsed and corresponding data is added to an array, which is in turn displayed on a table.

##To-Do List

There's a lot of work to be done! Here is the things I have in mind:

- Create a nice, native-looking, clean interface
- Implement logging in to your account (May require a bit of HTML Parsing)
- Add a feature to ask/reply/comment on questions (May require a bit of HTML Parsing)
- Add comments/answers view (easy with some RSS parsing)
- Properly format questions in a neat, clean UI
- Load unanswered/newest/most voted questions
- Load more questions in the list (currently loads first 30)

##License 

Copyright 2012 Fr0st Development

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License. 