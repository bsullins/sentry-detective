# sentry-detective
Dude who touched my car?

# context
Tesla's store loads of falase positives when in Sentry Mode. This makes it difficult to identify if anything worth caring about actually happened. Some viewing apps exist that help comb through the footage however it is still done manually.

# idea
Let's use Machine Learning to do this for us and scan all of the video clips and find if/when something actually happened.

# flow
 - Tesla is in sentry mode
 - something happens
 - Tesla logs clips from Sentry mode cameras (currently narrow front, two side repeaters, and back)
 - User gets notified of events when returning to car
 
 ***sentry detective enters the room***
 - User copies footage to computer
 - User runs footage through sentry detective
 - Sentry detective creates report in a text file with a descirption, timestamp and filename of notable events
 - User views those specific files/times to see if anything happened
