# Apple Music Listening Insights

This project analyzes your Apple Music listening data and generates visualizations for artist plays, skips, listening time, and more.

## 📥 How to Use

1. **Export Your Library**
   - Open **Apple Music** (or iTunes).
   - From the menu, go to:  
     `File` → `Library` → `Export Library...`
   - Save the exported file as `Library.xml`.

2. **Insert the XML**
   - Place your exported file inside the `data/` directory of this project:
     ```
     /data/Library.xml
     ```

3. **Install Requirements**
   ```bash
   pip install -r build/requirements.txt