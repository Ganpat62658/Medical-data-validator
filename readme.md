
## Medical data validation program

This programs let you varify the medical records that are in a specific format and tells if valid or not and if not then prints where is the defactes. The format for records is defined as list of dictionaries and inside those dictionary some predefined keys and predefined value types. value itself can be anything as long as it's a corect type and matches with format eg. key = 'patient_id' : value = 'p1001' here the key is fixed it cannot be anything but this at a specific index value can be 'p1002' or 'P101' as long as it starts with p in any either case and follows by a number integer to be specific I used re module for matching the pattern.
