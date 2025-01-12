# S&P 500 Valuation Visualization

This project visualizes the relationship between the S&P 500's some fundamental valuation metrics like P/E ratio, equity risk premium, etc. and subsequent 10-year real returns, based on Shiller data dating from 1871 to 2023, using a D3-based interactive scatter plot.

## How to Run

1. Ensure you have Python installed on your system.

2. Start a simple HTTP server to serve the files locally. Open a terminal in the project directory and run the following command:

   ```bash
   python -m http.server
   ```

3. Open your web browser and navigate to:

   ```
   http://localhost:8000
   ```

4. The visualization will load, using the data provided in `data.csv`.

## Notes

- Ensure the `data.csv` file is present in the same directory as the HTML file.
- Modify the `data.csv` file to update the visualization with your own data.

## Requirements

- Python 3.x
- Web browser supporting D3.js (e.g., Chrome, Firefox, Edge)

## Troubleshooting

- If the visualization does not load, ensure the HTTP server is running and the browser URL matches `http://localhost:8000`.
- Check the browser console for any errors.
