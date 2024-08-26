#### SQL RESOURCES FETCH

1. Fetch vitals observations
    `v4/fhir/Observation?subject=Patient/BY32923183-3&category=laboratory`
2. Fetch patient problem list
3. Fetch patient diagnosis
    a) All diagnosis
    b) Provisional diagnosis
    c) Confirmed diagnosis
4. Fetch medication requests
5. Fetch allergies


Priority
1. Vitals - https://hie.paperless.co.ke/v4/fhir/Observation?subject=Patient/BY32923183-3&category=laboratory
2. Patient diagnosis - https://hie.paperless.co.ke/v4/fhir/Condition?subject=Patient/BY32923183-3&category=encounter-diagnosis
3. Prescriptions - https://hie.paperless.co.ke/v4/fhir/MedicationRequest?subject=Patient/BY32923183-3