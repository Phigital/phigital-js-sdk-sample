# phigital-js-sdk-sample
Code samples using the Phigital JS SDK

For documentation see:

[External Event Documentation](http://docs.gophigital.com/v1.1/docs/external-actions-and-reactions-explained#external-event-card)


## testharness.html

A sample HTML page that can be used a testbed for your experiences, supporting both check-in functionality and sending
 custom events for completing external event cards.


## integration-samples

Code samples for integrating with 3rd party services.

1. **Gamesalad Demo Experience** - play a Gamesalad HTML5 game and get to a certain point and it will call an external URL
   that triggers an external action - to do this, you need a Gamesalad Pro account (the free version does not have
   the Call URL function). Note that this demo currently only works on iOS8 with the iPhone 6.
2. **Google Forms Test experience** - this is a Google Form that upon submission triggers an External Action
   (with a keyword, but without an Action ID specified in this case) - the reason we didn't specify an Action ID
   is because when you import/export an experience, the Action IDs change - so to preserve portability
   and ease of demo, we omitted the Action ID (aka Event ID).
