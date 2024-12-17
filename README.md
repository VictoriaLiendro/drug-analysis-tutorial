# drug-analysis-tutorial
This project is based on a YouTube tutorial (https://www.youtube.com/watch?v=jBlTQjcKuaY&amp;ab_channel=freeCodeCamp.org) and the accompanying Jupyter Notebook (dataprofessor/bioinformatics_freecodecamp).   I modified the code to analyze ErbB1 instead of the original target.  

This project will collect real data, from the chEMBL database. In the database the 'Target' refers to the target protein/organism that the drug should act, it could activate or inhibit it.

Here the target will be 'Epidermal growth factor receptor (EGFR or ErbB1)', a protein found on certain types of cells that binds the epidermal growth factor. The epidermal growth factor receptor protein is involved in cell signaling pathways that control cell division and survival. Sometimes, mutations (changes) in the EGFR gene cause epidermal growth factor receptor proteins to be made in higher than normal amounts on some types of cancer cells. This causes cancer cells to divide more rapidly. Drugs that block epidermal growth factor receptor proteins are being used in the treatment of some types of cancer. Epidermal growth factor receptors are a type of receptor tyrosine kinase. Also called EGFR, ErbB1, and HER1.

Filtering for the standard_type='IC50': IC50 is a quantitative measure that indicates how much of a particular inhibitory substance (e.g. drug) is needed to inhibit, in vitro, a given biological process or biological component by 50%. Hence, we will want to have the lower standard_value. For classification, drugs having an standard_value of <=1000 will be 'active', >=10000 will be 'inactive' and in between will be 'intermidiate'. 

