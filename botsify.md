Review of Botsify Chatbot Platform
==================================

Botsify is a tool for designing chatbots for non-technical users, much
like Chatfuel or Motion AI. The interface is perhaps a little less
intuitive than Chatfuel, as different parts of your bot are hidden
behind different menus. It does however, come with some pre-built
templates that might be useful for specific applications: namely
templates for hospitals, travel agencies, restaurants and general
FAQs. The user experience with these default bots leaves a lot to be
desired, as demonstrated in my conversation:

# To do: insert picture

It asks how many guests I want, but fails to recognise "5 guests",
returning a very unfriendly "Invalid Number" message. Similarly, it
doesn't pick up on my typo with "Tomorrw", but is happy once I fix
this mistake. It feels more like I'm interacting with a command line
application.

Editing the bot sometimes feels like a similar experience. I am
presented with errors like "There can be no repetitive user says
blocks at level 9". Ok... That's helpful.

Bot design is in terms of "stories". A story is a linear sequence of
interactions between the bot and the user. It's not clear whether one
story can branch into another or if you would need to create a
different story for each possible route in a possibility tree.

One feature that Botsify has that Chatfuel doesn't is the ability to
recognise what it calls "entities". In fact these are just different
words that it can pick up in the users query. It comes with several
default entities such as the ability to recognise numbers. I managed
to make a simple bot for the Eatalot restaurant that could understand
"I want 5 eggs", but for some reason when I added a similar story for
sausages, that didn't seem to work.

Another nice feature of botsify is the ability to save the users
responses to a form. This could be a great way to collect information
from users. Form responses can easily be exported to CSV through the
web interface.

Botsify has a feature it calls "bot learning and understanding" that
allow you to teach it the meaning of new expressions. Unfortunately
this doesn't seem to be flexible enough to allow multiple entities to
be associated with one phrase. I wanted to teach it that "I'd like 5
sausages please" would be the same as "5 sausages" but I had to choose
either "sausage" or "number" as an entity. What is nice is that you
can look over the training items and remove ones that don't look
right.

Botsify has four payment plans:

 - The free plan allows up to 100 users to interact with your bot
 - The basic plan costs $10 per month and allows you to create three
   bots and contact at most 1,000 users.
 - The premium plan closts $30 and allows you to create five bots and
   contact 5,000 users.
 - The business plan costs $50 and allows unlimited bots and users.
 
All the paid plans allow the integration of RSS and the use of a JSON
API.

Botsify also differs from Chatfuel in not focusing solely on
Messenger. In addition, it offers a web based chatbot (only available
on paid plans) and Alexa skills (currently in beta).

Summary (scores out of 5):

 - Platforms: Messenger, web, Alexa
 - Ease of use: 2
 - Intelligence potential: 3
 - Value for money: 5
