# TODO List for Improving Book Recommendation System

## Step 1: Adapt Notebook to Use Book Data
- [x] Modify colaborative.ipynb to load BX-Book-Ratings.csv instead of movie data.
- [x] Handle ISBNs as item identifiers; use ISBN as 'title' placeholder since no titles are available.
- [x] Update data merging and pivot table creation for books.

## Step 2: Enhance Data Preprocessing
- [x] Add handling for missing values in ratings.
- [x] Filter out users and items with very few ratings (e.g., users with <5 ratings, items with <10 ratings) to improve quality.
- [x] Normalize ratings if necessary.

## Step 3: Implement User-Based Collaborative Filtering
- [x] Add user-based similarity calculation alongside item-based.
- [x] Generate recommendations based on user similarities.

## Step 4: Add Evaluation Metrics
- [x] Implement RMSE or MAE for model evaluation.
- [x] Split data into train/test sets and evaluate the collaborative filtering.

## Step 5: Add Visualizations
- [x] Create plots for rating distributions, top-rated books, correlation heatmaps.
- [x] Save generated images (e.g., PNG files) in the project directory.

## Step 6: Explore Content-Based Filtering (if possible)
- [ ] If book metadata (e.g., genres, authors) can be added or fetched, implement content-based recommendations.
- [ ] Otherwise, note limitations in README.

## Step 7: Create Comprehensive README.md
- [x] Write README.md with project description, setup instructions, usage, and explanations of algorithms.
- [x] Include sections on data sources, improvements made, and how to run the notebook.

## Step 8: Final Testing and Cleanup
- [x] Run the notebook to ensure it works without errors.
- [x] Update any hardcoded paths or URLs.
- [x] Verify all images are saved correctly.
