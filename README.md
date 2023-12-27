# Ordered and Unordered Json Data
Ordered and Unordered Json Dataset for MongoDB
There are 4 json files.

## Example Json Format

	{
        "_id": 0,
        "name": "Ryjhmst Pce",
        "scores": [
            {
                "score": 50.00761103337471,
                "type": "exam"
            },
            {
                "score": 82.37607794807423,
                "type": "quiz"
            },
            {
                "score": 92.1551064999335,
                "type": "homework"
            }
        ],
        "school_no": 5968749818,
        "gender": "m",
        "age": 68
    },


## Files

**students_orj.json**: Original Json file. Json objects are sequential. There are 400000 rows of data.

**students_dif_value.json**: Same with students_orj.json. Only the values ​​in the name column are different.

**students_shuffled.json**: It contains the data in students_orj.json, but the json elements are not sequential.

**students_shuffled_dif_items.json**: Same with students_shuffled.json. Only the item numbers in the scores are different.

# License
This project is licensed under the MIT License - see the LICENSE.md file for details
