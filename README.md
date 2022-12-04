# INVIDIOUS Web search extension (Unofficial)

This is a fork of [**SearXNG-Web-Exstension**](https://github.com/LoserFox/SearXNG-Web-Exstension) and adds an INVIDIOUS instance as a custom search engine.

[**INVIDIOUS**](https://github.com/iv-org/invidious) is a degoogled youtube search engine.

# How does it work?
Extension use `manifest.json` settings which change your main search engine.

Example:

(**Default settings**)
```json
{
  "chrome_settings_overrides": {
    "search_provider": {
      "search_url": "https://example.com/search?q={searchTerms}"
    }
  }
}
```

(**With addon**)
```json
{
  "chrome_settings_overrides": {
    "search_provider": {
      "search_url": "https://invidious.snopyta.org/search?q=test={searchTerms}"
    }
  }
}
```

# Future Plans that will probably never happen
- the ability to click on the icon and pick an instance of INVIDIOUS
- automatically pick an instance that is running well from [**Here**](https://docs.invidious.io/instances/)


# Contributors
[**Loser Fox**](https://github.com/LoserFoxx) - where I forked the original code from. 
