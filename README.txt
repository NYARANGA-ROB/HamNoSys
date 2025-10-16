

Requirements:
*python 3.7 +

Our tool receives HamNoSys symbols. Optionally, the user can also provide their respective glosses. If so, the number of glosses must be equal to the number of HamNoSys symbols. The input must be identified by their quotes.

To run:
   python HamNoSys2SiGML.py "hamnosysSymbols" ("glosses")

   Ex:. python HamNoSyS2SiGML.py "hamnosyssymbol_GOOD hamnosyssymbol_MORNING" ("GOOD MORNING")
   *in brackets are the input which optionally. the brackets should not be included in the input	

The user also can extend the notation by adding the created HamNoSys codes and respective SiGMLs in the conversionSpreadSheet.txt.


parser.py: The parser developed is prepared to read an HTML exported from ELAN with two tiers (Glosses and HamNoSys respectively). If the user wishes to read a different input, for example a different number of tiers, this parser requires the appropriate adjustments.

RunPythonScripts.cs: The python scripts to be saved in a folder "PythonScripts" within the Unity Assets folder. The output from the the parser.py will also be saved in this same folder. The sigml output will be also be saved within the Unity Assets folder, but in the folder "SiGML_Files". 





