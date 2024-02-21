# Clipboard Image Text Extractor

This is a simple flask app that uses pytesseract to extract text from an image from the clipboard. It's containerized with docker so that you don't have to have pytesseract installed on your machine.

## Usage

1. Copy an image to your clipboard
2. Run the docker container
3. Visit `http://localhost:8080/` in your browser

## Running the app

- Dev Mode (has a volume for the app code so you can make changes and see them reflected in the container without rebuilding the image)

```bash
docker compose -f docker-compose.dev.yaml up
```

- Production Mode

```bash
docker compose -f docker-compose.prod.yaml up
```

## Contributing

Feel free to open an issue or a pull request if you have any ideas for improvements or new features.

## Credits

- Favicon: [Analyze](https://icons8.com/icon/7964/analyze) icon by [Icons8](https://icons8.com)
