# bug-packagejson-import

Instructions:

- clone the repo
- npm install (only in root of repository necessary)
- open the repo in vs code
- open a.ts
- you should see red line under "useEffect"
- put text cursor over "useEffect"
- press ctrl-. (ctrl-dot)

## expected behavior

- i should be offered to import "useEffect" from react, because I already imported other stuff from react!!

## actual behavior

- i just get offered to add a new function

## versions

vscode: 1.91.1 (user setup)
OS: Windows_NT x64 10.0.19045
typescript: it's using the version installed via npm
