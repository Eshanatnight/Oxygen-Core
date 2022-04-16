# Oxygen

Oxygen is a Voice Journal app written in rust. This is a UI Version of the Oxygen CLI. For more information, see the [README]("https://github.com/Eshanatnight/Oxygen-Core.git/Readme.md").

## Running the UI

To run the UI:

```Powershell
    cd .\ui
```

```Powershell
    npm install
```

```Powershell
    npm start
```

## Building Oxygen

Clone the repository

```Powershell
    git clone "https://github.com/Eshanatnight/Oxygen-Core.git"
```

To build a package to `ui/out`:

```Powershell
    cd .\ui
```

```Powershell
    npm run prod:package
```

To create the kind of asset that would get uploaded to GitHub releases:

```Powershell
cd .\ui
```

```Powershell
npm run prod:make
```

## Known Issues

Some of the API calls are not uptodate with the latest Node.js version. So some of the functions are deprecated. And are considered to be vulnerabilities.
