EDF4M
=====

Parse of EDF(+) files for matlab.

Using:

[header, signal] = loadEDF( fileName );
where 
  fileName - path to EDF(+) file.
  header - information about channels, subject, time, date, etc + annotations for EDF+ format
  signals - EEG signals in units.
