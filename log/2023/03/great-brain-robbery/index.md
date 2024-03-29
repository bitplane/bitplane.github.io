# This probably already exists

...and is why no text on the Internet after 2017-2018 can be trusted to
be from a real person, rather than an LLM bot farm.

## Method

* First we extract location and background info from users that we have
  training data for.
  It'll help if you're a nation state actor and have collected everyone's
  details for two decades, but it may be possible to do it using public info
  too. Like identify Reddit users, Usenet posters, Twits etc by grossly
  invasive data mining. Obviously the org doing it would need to be in a
  location with awful data protection laws. Using data leaks might help too.
  But the idea is to create a knowledge graph of individuals with queryable
  demographic details, and collect their personal writings.
  We know that most large companies have this data in droves.
* Identify high level groups that represent these groups of people. Location,
  age, background, and so on, and extract their text
* Train an LLM so it predicts tokens from the given demographics and individuals.
* Train it the other way, so it can detect demographics from a corpus of text and
  source locations. This may need some kind of extraction technique first.
* Infer personality types from the data as well as demographics.

## Uses

### Target manipulation

Target specific individuals or broader demographics by fine-tuning using email
history and other information, and test their responses to different angles.
Use the model to actually get an idea of how they might feel about a topic, how
they're best manipulated, where their vulnerabilities are and so on.

Chat with the model, train it on responses.

Use cases here:

* Political campaignig
* Individual marketing
* Incitement by agent provocateurs
* Astroturf testing
* Causing outrage / unrest in specific populations for political ends
* Targeting specific people in groups with high levels of influence
  * Politicians
  * Celebrities
  * CEOs
  * The press

### Target reconnaissance

Use it to figure out the chance that a person belongs to specific demographic
groups, or go meta on this and use it to find the best questions to ask that
cause the target to reveal the most amount of information about themselves.

This can then be used as a way to find hunted people in a list of candidates,
so is likely very useful for military intelligence. Extracting info from
targets could be used to get blackmailable information from large numbers of
people across an economy, like presumably how porn sites are used by Western
powers.

### Troll farms

Pick tons of people in the distributions you want to emulate, generate back
stories and use bots to post online using their specific point of view. We
should be able to write a complaint from the point of view of a 32 year old
nurse who is a single mother, born in Manchester, with one brother etc etc.

Repeat this a million times, you've got an army of different personalities
that can be used to push any agenda.

### Bot and owner detection

Actual people are likely out-of-distribution and far less predictable than
text generated by a language model. Text created by a langauge model will be
in the distribution of its data sets.

Those who have the largest data sources and know what data sources other people
should be able to detect variance from known data collections, and not only
figure out the difference between a bot and real person, but also who is running
the bots.

### Corporate sabotage

Knowing how you can manipulate decision makers, it ought to be possible to not
only make them buy products that aren't the best choice for them, but to trick
them into making decisions that trap them and cause problems.

This could be as simple as using multiple users to ask for a product that's too
expensive to make or maintain, be missold products or services that aren't right
for them, overstretch themselves, change direction at the wrong moment / false
pivots.

By investing a bit in minimal services from a company, false demographics could
be created, then rug pulled later.

Uses:

* economic espionage and sabotage
* hurting your competition (fire and motion, but the motion is the wrong way)
* hedge funds who have shorted a company and then want to collapse it for
  financial gain.
* Tricking companies into creating services that need to exist before some other
  play can be made, at their expense.

### Sybil and asymmetric warfare attacks

Contain, control and influence people, or waste their resources by surrounding
them with false personas that exist to take interaction time from real people.

### Impersonation and fraud

Personalized attacks by impersonating the writing style and backrgound context
of their real contacts.
