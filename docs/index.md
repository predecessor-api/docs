# Predecessor API

## Disclaimer

This documenation is maintained by Predecessor community members and is not an official product of Omeda Studios. The intent is to provide a shared knowledge base for current and future users of Omeda Studios' Public API for Predecessor.

The information provided here is contributed by volunteers and is not guaranteed to be up-to-date or accurate. Users should always refer to official Omeda Studios resources for accurate and up-to-date information regarding [Predecessor](https://www.predecessorgame.com/).

## Questions

Join the [Predecessor Discord](https://discord.gg/predecessor) and ask in the [#public-api](https://discord.com/channels/389767672151146498/1097914145610932406) channel.

## About

The Predecessor [Public API](https://www.predecessorgame.com/blog/public-api) has been opened up by Omeda Studios and enables developers/programmers within the community to pull raw data for analysis that can then be shared with the rest of the community.

All documented endpoints share this common base URL:

```
https://backend.production.omeda-aws.com/api/public
```

For example, an API Path of `/get-match/{id}/` should be treated as:

```
https://backend.production.omeda-aws.com/api/public/get-match/{id}/
```

- The API redirects requests without a trailing slash, so either include a trailing `/`, or enable a "follow redirects" mechanism in your code.
- Be mindful of your code's requests per second, put sleeps/pauses between API calls so we don't overload the API servers.
