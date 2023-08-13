# Matches by Epoch

```
{baseURL}/get-matches-since/{epoch}/
```

Returns a collection of 10 matches that ended at or after the given Unix `epoch` timestamp.

For pagination, use the `endTime` of the last match in the collection to fetch the next 10 matches.

## Known Issues

#### Pagination Duplicates

While paginating, the first element of the next page will most likely be a duplicate of the last element of the previous page. Plan around handling duplicate matches when paginating.

#### Potentially Unobtainable Matches

The response being limited to 10 matches means that if more than 10 matches all finish at the exact same time there will be missed matches. For example: If there are 12 matches that ended at exactly `1691873995` then we will only ever see 10 of them.
