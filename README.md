# DNA Sequence Alignment Project

This project is focused on performing DNA sequence alignment using the Needleman-Wunsch algorithm. It takes two DNA sequences and outputs an optimal alignment based on a scoring system that rewards matches and penalizes gaps and mismatches.

## Files
* dna_sequence_alignment.py: This is the main script that implements the Needleman-Wunsch algorithm. It processes two DNA sequences and aligns them based on a defined scoring matrix for matches, mismatches, and gaps.
* seqdump.txt: Contains raw DNA sequence data, used as input for the alignment process. The sequences belong to Drosophila melanogaster and can be analyzed using the provided script.

## Features
* Needleman-Wunsch Algorithm: This dynamic programming algorithm is implemented to find the optimal alignment between two sequences.
* Customizable Scoring: Users can adjust the scoring for matches, mismatches, and gaps based on their specific needs.
* Sequence Input: The script can handle large DNA sequences, and the seqdump.txt file serves as an example dataset for alignment.

Usage
1. Ensure you have Python installed.
2. Run the dna_sequence_alignment.py script in your terminal:
```markdown
python dna_sequence_alignment.py
```
3. The script reads two sequences, aligns them, and displays the optimal alignment.


## Outpus
The program prints out the mutations of the two sequences as well as the visual diagram of where these mutations are happening. 
