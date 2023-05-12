# Simple-ChatGPT-CLI

I believe many others have implement more sophisticated ChatGPT CLI tool. But this is a super simple one without fancy features that I created with Python for my own use case.
My motivation was that using OpenAI API could be much cheaper than subscribing ChatGPT Plus, and is claimed to be more privacy friendly by some legal experts.

I'm not planning adding fancy features unless I start to feel some feature would be a big plus to my productivity in my own use case. But everyone are welcomed to use this basic version or fork it to add their own features.

## Installation

```bash
pip install simple-chatgpt-cli
```

## Usage

You can run the program with
```bash
chatgpt
```

You must either set/save the key following the CLI prompts (recommended) or set an environment variable `OPENAI_API_KEY`.

![screenshot](screenshot.png)

## Tips

Use `#multiline` to enter multiline mode. This is useful when you want to enter messages with line breaks.

Use `#startover` to start a new conversation whenever you switch to a new topic and the bot doesn't need previous context anymore. This helps reduce your OpenAI bill.

The program will remind you this if you come back to an idle conversation after more than 5 minutes.

## Development

This project was initialized by my [Python project boilerplate](https://github.com/tailaiw/python-boilerplate). So you will need all the prerequisites of that project.
