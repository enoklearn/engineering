# Exercise: CLI Weather

## Overview

| Key | Value |
| --- | --- |
| Goal | Build a simple CLI app using Bash scripts to fetch the weather based on a zip code |
| Duration | 2-4 hours |

You should be able to run a bash script to fetch the weather based on a zip code:

```bash
$ weather --zipcode 29609
```

And get an output like (use your own creativity):

```bash
Currently the weather for 29609 is sunny with a temperature of 72°F — have a nice day!
```

## Steps

Use the following steps to help you progress through the exercise (use your own judgement, these are not precise steps):

1. Find a weather API that can fetch the weather based on a zip code
2. Use [`curl`](https://man7.org/linux/man-pages/man1/curl.1.html) to fetch the weather data from the API
3. Use [`jq`](https://stedolan.github.io/jq/) to parse the JSON data
4. Use `echo` to print the data to the command line
5. Use `--zipcode` flag to pass a zip code to the script (if no zipcode is provided, `echo` an error message)
6. Create a `weather` alias for your bash script to be used in the command line

## Questions

Use these questions to guide your curiosity during the exercise:

- What does curl do?
- What does jq do?
- What does echo do?
- How do you create an alias for a bash script?
- How do you pass a flag to a bash script?

## Reflection

Use the following questions to reflect on what you learned with this exercise and discuss with your mentor:

- What conclusion can you share with your mentor?
- What surprised you about this exercise?
- What did this exercise show you about yourself?
- What did this leave you excited to dig further into? 
- Where do you want to go from here?

## Need help?

- [Join our Discord to ask questions](https://discord.gg/bDVYvG3Czd)
