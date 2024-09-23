README: CSV to HTML Converter Script
Overview
This Python script converts race meet data from CSV files into HTML files that display team and athlete scores in a table format. It reads CSV files, extracts information like meet name, date, and descriptions, and generates separate HTML files for each meet.

How It Works
CSV Input: The script processes CSV files that contain race meet details, including team scores and athlete scores.

HTML Output: The script generates HTML files that display the meet information and results in a table format, separating team and athlete scores into two sections.

Process:

Reads CSV files using Python’s csv.reader.
Extracts key information from the first few non-empty rows (name, date, description, etc.).
Builds HTML content with a structured layout for the meet data.
Outputs the result into individual HTML files.
Cloning the Repository
To use this script, clone the repository from GitHub:

Open a terminal or command prompt.

Run the following command to clone the repository:

bash
Copy code
git clone https://github.com/your-username/csv-to-html-meet-scores.git
Replace your-username with the actual GitHub username if needed.

Navigate to the project folder:

bash
Copy code
cd csv-to-html-meet-scores
Files Involved
CSV Files: The script processes three CSV files (you can change these):

meets/56th_Holly-Duane_Raffin_Festival_of_Races_Mens_5000_Meters_D1_Boys_24.csv
meets/Bret_Clements_Bath_Invitational_Mens_5000_Meters_Class_1_24.csv
meets/SEC_Jamboree_#1_Mens_5000_Meters_Junior_Varsity_24.csv
You can replace these paths with your own CSV files.

HTML Files: The script outputs three HTML files:

meet1.html
meet2.html
meet3.html
You can modify these filenames by changing the html1_file, html2_file, and html3_file variables.

How to Run the Script
Ensure you have Python installed: You can download it from Python's official website.

Modify file paths: If you want to use different CSV files or output different HTML files, update the following variables at the top of the script:

csv_file1, csv_file2, csv_file3: Specify the paths to your CSV files.
html1_file, html2_file, html3_file: Specify the desired HTML output filenames.
Run the script:

Open your terminal or command prompt.

Navigate to the folder where you cloned the repository (cd csv-to-html-meet-scores).

Run the script using Python:

bash
Copy code
python script_name.py
Replace script_name.py with the actual script filename.

Output: HTML files will be generated in the project folder, displaying the race results in a structured table format.

Example CSV Format
Here is an example of what your CSV file should look like:

less
Copy code
Meet Name
Meet Date
Meet Link
Meet Description

Place, Team Name, Score
1, Team A, 120
2, Team B, 130
...

Place, Profile Picture, Name, Grade, Time, Team
1, <img_link>, John Doe, 12, 15:30, Team A
2, <img_link>, Jane Smith, 11, 15:45, Team B
...
Requirements
Python 3.x
No external dependencies
Customization
Meet Data: Edit the CSV files with your own data.
HTML Structure: You can adjust the html_content variable in the script to modify the layout or add custom styles.
Notes
Make sure your CSV files follow the expected format for proper conversion.
The script does not include a footer by default, but you can add one in the HTML content section if necessary.


Enjoy using the CSV to HTML converter script!
