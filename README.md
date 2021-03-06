# beatsaver-viewer

[A-Frame]: https://aframe.io
[visit]: https://supermedium.com/beatsaver-viewer/?id=811-535&difficulty=Expert

Web-based viewer for BeatSaver maps, built with [A-Frame] and JavaScript.

**[CLICK TO VIEW][visit]**

![](https://user-images.githubusercontent.com/674727/50229336-f395ca00-035e-11e9-844c-a6bbb07fbf38.jpg)

The viewer works within a normal web browser and can be embedded on any
webpage. It can also be previewed within VR headsets on browsers that support
VR (e.g., [Supermedium](https://supermedium.com)).

Featured on the unofficial [Beat Saber
Songs](https://beatsaber-songs.herokuapp.com/top/all) site.

## Usage

You can [visit or link the viewer directly][visit].

Or if you have a site, you can I-Frame the viewer and pass a query parameter
containing the song ID and difficulty:

```
<iframe src="https://supermedium.com/beatsaver-viewer/?id=811-535&difficulty=Expert">
```

## Roadmap

- Mobile support
- Difficulty switcher
- Custom saber viewer

## Community

*The BeatSaver viewer is an unofficial community project and not officially
affiliated with Beat Saber.*

- [Supermedium Discord](https://supermedium.com/discord)
- [BeastSaber Discord](https://discordapp.com/invite/cZpFayw)
- [BeatSaber Songs](https://beatsaber-songs.herokuapp.com/top/all)

## Development

Built with [A-Frame](https://aframe.io), a web framework that we created for
building VR experiences. And JavaScript.

```
npm install
npm run start
```

Then head to `localhost:9999` in your browser.
