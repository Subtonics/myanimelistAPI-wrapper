## UpdateAnimeAsync
Updates existing anime in user's list asynchronously.

### Parameters

| Name | Description |
| ---- | ----------- |
| [MALAPI.Dto.AnimeEntry] newAnimeInfo | The updated anime entry. |
| [System.Int32] animeId | the ID of the anime entry you want to update. |

### Returns
[System.String] represnting the state of updating "Updated" or detailed error message.

[System.String]: <https://msdn.microsoft.com/en-us/library/system.string(v=vs.110).aspx>
[System.Int32]: <https://msdn.microsoft.com/en-us/library/system.int32(v=vs.80).aspx>
[System.DateTime]: <https://msdn.microsoft.com/en-us/library/system.datetime(v=vs.110).aspx>
[System.Single]: <https://msdn.microsoft.com/en-us/library/system.single(v=vs.80).aspx>

[MALAPI.Dto.AnimeEntry]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Dto/AnimeEntry.md#animeentry>
[MALAPI.Dto.MangaEntry]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Dto/AnimeEntry.md#mangaentry>

[MALAPI.Dto.AnimeSearchResult]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Dto/AnimeSearch.md#animesearchresult>
[MALAPI.Dto.AnimeSearchEntry]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Dto/AnimeSearch.md#animesearchentry>
[MALAPI.Dto.MangaSearchResult]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Dto/MangaSearch.md#mangasearchresult>
[MALAPI.Dto.MangaSearchEntry]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Dto/MangaSearch.md#mangasearchentry>

[MALAPI.AnimeListStatus]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Enumerations.md#animeliststatus>
[MALAPI.MangaListStatus]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Enumerations.md#mangaliststatus>
[MALAPI.EntryScore]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Enumerations.md#entryscore>
[MALAPI.AnimeType]: <https://github.com/i3dprogrammer/myanimelistAPI-wrapper/blob/master/docs/Enumerations.md#animetype>