# ehr_preprocess
This repo can be used to produce formatted versions of Electronic Health Records for MIMIC and other datasets.\newline
Data is separated into patients_info (static information) and concept.{eventtype}.\newline

patients_info: PID and corresponding static information\newline
concept.{eventtype}: PID, ADMISSION_ID, CONCEPT, TIMESTAMP, (TIMESTAMP_END, VALUE, VALUE_UNIT, ICUSTAY_ID)\newline
