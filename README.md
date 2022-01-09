# RadioStats.Online

NOTE: If you wish for your station to be removed, please head to the RadioStats discord ([found here](https://discord.com/invite/uG554Ha3fj)) and contact a Developer.

If you wish to add your station to [RadioStats](https://radiostats.online) then please follow the instructions!

### Adding a Radio:

Please fork the respository and add the following json entry for your station:

(NOTE: If your station requires a special API to be made, please contact a Developer in the RadioStats Discord!)

```json
{
	"id": "Next ID Available",
	"name": "Station Name",
	"shortcode": "shorter version of the name (all in lowercase)",
	"aliases": ["Aliases of the station name"],
	"stream": "Stream URL",
	"website": "Website URL",
	"logo": "Logo URL",
	"hex": "Colour Code to be used (In HEX format i.e #fff)",
	"api": {
		"url": "API URL",
		"song": "Path to Song Object",
		"song_title": "Path inside the song object to title",
		"song_artist": "Path inside the song object to artist",
		"dj": "Path to DJ Object",
		"dj_name": "Path inside the DJ object to name",
		"listeners": "Path to Listeners Object",
		"listeners_data": "Path inside the Listeners object to total"
	}
}
```

## License
[MIT](https://choosealicense.com/licenses/mit/)
