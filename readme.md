# Translation and Ciphers

## Description

This extension allows automatic, client-side translation of dialogue. While
LLMs are good at languages, it's somewhat challenging to make it follow strict language rules. This extension parses messages automatically and translates text using in-built SillyTavern translation APIs.
At the same time, it injects the original messages from before translation on message send, preserving the original context. 

The extension uses localStorage for storing character data at this stage.

!! IMPORTANT !!

Please be careful when enabling this on long, existing chats.
If you open a chat with a huge history (50+ messages) that hasn't been translated yet, 
the extension will attempt to translate/parse all of them at once. This may cause a temporary freeze, lag, or rate limiting, causing the 
extension to stop working entirely.

# Installation

Enter the link for this repository in the input that appears after
clicking "Install Extension" inside Extensions section

You may find the source code on my Github account under /STC-Source
