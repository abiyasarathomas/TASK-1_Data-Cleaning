# TASK-1_Data-Cleaning
# Screen Time App Usage Dataset - Cleaned Version

# What Was Cleaned?


- "Standardized column names" (lowercase, no spaces, underscores only)
- "Removed duplicate rows" to avoid repeated records
- "Dropped duplicate columns" like `extra_col_11` to `extra_col_23` that didn’t add value
- "Cleaned the `category` column" (lowercase, no weird spaces)
- "Converted date column" to proper datetime format
- "Fixed numeric columns" like `screen_time_min`, `launches`, `youtube_views`, etc.
- "Dropped rows with missing" `user_id`, `app_name`, or `date`** — those are essential!

---

# Files Included

- `screen_time_app_usage_dataset.csv` – the original raw file
- `screen_time_cleaned.csv` – the sparkling clean, ready-to-analyze file
- `Cleaned.py` – the Python script used to clean the data

---

# Tools Used

- Python 3
- Pandas (our BFF for this task)
- `.isnull()`, `.drop_duplicates()`, and `.astype()` 



# Output

When you run the script, it prints:
- CLEANED ✅
