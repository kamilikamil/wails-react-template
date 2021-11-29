# README

## About

The frontend typescript react app is made using `create-react-app --template typescript`.

To use this template run `wails init -n "your-project-name" -t https://github.com/kamilikamil/wails-react-template`, assuming you have installed wails cli. If you haven't, simply run `go install github.com/wailsapp/wails/v2/cmd/wails@latest`

## Building 

To build this project in debug mode, use `wails build`. For production, use `wails build -production`.
To generate a platform native package, add the `-package` flag.

## Live Development

To run in live development mode, run `wails dev` in the project directory. In another terminal, go into the `frontend` 
directory and run `npm run dev`. The frontend dev server will run on http://localhost:34115. Connect to this
in your browser and connect to your application.