**Caps No Caps** tries sanitize chat messages from any words which appear to be mostly in capital letters.  

## Permissions
- `capsnocaps.ignore` -- players with this permission can bypass this chat filter

## Configuration
- `Word Length Threshold`  
  Words up to the defined length are ignored.  
  This allows short words or abbreviations, which contain mostly or only capital letters, to be written normally  
- `Capital Letter Percentage Threshold (between 0 and 1)`  
  Words with more than the defined percentage of capital letters are converted into lower-case.  
  The value must be between 0 and 1, where 0.4 would mean up to 40% of the word's letters may be capital

### Default Configuration
```json
{
  "Word Length Threshold": 1,
  "Capital Letter Percentage Threshold (between 0 and 1)": 0.4
}
```