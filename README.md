# Video Downloader and Concatenator

This Python script enables you to seamlessly download and concatenate `.ts` video files from various sources into a unified video file.

## How It Works

### Input File
Provide a text file (`inputs.txt`) comprising a catalog of video sources along with their corresponding folder names. Each line in the file should adhere to the format: `folder_name,video_source_url`.

### Download Process
- The script intelligently extracts video IDs and titles from each URL.
- Leveraging concurrent processing, it swiftly downloads each video file in `.ts` format from the provided sources, enhancing download speed and efficiency.

### Concatenation
- Following the download phase, the script amalgamates all downloaded video files into a single `.ts` file titled `all_videos.ts`.
- Subsequently, it systematically eliminates the temporary `.ts` files to maintain a clutter-free directory.

## Usage

1. **Clone the repository**:
    ```bash
    git clone <repository_url>
    ```

2. **Navigate to the directory**:
    ```bash
    cd <repository_directory>
    ```

3. **Add your video sources to `inputs.txt`**.

4. **Execute the Python script**:
    ```bash
    python video_downloader.py
    ```

5. Upon completion, the concatenated video file `all_videos.ts` will be accessible in the directory.

## Requirements

- Python 3.x
- Selenium
- BeautifulSoup

## Contributing

Contributions are highly encouraged! Prior to making substantial changes, kindly open an issue to discuss your proposed modifications.

## License

This project is licensed under the MIT License. Feel free to peruse the [LICENSE](link_to_license_file) file for more details.

Tailor the content to suit your specific project requisites. This README template exudes professionalism and offers concise directives for users to effectively utilize the script.
