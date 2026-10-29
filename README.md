# PBA-2
CODE 1:
import re

text = "My PIN codes are 411001, 400001 and 012345."

pattern = r'\b[1-9]\d{5}\b'

pin_codes = re.findall(pattern, text)

print("PIN codes found:", pin_codes)


 CODE 2:
 import re

text = "My PIN codes are 411001, 400001 and 012345."

pattern = r'\b[1-9]\d{5}\b'

pin_codes = re.findall(pattern, text)

print("PIN codes found:", pin_codes)
