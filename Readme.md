# Oxygen

Oxygen is a Voice Journal app written in rust. This is a UI for the Oxygen CLI. For more information, see the [README]("https://github.com/Eshanatnight/Oxygen-Core.git/Readme.md").

## Running the UI

To run the UI:

```powershell
    cd ./ui
```

```powershell
    npm install
```

```powershell
    npm start
```

## Building Oxygen

Clone the repository

```Powershell
    git clone "https://github.com/Eshanatnight/Oxygen-Core.git"
```

To build a package to `ui/out`:

```
    cd ./ui
    npm run prod:package
```

To create the kind of asset that would get uploaded to GitHub releases:

```
cd ./ui
npm run prod:make
```

## Known Issues

Some of the API calls are not uptodate with the latest Node.js version. So some of the functions are deprecated. And are considered to be vaunerable.