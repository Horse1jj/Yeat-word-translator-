## How It Works

The vocabulary is stored in a words.json file, making it easy to edit or expand.

The translator dynamically loads words from words.json and displays the meaning when a word is entered.

## adding words 

You can easily add new words and their meanings by editing the words.json file. 

make a pull request 

Open the words.json file in a text editor.
Add a new entry in the format:
"Word": "Meaning"
For example:

``` json 
{
  "Tonka": "A large truck or car, often referring to luxury vehicles.",
  "Twizzy": "Close friend or brother, someone you're very tight with.",
  "NewWord": "The definition of the new word."
}

```

Save the file.

**Notes**

Ensure each word and meaning pair is enclosed in quotes and separated by a colon ```:```
The last entry in the file should not have a trailing comma ```,```
