```markdown
## Project Structure

The project directory is organized as follows:

- `MasterDictionary/`: Contains the positive and negative word lists as `.docx` files.
- `Extracted_Article/`: This folder will be generated to store the extracted articles from the provided URLs.
- `input.xlsx`: Excel file containing URLs for web content extraction.
- `requirements.txt`: List of required Python packages with versions.
- `Text_Analysis.ipynb`: Python notebook to perform sentiment and readability analysis on extracted articles.
- `webscrap.ipynb`: Python notebook to extract web content using `newspaper3k` library.

## Web Content Extraction

The `web_content_extraction.py` notebook retrieves web content from the provided URLs using the `newspaper3k` library. Extracted articles are saved in the `Extracted_Article` folder. To run the script, execute the following command:

```bash
python web_content_extraction.py
```

## Sentiment and Readability Analysis

The `Text_Analysis.ipynb` Notebook performs sentiment and readability analysis on the extracted articles. It calculates various metrics including sentiment scores, polarity, subjectivity, fog index, word count, syllable count, and more. The results are displayed and saved in a CSV file named `results.csv`. To run the script, execute the following command:


## Example Use Case

Imagine you have a collection of news article URLs in your `input.xlsx` file. You can use these scripts to extract the content of these articles, analyze their sentiment, and calculate readability metrics. The generated `results.csv` file will provide insights into the sentiment distribution and readability of the extracted articles.

## Future Enhancements

- Incorporate more advanced sentiment analysis techniques.
- Provide graphical visualization of sentiment and readability metrics.
- Explore additional features for analyzing text content.

## Acknowledgments

We would like to acknowledge the open-source libraries and resources used in this project, including NLTK, newspaper3k, and others.

## Contact

For any questions or suggestions, please feel free to contact (mailto:datadinesh1@gmail.com).




