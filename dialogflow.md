A Review of Dialogflow (formerly API.ai)
========================================

I was quite excited to try out Dialogflow for several reasons. First,
I knew it had recently been bought be Google, and I know they wouldn't
buy anything flaky. Secondly, I had just discovered that the company
behind it has a long history (well long in chatbot terms!) - it was
founded as Speaktoit back in 2010. It first produced a virtual
assistant for mobile performed similar tasks to Siri and Google
Now. In 2014 they opened up the technology behind their app as API.ai,
enabling third parties to make use of their speech recognition,
text-to-speech and natural language understanding tools. Finally,
after Google bought them in 2016 the product was renamed Dialogflow,
in October 2017. I'm not quite sure why they settled on that name,
perhaps to go well with Google's flagship machine learning product,
TensorFlow? Personally I thought API.ai was quite a good name.

Anyhow, as you'd expect from Google, the product is
sophisticated. This comes with the downside of being not quite as easy
to use as some of its competitors, in particular Chatfuel. However,
once you've got your head round the concepts, the benefits of the
additional power will definitely pay off.

Dialogue flow is based around "intents". An intent is a representation
of what the user has said in a form that the computer understands. So
if you say "I'd like a train to Norwich", this may be mapped to an
intent that looks something like:

 - Intent name: "train"
 - Destination: "Norwich"
 - Departure location: unknown
 - Desired arrival time: unknown

The nice thing about this is that once the system knows what you are
looking for, it also knows what questions to ask you to help you
achieve your goal. So it may say, "Great, what time would you like to
arrive?" to help determine your desired arrival time.

But what's really powerful about Dialogflow is its built-in ability to
recognise _entities_. These are natural language expressions that are
recognised as belonging to a certain category, for example place names
or times. For example, for the query "I'd like a train from Luton to
Norwich arriving at 3pm", it is able to detect that Norwich and Luton
are "cities" (technically Luton is a town) and that 3pm is a time,
which is returned in ISO-8601 format (for example "15:00:00").

Added to this is another really powerful feature: "contexts". This
allows your app to remember things that have happened and reuse that
information at a later point. For example, after booking the train to
Norwich, I might say "What time does it leave again?" and the bot
would be able to know that I'm talking about the train booking.

What's really nice about Dialogflow is the testing capabilities, which
provide a simulation of your bot as it would work in Google Home. This
means you get to actually talk to your bot! What is a little weird is
that you first have to say "Talk to my test app". After that, you're
actually conversing with your bot.

How much does it cost? There are two options:

 - Dialogflow standard edition is free, and allows a maximum of 1,000
   requests a day and 15,000 per month. It is also limited to 3
   queries per second (averaged over a minute). Support is from the
   community or by email.
 - The enterprise edition costs $0.002 per request for text queries
   and $0.0065 per request for voice interactions, and supports
   unlimited requests, and a maximum of 10 queries per second. It also
   possible to get Google Premium Support for this edition (at an
   additional cost, unless you are already paying for Google Cloud
   support).
   
It's hard to beat this platform: it has excellent features at a
reasonable cost. Although the learning curve may be steeper than other
platforms, the payoff is worth it.

Summary (scores out of 5):

 - Platforms: Messenger, Google Assistant, Slack, Kik, Line, Skype,
   Cisco Spark, Cisco Tropo, Telegram, Twilio, Twitter and Viber.
 - Ease of use: 4
 - Intelligence potential: 5
 - Value for money: 5
