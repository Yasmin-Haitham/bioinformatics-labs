# bioinformatics-labs
This folder holds the code for smith waterman algorithm, used to align local segments of DNA, <br>
or with the aid of the provided PAM 250 matrix and the BLOSUM 62 matrix, can align local segments of Protein.<br>
This is the Submition for the final project for the subject CSE486 (UG2018) - Bioinformatics  <br>
To use this code, after downloading it on your own device, you may proceed to upload it on a compatible pyhton notebook application or, online platform such as colab provided by google.<br>
![image](https://user-images.githubusercontent.com/66221948/170883379-87221bf4-677a-4a0f-baa5-0bb0976f4a7e.png) <br>
In the above Image you will find provided the part responsible for running the given functions.<br>
Using the fasta_reader function to read the fasta files provided it with the needed path for said fasta files that hold the sequences you wish to align.<br>
Then using the smith-waterman function to align the files it needs 4 parameters.
They are as follows:<br>
  - First and Second parameters are the 2 files read earlier with the fasta reader function.
  - Third, is the fasta type (1 -> DNA, 2 -> protein)
  - Fourth, is the protein score(1-> blosum,  2->pam, 0-> DNA) this is used to identify which matrix to use.

For any further enquires, please reach out to me on my email (yasmin.h.hekal@gmail.com) 
