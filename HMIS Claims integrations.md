## Items to be tracked
1. References - everywhere you are creating references to patients, professionals and facilities, use this structure
```
"serviceProvider": {
            "reference": "Organization/FID-22-101101-0",
            "identifier": [
                {
                    "system": https://fr.kenya-hie.health/api/v4/Organization,
                    "value": "FID-22-101101-0"
                }
            ]
    }
 

"subject": {
        "reference": "Patient/CR1383914618670-6",
        "identifier": [
            {
                "system": https://cr.kenya-hie.health/api/v4/Patient,
                "value": "CR6823084673797-8"
            }
        ]
    },



"provider": {
    "reference": "Practitioner/PUID-0142928-6",
    "individual": {
        "identifier": [
            {
                "system": https://hwr.kenya-hie.health/api/v4/Practitioner,
                "value": "PUID-0142928-6"
            }
        ]
    }
}
```
2. Add encounter resource in the SHR bundle
3. Claim submission
4. Check claim status action
5. 
