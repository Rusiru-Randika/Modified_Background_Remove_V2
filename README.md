# Modified Background Remover V2 Web App

This repository contains an updated version of the **Background Remover Web App**, enabling users to upload images, remove their backgrounds, preview the results, and download them. The app leverages the `rembg` library for background removal and `Gradio` for the user interface. The app is optimized to run in Google Colab.

## Features
- **Upload Images**: Supports PNG, JPG, and other common image formats.
- **Background Removal**: Automatically removes the background using AI-powered tools.
- **Preview**: Instantly preview the processed output.
- **Download**: Save the processed image in `.png` format.

## Running the Web App on Google Colab
Follow these steps to use the app on Google Colab:

1. **Open the Notebook**:
   - Use the [Colab Notebook link](https://colab.research.google.com/) provided in the repository.

2. **Install Dependencies**:
   - Run the initial cells to install `gradio`, `rembg`, and other necessary libraries:
     ```bash
     !pip install gradio rembg --quiet
     ```

3. **Run the Code**:
   - Launch the Gradio interface with the following command:
     ```python
     demo.launch(share=True)
     ```

4. **Access the Interface**:
   - Open the public URL displayed (e.g., `https://<unique_id>.gradio.live/`) to interact with the app.

## Usage
1. **Upload an Image**: Click the Upload button to choose a file, or simply use your camera or clipboard.
2. **Remove Background**: Wait for the app to process and remove the background.
3. **Preview Results**: View the background-removed image in the app.
4. **Download Output**: Save the processed image to your device.

## Example
![image](https://github.com/user-attachments/assets/e007ff15-343b-48c3-a252-7f6342cdc2fb)

## Dependencies
- [Pillow](https://python-pillow.org/)
- [rembg](https://github.com/danielgatis/rembg)
- [Gradio](https://gradio.app/)

## Contributing
Feel free to contribute by submitting a pull request or reporting issues.

## License
This project is licensed under the MIT License.

## Contact
For any queries, contact [Rusiru Randika](mailto:rusirurandikakmv@gmail.com).

