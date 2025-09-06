# emoji_poet
Telegram bot that generates a vintage postcard by receiving up to 3 emojis. 

You can look up "Emoji Poet" on Telegram.
Send a message to this bot. 
If your message doesn't contain any emoji, it will return a simple message.
If your message contains emojis, up to three first emojis are processed as an input.
After processing, the bot returns an image that has a vintage postcard style.

Caveats:
- For some reason, the images don't always look like postcards. In my opinion, dev followed this instrucion more closely than pro.
- Not all emojis are processed correctly. I think it's because I can't cover them all specifically. The next step would be to analyze the emojis by an LLM, so that the analysis is always guaranteed.
- The code in the JS nodes can be improved. But as always, the time's not enough for such tasks :)