# DCE-iteration-1

A simple scripted chatbot example for TU/e Industrial Design's Master course Designing Conversational Experiences. The example saves a user response and uses them later. In addition, the user is provided a question with three options, which each have a separate response.

This example uses PicoCSS, a CSS framework that helps with simplicity. https://picocss.com/

# Explanation:
For the first chatbot created in the course designing conversational experiences, I tried to explore the notion of embedding tone into the conversations we have with our chatbots. Often when we converse with chatbots, we have to talk in a littoral manner, explaining our feelings in words. This works, but it seems littoral words do not always capture the needs or feelings of conversation partners. Especially when conversing with partners from high-context cultures, where the meaning of words do not always tell the whole story [7]. This shows that chatbots often seem to be tailored to the more dominant low-context cultures. Where most papers regarding emotions and chat apps try to recognize emotions based on the content of the text message [1,2,3,4], I try to create an environment can be more expressive and transparent about their tone and emotions.

I tried to tackle this lack of context in my chatbot by adding an extra modality, namely speech-like sounds. Additionally, the chatbot UI allows users to adjust the tone their messages. Giving back the idea of tonality in conversations and allowing for more context based communication. The addition of sounds into the chatbot UI was based on the idea that text is not able to convey this additional contextual layer and emojis can be ambiguous or have deeper meanings. By adding sounds that imitate speech, conversation partners can interpret the tone of the message in a more natural way. Here it is important the sounds imitate speech rather than be speech as this emphasises just the tone of the message rather than the pronunciation or accent. In the future, it could be interesting to explore different modalities such as haptics, vibrational patterns or different sounds. One example of an implementation of extra modalities in a chat environment are the apple iMessage effects or VibEmoji a multimodal emoji builder which allows the user to add haptics along their emoji's [6]. Another is ARCADE a chat environment which embeds different modalities through an Augmented Reality character [5].

A benefit of adding additional modalities to chatbots is that it creates a better idea on what how a message might be perceived, as mapping emotions or tones to a slider is rather abstract. Giving an additional representation of the message and its tonality, users can explore the outcome of different settings allowing them to get a feel for how the messages get across.  In the future this emotional slider could be mapped to a variable which can be passed to a large language model, so that it can adjust its responses to suit the contextual situation. In the VibEmoji paper, adding a modality does not only indicate conversations become more expressive, but also indicates better emotional understanding and engaging conversations [6].

The chatbot script takes in mind the tone of the message, for example starting the conversation with "Good" in a cheerful tone, leads to a different path than when starting the conversation with "Good" in a sad tone. Because of tonality, simple scripts based on keywords won't suffice anymore. This requires conversation designers and users to think more about the intent and reception of their messages. Building a framework for high context communication without the need for emoji's, which can be perceived as childish, ironic or have deeper meanings.

[1] https://dl.acm.org/doi/10.1145/3689092.3689959

[2] https://dl.acm.org/doi/10.1145/3125739.3132611

[3] https://dl.acm.org/doi/10.1145/3689092.3689403

[4] https://dl.acm.org/doi/10.1145/3678957.3685759

[5] https://dl.acm.org/doi/10.1145/3686215.3688376

[6] https://dl.acm.org/doi/10.1145/3491102.3501940

[7] https://erinmeyer.com/books/the-culture-map/