I searched in the surgery file for procedure location and found:

130.119  surgery | non-OR location --> pointer to file 44



130. 118  SURGERY  NON-OR PROCEDURE | SetOfCodes  | Y:YES;  | ^SRF(D0,"NON") | 1

This field is a flag signifying this case is a non-OR surgical procedure.

119 SURGERY NON-OR LOCATION |  Pointer  | SC(44 ^SRF(D0,"NON") 2

This is the location (file 44) where this non-OR procedure was performed.  

File 44: HOSPITAL LOCATION  
Contains locations found in the hospital (ie. Wards, Clinics)

However, file 44 does not enumerate these hospital locations.
