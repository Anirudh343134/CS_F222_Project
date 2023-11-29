# CS_F222_Project
Project prepared for the course Discrete Structures for Computer Science Fall 2023

## Usage

1. **Input File:**
   - Create an input file named `input.txt` with the following format:
     - The first line contains a space-separated list of CDCs (Common Disciplinary Courses).
     - The second line contains a space-separated list of electives.
     - Subsequent lines contain preferences of each professor, where each line corresponds to a professor's preferences.

2. **Run the Script:**
   - Execute the script by running the command:
     ```bash
     python script_name.py
     ```
     Make sure to replace `script_name.py` with the actual name of your Python script.

3. **Output:**
   - The script will generate an output file named `output.txt` containing the assignments for each solution.

## Parameters

Adjust the parameters within the script:
- `n1`: Number of professors of category x1.
- `n2`: Number of professors of category x2.
- `n3`: Number of professors of category x3.
- `num_solns`: Number of solutions required.

## File Formats

### Input File (`input.txt`)

The input file should have the following format:

```plaintext
CDC1 CDC2 ... CDCn
Elective1 Elective2 ... Electivek
Prof1_Pref1 Prof1_Pref2 ... Prof1_Prefm
Prof2_Pref1 Prof2_Pref2 ... Prof2_Prefp
...
