# heal-and-connect.github.io

## Development

Install tailwind
```
npm install -D tailwindcss@v3.1.8
```
for some reason `--watch` doesn't work with tailwind v3.2 on Ubuntu 20.04 at time of writing.

Run tailwind:
```
npx tailwindcss -i ./assets/css/input.css -o ./assets/css/style.css --watch
```

Run hugo:
```
hugo server -D
```
