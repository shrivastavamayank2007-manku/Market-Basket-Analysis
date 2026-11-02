# Market Basket Analysis — VS Code Project

## Files
- `index.html`: Complete browser-based application (HTML, CSS, and JavaScript in one file).
- `sample_transactions.csv`: Sample supermarket transactions to import into the app.

## Run it
1. Open this folder in Visual Studio Code.
2. Open `index.html` in your browser (or use the Live Server extension).
3. Click **Import CSV** and select `sample_transactions.csv`.
4. Click **Run Apriori Analysis**.

The CSV has one transaction per row: `TransactionID` identifies the transaction and `Item1`, `Item2`, etc. hold the products. Blank cells mean no additional item in that transaction.

## Customize
- Edit the CSS inside `<style>` to change colors, layout, spacing, and typography.
- Edit the sample dataset in `sample_transactions.csv`.
- Edit the JavaScript inside `<script>` to change Apriori logic, metrics, sorting, or business insights.
- Support and confidence are percentages in the UI (e.g. 30 means 30%).

## Notes
This version runs entirely in the browser and implements Apriori in JavaScript. It does not require Python or `mlxtend`. If your instructor requires the `mlxtend` library specifically, this needs a Python implementation.


