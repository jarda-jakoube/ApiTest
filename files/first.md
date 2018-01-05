# newAPi

Polls is a simple API allowing consumers to view polls and vote in them.

## Questions Collection [/questions]

### List All Questions [GET]

+ Response 200 (application/json)
    + Attributes (Family) 
        
# Data Structures

## Family
- `father`: (Person)
    - first_name: Otec
- `mother`: (Person)
    - last_name: krava
- `mother2`: (Person)
- `dogs`: (array[Dog, Dog])

## Dog
- `psi_jmeno`
- `psi_name`

## Person
- `id`: `-1` (number) - unique number
- `first_name`: jmeno (string)
- `last_name`