# Contributions Template

## ***Do not repeat the word if already present.***

## File Name

Create a file name in the format given below in respective folders.

The file name should start with a capital letter.
Restrict to only one word per file.

Format : `[FIRST-ALPHABET]/[Word].json`

Example : `C/Cool.json`


## File Path

Add the word to an existing folder corresponding to the starting letter of the word (folders are already created).

## JSON File 

The file must contain 3 keys

```
word: Your word 
```

``` 
synonyms: One or more synonyms in an array 
```

``` 
antonyms : One or more antonyms in an array
```


## Example file (Word with one synonym) 

```json
{
    "word": "your-word",
    "synonyms": [
        "synonym"
    ],
    "antonyms": [
        "antonym"
    ]
}

```


## Example file (Word with more than one synonym or antonyms) 

```json
{
    "word": "your-word",
    "synonyms": [
        "synonym-1",
	"synonym-2",
	"synonym-3"
    ],
    "antonyms": [
        "antonym-1",
	"antonym-2",
	"antonym-3"
    ]
}

```

## Once done with these steps drop a PR. 

# Happy Hacktoberfest :sunglasses: