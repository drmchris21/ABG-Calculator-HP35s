# ABG-Calculator-HP35s
Acid/Base disorder calculator based on Arterial Blood Gas Analyser for the HP 35s Calculator 

Editing instructions

Configure your editor to display 8 spaces per tab.

The first column is the line number ex. A015 (always a capital letter and 3 digits).

The second column is the label (see below).

The third column is the actual instruction.

The fourth column is the comments.

The program must run in RPN mode.

Entering the program replace every label name in instructions GTO and XEQ with the actual line number of column 1 of the particular label.


Program Input

P=Ph

C=CO2

H=HCO3

N=Na

L=Cl

Program output

The program uses the following abbreviations:

AC	Acidosis

AL	Alcalosis

R	Respiratory

M	Metabolic

A	Acute

C	Chronic

\+	And

W	With

WO	Without

P	Partially

CMP	Compensated

U	Uncompensated

AGAP	Anion Gap


In Variable G the program stores the Anion Gap (N-H-L)

To run the program turn your HP35s to RPN mode ent type [XEQ] A [ENTER]


The Program uses 2 algorithms, the first in PART2 is a decision tree and the second in PART3 is based on formulas.
It can produce 1 up to 3 answers, the first is from the first algorithm, the second from the second, and a third one in case of metabolic acidosis with anion gap.
