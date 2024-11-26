1. Provider
    ```
        "provider": {
        "identifier": [
            {
                "use": "official",
                "type": {
                    "coding": [
                        {
                            "system": "http://ts-kenyahie.health/facility-identifier-type",
                            "code": "fr-code"
                        }
                    ]
                },
                "system": "http://itm/license/provider-license",
                "value": "FID-22-101101-0"
            }
        ],
        "type": "Organization"
    },
    ```
2. Patient
    ```
        "patient": {
            "identifier": [
                {
                    "use": "official",
                    "system": "http://ts-kenyahie.health/patient-identifier",
                    "value": "CR6823084673797-8"
                }
            ]
        }
    ```
3. Profesional
    ```
        "provider": {
            "identifier": [
                {
                    "use": "official",
                    "system": "http://ts-kenyahie.health/professional-identifier",
                    "value": "PUID-0142928-6"
                }
            ],
            "type": "Practitioner"
        }
    ```
4. Coverage
    ```
    "coverage": {
        "identifier": [
            {
                "system": "http://itm/coverage-id",
                "value": "21"
            }
        ]
    },
    ```

5. Insurer
    ```
        "insurer": {
            "identifier": [
                {
                    "use": "official",
                    "system": "http://ts-kenyahie.health/insurer-identifier",
                    "value": "sha"
                }
            ]
        },
    ```


Pending confirmation
1. Careteam provider - currently is PractitionerRole -> replace with practitioner reference since using that ther role/specialty can be extracted
2. Passing parameters for benefits business rules in the eligibility request
3. Value sets required for claims
4. 


Current implementation
1. Expects bundle first rep is a claim resource
2. Expects claims to be stored successfully 
3. 


PreAuth

