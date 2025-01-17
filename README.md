# <p align=center> Discord Guild Members Scraper

## <p align=center> Check out my other project<br>[Darkend](https://darkend.tech)

### Features

- Ability to scrape the profile pictures of members in the following formats:
  - `webp`
  - `png`
  - `jpg`
  - `jpeg`
- Scrape all members Usernames, Discrimnators, IDs, Bios and PFPs to a `txt` file.
- Ability to specify which guilds to scrape in the JSON config file.
- Each guild has it's own folder so the data is easy to handle.

### Notes

- There are plenty of things that could be added to the script, feel free to contribute!
- This project is inspired by sertchan's [JS-based tool](https://github.com/sertchan/Discord-Scraper).

### Installation

- Clone repo from git

```sh
>>> git clone <>
```

- Install the dependencies.

```sh
>>> pip install -r requirements.txt
```

- Rename `config.json.example` to `config.json` and edit required settings.
  - Input `channel_id` if you wish to scrape members from a particular channel; else leave 0

### Usage

```sh
>>> cd Discord-Scraper/source
>>> python main.py
```

### Project screenshots

<img src='assets/console.png' style="width: 90%">
<img src='assets/datascraped_folder.png' style="width: 90%">
<img src='assets/guild_folder.png' style="width: 90%">

## License Disclaimer

This project is licensed under the MIT license.

# Note

I will be working on a custom Disocrd library for everything a user account can do very soon, and it will be used in this project instead of `discord.py-self` to ensure it's faster and better than ever.
