# Coronabot
## Description
Coronabot provides the latest COVID-19 statistics. You can choose a single country to view graphs of cases and deaths since the beginning of the pandemic.
Alternatively, you can compare how each country is fairing by entering two or more countries (up to six).

Available commands:

 - `.stats <country-name/code>`: provides the statistics for a single country. Example: `.stats us`
 - `.stats <country-1> <country-2> ... <country-6>`: compares cases or deaths per million population of up to six countries. Example: `.stats uk us es`
 - `.list`: replies with a direct message listing all available countries with their codes.
 - `.help`: replies with a list of available commands and their usage.
 - `.info`: replies with information about the bot.

`<country-name/code>`: Country codes follow the ISO-3166 (2 letter codes) and country names with two or more parts must use a dash (-) instead of a space, e.g. New Zealand → new-zealand.

Reactions:

- 🗑️ Deletes the bot's message.
- 📈 Sends a linear graph.
- 📉 Sends a logarithmic graph.
- 📊 Sends a bar chart.
- 🧪 Changes data to Cases/1M population (Applicable only when comparing countries).
- 💀 Changes data to Deaths/1M population (Applicable only when comparing countries).

## How to deploy
You need to create a file named `config.json` that contains your discord bot token.
```
{
  "Token": "<your_token>"
}
```
