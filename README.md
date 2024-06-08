# Node.js Multer Sharp Upload Files Resize Images Tutorial

This project is a tutorial on how to upload files and resize images using Node.js, Multer, and Sharp.

## Project Structure

The project is structured as follows:

- `src/controllers/`: Contains the logic for handling requests. Notable files include `home.js` and `upload.js`.
- `src/routes/`: Contains the routes for the application. The main file is `web.js`.
- `src/views/`: Contains the HTML files for the application. The main file is `index.html`.
- `src/server.js`: The entry point of the application.
- `upload/`: The directory where uploaded files are stored.

## Key Features

- **File Upload:** This project uses the upload controller to handle file uploads. The `uploadFiles` and `uploadImages` functions are used to upload and process the files.
- **Image Resizing:** The project uses the Sharp library to resize images after they are uploaded.
- **Routing:** The routes module handles routing for the application. It uses the `uploadController` and `homeController` to handle requests.

## Running the Project

To run the project, use the start script in the `package.json` file:

```
npm start
```

This will start the server as defined in `src/server.js`.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
