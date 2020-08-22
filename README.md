# H5P InHub Audio Recorder

This is a fork of [H5P Audio Recorder](https://github.com/h5p/h5p-audio-recorder) that allows to save the recording on the server instead of only allow to download the recording, you will need to modify the setFinished event on your back-end to save the result file and register it on the database, I suggest you to add a file column on the h5p_results table.

## Getting started

Grab all the modules:

```bash
npm install
```

Build project for production:

```bash
npm run build
```

Run tests:

```bash
npm test
```

## Translating

Help translate h5p-audio-recorder on [crowdin.com](https://crowdin.com/project/h5p-audio-recorder).

If your language isn't on the list, feel free to make a post in the community [forum](https://h5p.org/forum/6).

## License

*H5P Audio Recorder* is [MIT licenced](LICENCE.md)
